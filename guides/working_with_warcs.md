Working with WARCs
==================

If you've got some WARCs, this page aims to help you work our what to do with them.

* [Playback](#playback)

Playback
--------

To play back archived resources, we need to be able to look content up by URL -- mapping 
the requested URL to the WARC records that contain that content as seen at different times.
This is usually done using three components:

1. A content index (CDX) that maps URLs to the series of `(WARC filename, offset)` results, one for each crawled instance, where the `offset` refers to the position in the WARC file where the corresponding WARC Record begins.
2. A resource locator that takes the WARC filename and offset and retrieves the corresponding WARC record.
4. A replay interface that allows the user to request URIs and performs and performs any necessary modifications (e.g. re-writing links) before delivering the response to the user.

When operating at small scale (maybe a few million WARC records at most), tools like pywb and OpenWayback can do all of these for you.
However, when you have a lot of resources, you'll probably need to manage the CDX separately. 

### Large Content Indexes

The two main approaches people are using for large scale CDX indexes are:

1. Big sorted CDX file. Generally constructed using OpenWayback or Pywb's cdx-indexer tools and GNU sort. The basic workflow would be:
```
# ensure sort order is not locale-sensitive
export LC_ALL=C
cdx-indexer warc1.warc | sort > warc1.cdx
cdx-indexer warc2.warc | sort > warc2.cdx
...
sort --merge warc1.cdx warc2.cdx warc3.cdx ... > big.cdx
```

For large scale sorting ensure you give `sort` a large amount of RAM with `--buffer-size` and set `--temporary-directory` to somewhere that can fit the whole dataset.

Generally people using this option have some sort of scheme for doing incremental updates. Like a big master CDX file and one or more smaller ones they add to incrementally and then periodically merge into the big one.

2. A "CDX server" which can incrementally be updated. OutbackCDX is my one, used I think currently by Australia, British Library and New Zealand. SolrWayback is another option. Finally Ilya mentioned recently that PyWb can use a Redis server for this purpose.

The tradeoffs:
• Big sorted CDX file: nice option if your collection doesn't change much. Very easy to understand - just sorted a text file. Very amenable to processing using platforms like Hadoop.
• OutbackCDX: stores the index compressed - about 1/5th the size of the corresponding CDX files. Quite convenient for incremental updates.
• SolrWayback: saves you from maintaining separate Solr and CDX indexes. Although it sounds like in your case you aren't planning to do full text search so this option doesn't make that much sense.
• Redis: off the shelf database tool, intended for datasets that fit inside memory, no compression (although you could possibly use an alternative implementation like LedisDB to gain some of those features)

### Repository Integration

If you need to integrate with your organisations storage facility, rather than using the local filesystem, you'll need to configure 
your playback software to use an external resource locator service. TBC

* HTTP Server supporting byte range requests
* HttpFS
* ...
