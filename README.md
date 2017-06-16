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
* Link additions should be inserted alphabetically to the relavant category.
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
    * [Glossary of Archive-It and Web Archiving Terms](https://support.archive-it.org/hc/en-us/articles/208111686-Glossary-of-Archive-It-and-Web-Archiving-Terms)
* More advanced material:
    * [Awesome Memento](https://github.com/machawk1/awesome-memento)
    * [The WARC Ecosystem](http://www.archiveteam.org/index.php?title=The_WARC_Ecosystem)

### Tools & Software

#### Acquisition

* [ArchiveFacebook](https://addons.mozilla.org/en-US/firefox/addon/archivefacebook/) (Stable)	- A [Mozilla Firefox](http://www.mozilla.org/en-US/firefox/new/) add-on for individuals to archive their Facebook accounts.

* [Brozzler](https://github.com/internetarchive/brozzler) (Stable) - A distributed web crawler (爬虫) that uses a real browser (chrome or chromium) to fetch pages and embedded urls and to extract links.

* [F(b)arc](https://github.com/justinlittman/fbarc) (Stable) - A commandline tool and Python library for archiving data from [Facebook](https://www.facebook.com/) using the [Graph API](https://developers.facebook.com/docs/graph-api).
 
* [Heritrix](https://webarchive.jira.com/wiki/display/Heritrix/Heritrix) (Stable) - An open source, extensible, web-scale, archival quality web crawler.

* [grab-site](https://github.com/ludios/grab-site) (Stable) - The archivist's web crawler: WARC output, dashboard for all crawls, dynamic ignore patterns.

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

* [Warcat](https://github.com/chfoo/warcat) - Tool and library for handling Web ARChive (WARC) files.

#### Replay

* [PyWb](https://github.com/ikreymer/pywb) (Stable) - A Python (2 and 3) implementation of web archival replay tools, sometimes also known as 'Wayback Machine'.

* [OpenWayback](https://github.com/iipc/openwayback/) (Stable) - The open source project aimed to develop Wayback Machine, the key software used by web archives worldwide to play back archived websites in the user's browser.

* [Webrecorder Player](https://github.com/webrecorder/webrecorderplayer-electron) Webrecorder Player for Desktop OSX/Windows/Linux). (Built with Electron + Webrecorder)


#### Utilities

* [HadoopConcatGz](https://github.com/helgeho/HadoopConcatGz) (Stable) - A Splitable Hadoop InputFormat for Concatenated GZIP Files (and *.warc.gz)

* [Jwat](https://sbforge.org/display/JWAT/JWAT) (Stable) - Libraries and tools for reading/writting/validating WARC/ARC/GZIP files.

* [Warcat](https://github.com/chfoo/warcat) (Stable) - Tool and library for handling Web ARChive (WARC) files.

* [WarcPartitioner](https://github.com/helgeho/WarcPartitioner) (Stable) - Partition (W)ARC Files by MIME Type and Year

#### Analysis

* [ArchiveSpark](https://github.com/helgeho/ArchiveSpark) (Stable) - An Apache Spark framework (not only) for Web Archives that enables easy data processing, extraction as well as derivation.

* [warcbase](http://warcbase.org/) (Stable) - Warcbase is an open-source platform for managing analyzing web archives.

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
