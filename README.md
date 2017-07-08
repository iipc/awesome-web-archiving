# Awesome Web Archiving [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Introduction

An [Awesome List](https://github.com/sindresorhus/awesome/blob/master/awesome.md) for getting started with web archiving. Inspired by the [awesome](https://github.com/sindresorhus/awesome) list.

## Table of Contents

   * [Training/Documentation](#trainingdocumentation)
   * [Tools & Software](#tools--software)
   * [Community Resources](#community-resources)
   * [Deprecated](#deprecated)

## Contribute

Please ensure your pull request adheres to the following guidelines:

* Use the following format: 
   * `[Name](link)` (Status: **Stable** or **In Development**) - Brief Description of what the module does
* Make an individual pull request for each new item.
* Link additions should be inserted alphabetically to the relevant category.
* New categories or improvements to the existing categorization are welcome.
* Check your spelling and grammar.
* The pull request and commit should have a useful title.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the owner has waived all copyright and related or neighboring rights to this work.

## The List

### Training/Documentation

* Introductions to web archiving concepts:
    * [What is a web archive?](https://youtu.be/ubDHY-ynWi0) video from [the UK Web Archive YouTube Channel](https://www.youtube.com/channel/UCJukhTSw8VRj-VNTpBcqWkw)
    * [Wikipedia's List of Web Archiving Initiatives](https://en.wikipedia.org/wiki/List_of_Web_archiving_initiatives)
    * [Glossary of Archive-It and Web Archiving Terms](https://support.archive-it.org/hc/en-us/articles/208111686-Glossary-of-Archive-It-and-Web-Archiving-Terms)
    * [The Web Archiving Lifecycle Model](https://archive-it.org/blog/post/announcing-the-web-archiving-life-cycle-model/) -- The Web Archiving Lifecycle Model is an attempt to incorporate the technological and programmatic arms of the web archiving into a framework that will be relevant to any organization seeking to archive content from the web. Archive-It, the web archiving service from the Internet Archive, developed the model based on its work with memory institutions around the world.
* [Awesome Memento](https://github.com/machawk1/awesome-memento)
* More advanced material:
    * [Awesome Memento](https://github.com/machawk1/awesome-memento)
    * [docs.warcbase.org](https://lintool.github.io/warcbase-docs/)
    * [Heritrix Walkthrough](https://github.com/web-archive-group/heritrix-walkthrough) (In development)
    * [The WARC Ecosystem](http://www.archiveteam.org/index.php?title=The_WARC_Ecosystem)
    * [The Web Crawl section of COPTR](http://coptr.digipres.org/Category:Web_Crawl)
    * [warcbase workshop](https://github.com/web-archive-group/warcbase_workshop_vagrant)

### Tools & Software

This list of tools and software is intended to briefly describe some of the most important and widely-used tools related to web archiving. For more details, we recommend you refer to (and contribute to!) these excellent resources from other groups:

* [Comparison of web archiving software](https://github.com/archivers-space/research/tree/master/web_archiving)
* [Awesome Website Change Monitoring](https://github.com/edgi-govdata-archiving/awesome-website-change-monitoring)
* [Web Crawl @ COPTR](http://coptr.digipres.org/Category:Web_Crawl)

#### Acquisition

* [ArchiveFacebook](https://addons.mozilla.org/en-US/firefox/addon/archivefacebook/) (Stable)	- A [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/) add-on for individuals to archive their Facebook accounts.

* [Brozzler](https://github.com/internetarchive/brozzler) (Stable) - A distributed web crawler (爬虫) that uses a real browser (chrome or chromium) to fetch pages and embedded urls and to extract links.

* [F(b)arc](https://github.com/justinlittman/fbarc) (Stable) - A commandline tool and Python library for archiving data from [Facebook](https://www.facebook.com/) using the [Graph API](https://developers.facebook.com/docs/graph-api).
 
* [grab-site](https://github.com/ludios/grab-site) (Stable) - The archivist's web crawler: WARC output, dashboard for all crawls, dynamic ignore patterns.

* [Heritrix](https://webarchive.jira.com/wiki/display/Heritrix/Heritrix) (Stable) - An open source, extensible, web-scale, archival quality web crawler.

* [html2warc](https://github.com/steffenfritz/html2warc) (Stable) - A simple script to convert offline data into a single WARC file.

* [HTTrack](http://www.httrack.com/) (Stable) - An open source website copying utility.

* [Lentil](https://github.com/NCSU-Libraries/lentil) (Stable) - A Ruby on Rails Engine that supports the harvesting of images from Instagram and provides several browsing views, mechanisms for sharing, tools for users to select their favorite images, an administrative interface for moderating images, and a system for harvesting images and submitting donor agreements in preparation of ingest into external repositories.

* [SiteStory](http://mementoweb.github.com/SiteStory/) (Stable) - A transactional archive that selectively captures and stores transactions that take place between a web client (browser) and a web server.

* [twarc](https://github.com/docnow/twarc) (Stable) - A command line tool and Python library for archiving Twitter JSON data.

* [WARCreate](http://matkelly.com/warcreate/) (Stable) - A [Google Chrome](https://www.google.com/intl/en/chrome/browser/) extension for archiving an individual webpage or website to a WARC file.

* [WAIL](https://machawk1.github.io/wail/) (Stable) - A graphical user interface (GUI) atop multiple web archiving tools intended to be used as an easy way for anyone to preserve and replay web pages; [Python](https://machawk1.github.io/wail/), [Electron](https://github.com/n0tan3rd/wail).

* [Web2Warc](https://github.com/helgeho/Web2Warc) (Stable) - An easy-to-use and highly customizable crawler that enables anyone to create their own little Web archives (WARC/CDX).

* [Webrecorder](https://webrecorder.io/) (Stable) - Create high-fidelity, interactive recordings of any web site you browse.

* [Wget](http://www.gnu.org/software/wget/) (Stable) - An open source file retrieval utility that of [version 1.14 supports writing warcs](http://www.archiveteam.org/index.php?title=Wget_with_WARC_output).

* [Wget-lua](https://github.com/alard/wget-lua) (Stable) - Wget with Lua extension.

* [Wpull](https://github.com/chfoo/wpull) (Stable) - A Wget-compatible (or remake/clone/replacement/alternative) web downloader and crawler.

#### Replay

* [PyWb](https://github.com/ikreymer/pywb) (Stable) - A Python (2 and 3) implementation of web archival replay tools, sometimes also known as 'Wayback Machine'.

* [OpenWayback](https://github.com/iipc/openwayback/) (Stable) - The open source project aimed to develop Wayback Machine, the key software used by web archives worldwide to play back archived websites in the user's browser.

* [Webrecorder Player](https://github.com/webrecorder/webrecorderplayer-electron) Webrecorder Player for Desktop OSX/Windows/Linux. (Built with Electron + Webrecorder)

#### Search & Discovery

* [Shine](https://github.com/ukwa/shine) (Stable) - A prototype web archives exploration UI, based on a Solr back-end that has been populated using the [warc-discovery]() indexer.

* [warc-discovery](https://github.com/ukwa/webarchive-discovery) (Stable) - WARC and ARC indexing and discovery tools.

* [WARClight](https://github.com/web-archive-group/warclight) (In Development) - Blacklight instance operating on WARCs indexed using [warc-discovery](https://github.com/ukwa/webarchive-discovery).

#### Utilities

* [HadoopConcatGz](https://github.com/helgeho/HadoopConcatGz) (Stable) - A Splitable Hadoop InputFormat for Concatenated GZIP Files (and *.warc.gz).

* [har2warc](https://github.com/webrecorder/har2warc) - Convert HTTP Archive (HAR) -> Web Archive (WARC) format. (Python)

* [Jwat](https://sbforge.org/display/JWAT/JWAT) (Stable) - Libraries and tools for reading/writing/validating WARC/ARC/GZIP files. (Java)

* [node-warc](https://github.com/N0taN3rd/node-warc) - Parse Web ARChive (WARC) files with `node.js`.

* [The Archive Browser](https://archivebrowser.c3.cx/) - The Archive Browser is a program that lets you browse the contents of archives, as well as extract them. It will let you open files from inside archives, and lets you preview them using Quick Look. WARC is supported. (OSX only, Proprietary app)

* [The Unarchiver](http://unarchiver.c3.cx/unarchiver) - Program to extract the contents of many archive formats, inclusive of WARC, to a file system. Free variant of The Archive Browser. (OSX only, Proprietary app)

* [Warcat](https://github.com/chfoo/warcat) (Stable) - Tool and library for handling Web ARChive (WARC) files. (Python)

* [warcio](https://github.com/webrecorder/warcio) - Streaming WARC/ARC library for fast web archive IO. (Python)

* [warctools](https://github.com/internetarchive/warctools) - Library to work with ARC and WARC files. (Python)

* [wasapi-downloader](https://github.com/sul-dlss/wasapi-downloader) (Stable) - Java command line application to download crawls from WASAPI.

* [WarcPartitioner](https://github.com/helgeho/WarcPartitioner) (Stable) - Partition (W)ARC Files by MIME Type and Year.

* [webarchive](https://github.com/richardlehane/webarchive) - Golang readers for ARC and WARC webarchive formats.

* [webarchive-indexing](https://github.com/ikreymer/webarchive-indexing) - Tools for bulk indexing of WARC/ARC files on Hadoop, EMR or local file system.

#### Analysis

* [ArchiveSpark](https://github.com/helgeho/ArchiveSpark) (Stable) - An Apache Spark framework (not only) for Web Archives that enables easy data processing, extraction as well as derivation.

* [warcbase](http://warcbase.org/) (Stable) - Warcbase is an open-source platform for managing & analyzing web archives.

### Community Resources

#### Blogs and Scholarship

* [IIPC Blog](https://netpreserveblog.wordpress.com/)
* [Web Archiving Roundtable](https://webarchivingrt.wordpress.com/) - Currently dormant, but is a great archive of web archiving resources and links.
* [The Web as History](http://www.ucl.ac.uk/ucl-press/browse-books/the-web-as-history) - An open-source book that provides a conceptual overview to web archiving research, as well as several case studies.

#### Mailing Lists

* [IIPC](http://netpreserve.org/about-us/iipc-mailing-list/)
* [OpenWayback](https://groups.google.com/forum/#!forum/openwayback-dev)
* [WASAPI](https://groups.google.com/forum/#!forum/wasapi-community)

#### Slack

* Ask [@netpreserve](https://twitter.com/NetPreserve) for access to the [IIPC Slack](https://iipc.slack.com/)
* Ask [@ianmilligan1](https://twitter.com/ianmilligan1) for access to the [Archives Unleashed Slack](https://archivesunleashed.slack.com/), a researcher group of people working with web archives.

#### Twitter

* [IIPC](https://twitter.com/NetPreserve)
* [#webarchives](https://twitter.com/search?f=tweets&vertical=default&q=%23webarchives&src=typd)

----

### Deprecated

* [pywb Wayback Web Recorder (Archiver)](https://github.com/ikreymer/pywb-webrecorder) (Sunsetted) - A bare-bones example of how to create a simple web recording and replay system.

* [Warrick](https://code.google.com/archive/p/warrick/downloads) (Unknown) - An open source downloadable tool or web service for reconstructing websites from web archives, using [Memento](http://mementoweb.org/).
