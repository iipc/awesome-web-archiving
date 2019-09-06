# Awesome Web Archiving [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Introduction

An [Awesome List](https://github.com/sindresorhus/awesome/blob/master/awesome.md) for getting started with web archiving. Inspired by the [awesome](https://github.com/sindresorhus/awesome) list.

## Table of Contents

   * [Training/Documentation](#trainingdocumentation)
   * [Resources for Web Publishers](#resources-for-web-publishers)
   * [Tools & Software](#tools--software)
       * [Acquisition](#acquisition)
       * [Replay](#replay)
       * [Search & Discovery](#search--discovery)
       * [Utilities](#utilities)
       * [Analysis](#analysis)
       * [Quality Assurance](#quality-assurance)
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
* The WARC Standard
    * The [warc-specifications](https://iipc.github.io/warc-specifications/) community HTML version of the official specification and hub for new proposals.
    * The [offical ISO 28500 WARC specification homepage](http://bibnum.bnf.fr/WARC/).
* More advanced material:
    * [Awesome Memento](https://github.com/machawk1/awesome-memento)
    * [Archives Unleashed Toolkit documentation](http://archivesunleashed.org/aut/)
    * [Heritrix Walkthrough](https://github.com/web-archive-group/heritrix-walkthrough) (In development)
    * [The WARC Ecosystem](http://www.archiveteam.org/index.php?title=The_WARC_Ecosystem)
    * [The Web Crawl section of COPTR](http://coptr.digipres.org/Category:Web_Crawl)
    * [warcbase workshop](https://github.com/web-archive-group/warcbase_workshop_vagrant)

### Resources for Web Publishers

These resources can help when working with individuals or organisations who publish on the web, and who want to make sure their site can be archived.

* [Stanford Libraries' Archivability pages](https://library.stanford.edu/projects/web-archiving/archivability)
* The [Archive Ready](http://archiveready.com/) tool, for estimating how likely a web page will be archived successfully.

### Tools & Software

This list of tools and software is intended to briefly describe some of the most important and widely-used tools related to web archiving. For more details, we recommend you refer to (and contribute to!) these excellent resources from other groups:

* [Comparison of web archiving software](https://github.com/archivers-space/research/tree/master/web_archiving)
* [Awesome Website Change Monitoring](https://github.com/edgi-govdata-archiving/awesome-website-change-monitoring)
* [Web Crawl @ COPTR](http://coptr.digipres.org/Category:Web_Crawl)

#### Acquisition

* [ArchiveBox](https://github.com/pirate/ArchiveBox) (In Development) - A tool which maintains an additive archive from RSS feeds, bookmarks, and links using wget, chrome headless, and other methods. (formerly `Bookmark Archiver`)

* [archivenow](https://github.com/oduwsdl/archivenow) (Stable) - A [Python library](http://ws-dl.blogspot.com/2017/02/2017-02-22-archive-now-archivenow.html) to push web resources into on-demand web archives.

* [Brozzler](https://github.com/internetarchive/brozzler) (Stable) - A distributed web crawler (爬虫) that uses a real browser (chrome or chromium) to fetch pages and embedded urls and to extract links.

* [Chronicler](https://github.com/CGamesPlay/chronicler) (In Development) - Web browser with record and replay functionality.

* [Crawl](https://git.autistici.org/ale/crawl) (Stable) - A simple web crawler in Golang.

* [crocoite](https://github.com/promyloph/crocoite) (In Development) - Crawl websites using headless Google Chrome/Chromium and save resources, static DOM snapshot and page screenshots to WARC files.

* [F(b)arc](https://github.com/justinlittman/fbarc) (Stable) - A commandline tool and Python library for archiving data from [Facebook](https://www.facebook.com/) using the [Graph API](https://developers.facebook.com/docs/graph-api).

* [freeze-dry](https://github.com/WebMemex/freeze-dry) (In Development) – JavaScript library to turn page into static, self-contained HTML document; useful for browser extensions.

* [grab-site](https://github.com/ArchiveTeam/grab-site) (Stable) - The archivist's web crawler: WARC output, dashboard for all crawls, dynamic ignore patterns.

* [Heritrix](https://github.com/internetarchive/heritrix3/wiki) (Stable) - An open source, extensible, web-scale, archival quality web crawler.

* [html2warc](https://github.com/steffenfritz/html2warc) (Stable) - A simple script to convert offline data into a single WARC file.

* [HTTrack](http://www.httrack.com/) (Stable) - An open source website copying utility.

* [Lentil](https://github.com/NCSU-Libraries/lentil) (Stable) - A Ruby on Rails Engine that supports the harvesting of images from Instagram and provides several browsing views, mechanisms for sharing, tools for users to select their favorite images, an administrative interface for moderating images, and a system for harvesting images and submitting donor agreements in preparation of ingest into external repositories.

* [SingleFile](https://github.com/gildas-lormeau/SingleFile) (Stable) - Browser extension for Firefox/Chrome and CLI tool to save a faithful copy of a complete page as a single HTML file.

* [SiteStory](http://mementoweb.github.com/SiteStory/) (Stable) - A transactional archive that selectively captures and stores transactions that take place between a web client (browser) and a web server.

* [Social Feed Manager](https://gwu-libraries.github.io/sfm-ui/) (Stable) - Open source software that enables users to create social media collections from Twitter, Tumblr, Flickr, and Sina Weibo public APIs. 

* [Squidwarc](https://github.com/N0taN3rd/Squidwarc) (In Development) - An [open source, high-fidelity, page interacting](http://ws-dl.blogspot.com/2017/07/2017-07-24-replacing-heritrix-with.html) archival crawler that uses Chrome or Chrome Headless directly.

* [StormCrawler](http://stormcrawler.net/) (Stable) - A collection of resources for building low-latency, scalable web crawlers on Apache Storm.

* [twarc](https://github.com/docnow/twarc) (Stable) - A command line tool and Python library for archiving Twitter JSON data.

* [WARCreate](http://matkelly.com/warcreate/) (Stable) - A [Google Chrome](https://www.google.com/intl/en/chrome/browser/) extension for archiving an individual webpage or website to a WARC file.

* [Warcworker](https://github.com/peterk/warcworker) (Stable) - An open source, dockerized, queued, high fidelity web archiver based on Squidwarc with a simple web GUI.

* [WAIL](https://machawk1.github.io/wail/) (Stable) - A graphical user interface (GUI) atop multiple web archiving tools intended to be used as an easy way for anyone to preserve and replay web pages; [Python](https://machawk1.github.io/wail/), [Electron](https://github.com/n0tan3rd/wail).

* [Web2Warc](https://github.com/helgeho/Web2Warc) (Stable) - An easy-to-use and highly customizable crawler that enables anyone to create their own little Web archives (WARC/CDX).

* [WebMemex](https://webmemex.org/) (In Development) - Browser extension for Firefox and Chrome which lets you archive web pages you visit.

* [Webrecorder](https://webrecorder.io/) (Stable) - Create high-fidelity, interactive recordings of any web site you browse.

* [Wget](http://www.gnu.org/software/wget/) (Stable) - An open source file retrieval utility that of [version 1.14 supports writing warcs](http://www.archiveteam.org/index.php?title=Wget_with_WARC_output).

* [Wget-lua](https://github.com/alard/wget-lua) (Stable) - Wget with Lua extension.

* [Wpull](https://github.com/chfoo/wpull) (Stable) - A Wget-compatible (or remake/clone/replacement/alternative) web downloader and crawler.

#### Replay

* [PyWb](https://github.com/ikreymer/pywb) (Stable) - A Python (2 and 3) implementation of web archival replay tools, sometimes also known as 'Wayback Machine'.

* [OpenWayback](https://github.com/iipc/openwayback/) (Stable) - The open source project aimed to develop Wayback Machine, the key software used by web archives worldwide to play back archived websites in the user's browser.

* [Webrecorder Player](https://github.com/webrecorder/webrecorderplayer-electron) - Webrecorder Player for Desktop OSX/Windows/Linux. (Built with Electron + Webrecorder)

* [InterPlanetary Wayback (ipwb)](https://github.com/oduwsdl/ipwb) - Web Archive (WARC) indexing and replay using IPFS.

#### Search & Discovery

* [SecurityTrails](https://securitytrails.com/) - Web based archive for WHOIS and DNS records. REST API available free of charge. 

* [Tempas v1](http://tempas.L3S.de/v1) (Stable) - Temporal web archive search based on [Delicious](https://en.wikipedia.org/wiki/Delicious_(website)) tags.

* [Tempas v2](http://tempas.L3S.de/v2) (Stable) - Temporal web archive search based on links and anchor texts extracted from the German web from 1996 to 2013 (results are not limited to German pages, e.g., [Obama@2005-2009 in Tempas](http://tempas.l3s.de/v2/query?q=obama&from=2005&to=2009)).

* [webarchive-discovery](https://github.com/ukwa/webarchive-discovery) (Stable) - WARC and ARC full-text indexing and discovery tools, with a number of associated tools capable of using the index shown below:

    * [Shine](https://github.com/ukwa/shine) (Stable) - A prototype web archives exploration UI, developed with researchers as part of the [Big UK Domain Data for the Arts and Humanities project](https://buddah.projects.history.ac.uk/).

    * [SolrWayback](https://github.com/netarchivesuite/solrwayback) (In Development) - A prototype web archives exploration UI with integrated playback functionality for WARCs.

    * [Warclight](https://github.com/archivesunleashed/warclight) (In Development) - A Project Blacklight based Rails engine that supports the discovery of web archives held in the WARC and ARC formats. 
    
    * [Wasp](https://github.com/webis-de/wasp) (In Development) - A fully functional prototype of a personal [web archive and search system](http://desires.dei.unipd.it/papers/paper4.pdf).
    
    * Other possible options for builting a front-end are listed on in the `webarchive-discovery` wiki, [here](https://github.com/ukwa/webarchive-discovery/wiki/Front-ends).

#### Utilities

* [ArchiveTools](https://github.com/recrm/ArchiveTools) - Collection of tools to extract and interact with WARC files. (Python)

* [HadoopConcatGz](https://github.com/helgeho/HadoopConcatGz) (Stable) - A Splitable Hadoop InputFormat for Concatenated GZIP Files (and *.warc.gz).

* [har2warc](https://github.com/webrecorder/har2warc) - Convert HTTP Archive (HAR) -> Web Archive (WARC) format. (Python)

* [httpreserve.info](httpreserve.info) (Stable) - Service to return the status of a web page or save it to the Internet Archive. Returns JSON via browser or command line via CURL using GET. (Golang Package)

* [HTTPreserve Workbench](https://github.com/httpreserve/workbench) (In Development) - Tool and API to describe the status of a web page encoded in a simple JSON output describing current status, and earliest and latest links on wayback.org. Save a web page to the Internet Archive. Audit lists of URIs and output a CSV with the data described above. (Golang)

* [Jwat](https://sbforge.org/display/JWAT/JWAT) (Stable) - Libraries and tools for reading/writing/validating WARC/ARC/GZIP files. (Java)

* [node-cdxj](https://github.com/N0taN3rd/node-cdxj) (Stable) - [CDXJ](https://github.com/oduwsdl/ORS/wiki/CDXJ) file parser. (Node.js)

* [node-warc](https://github.com/N0taN3rd/node-warc) (Stable) - Parse WARC files or create WARC files using either [Electron](https://electron.atom.io/) or [chrome-remote-interface](https://github.com/cyrus-and/chrome-remote-interface). (Node.js)

* [OutbackCDX](https://github.com/nla/outbackcdx) (Stable) - RocksDB-based capture index (CDX) server supporting incremental updates and compression. Can be used as backend for OpenWayback, PyWb and [Heritrix](https://github.com/ukwa/ukwa-heritrix/blob/master/src/main/java/uk/bl/wap/modules/uriuniqfilters/OutbackCDXRecentlySeenUriUniqFilter.java).

* [py-wasapi-client](https://github.com/unt-libraries/py-wasapi-client) (Stable) - Command line application to download crawls from WASAPI. (Python)

* [The Archive Browser](https://archivebrowser.c3.cx/) - The Archive Browser is a program that lets you browse the contents of archives, as well as extract them. It will let you open files from inside archives, and lets you preview them using Quick Look. WARC is supported. (OSX only, Proprietary app)

* [The Unarchiver](http://unarchiver.c3.cx/unarchiver) - Program to extract the contents of many archive formats, inclusive of WARC, to a file system. Free variant of The Archive Browser. (OSX only, Proprietary app)

* [tikalinkextract](https://github.com/httpreserve/tikalinkextract) (In Development) - Extract hyperlinks as a seed for web archiving from folders of document types that can be parsed by Apache Tika. (Golang, Apache Tika Server)

* [Warcat](https://github.com/chfoo/warcat) (Stable) - Tool and library for handling Web ARChive (WARC) files. (Python)

* [warcio](https://github.com/webrecorder/warcio) - Streaming WARC/ARC library for fast web archive IO. (Python)

* [warctools](https://github.com/internetarchive/warctools) - Library to work with ARC and WARC files. (Python)

* [wasapi-downloader](https://github.com/sul-dlss/wasapi-downloader) (Stable) - Java command line application to download crawls from WASAPI.

* [WarcPartitioner](https://github.com/helgeho/WarcPartitioner) (Stable) - Partition (W)ARC Files by MIME Type and Year.

* [webarchive](https://github.com/richardlehane/webarchive) - Golang readers for ARC and WARC webarchive formats.

* [webarchive-indexing](https://github.com/ikreymer/webarchive-indexing) - Tools for bulk indexing of WARC/ARC files on Hadoop, EMR or local file system.

* [wikiteam](https://github.com/WikiTeam/wikiteam) (Stable) - Tools for downloading and preserving wikis

#### Analysis

* [ArchiveSpark](https://github.com/helgeho/ArchiveSpark) (Stable) - An Apache Spark framework (not only) for Web Archives that enables easy data processing, extraction as well as derivation.

* [Archives Unleashed Cloud](https://cloud.archivesunleashed.org) (Stable) - Archives Unleashed Cloud (AUK) is an web interface for analysing web archives. Currently, it can sync with Archive-It collections and extract hyperlink networks, full text, and other information from your collections.

* [Archives Unleashed Notebooks](https://github.com/archivesunleashed/auk-notebooks) - Jupyter notebooks to assist in creating additional analysis and visualizations of Archives Unleashed Cloud derivatives.

* [Archives Unleashed Toolkit](https://github.com/archivesunleashed/aut) (Stable) - Archives Unleashed Toolkit (AUT) is an open-source platform for analyzing web archives.

#### Quality Assurance

* [Chrome Check My Links](https://chrome.google.com/webstore/detail/check-my-links/ojkcdipcgfaekbeaelaapakgnjflfglf) - Browser extension: a link checker with more options

* [Chrome link checker](https://chrome.google.com/webstore/detail/link-checker/aibjbgmpmnidnmagaefhmcjhadpffaoi) - Browser extension: basic link checker

* [Chrome link gopher](https://chrome.google.com/webstore/detail/bpjdkodgnbfalgghnbeggfbfjpcfamkf/publish-accepted?hl=en-US&gl=US) - Browser extension: link harvester on a page 

* [Chrome Open Multiple URLs](https://chrome.google.com/webstore/detail/open-multiple-urls/oifijhaokejakekmnjmphonojcfkpbbh?hl=de) - Browser extension: opens multiple URLs and also extracts URLs from text

* [Chrome Revolver](https://chrome.google.com/webstore/detail/revolver-tabs/dlknooajieciikpedpldejhhijacnbda) - Browser extension: switches between browser tabs

* [FlameShot](https://github.com/lupoDharkael/flameshot) - Screen capture and annotation on Ubuntu

* [PlayOnLinux](https://www.playonlinux.com/en/) - For running Xenu and Notepad++ on Ubuntu

* [PlayOnMac](https://www.playonmac.com/en/) - For running Xenu and Notepad++ on MacOS.

* [Windows Snipping Tool](https://support.microsoft.com/en-gb/help/13776/windows-use-snipping-tool-to-capture-screenshots) - Windows built-in for partial screen capture and annotation. On MacOS you can use Command + Shift + 4 (keyboard shortcut for taking partial screen capture)

* [WineBottler](http://winebottler.kronenberg.org/) - For running Xenu and Notepad++ on MacOS.

* [xDoTool](https://github.com/jordansissel/xdotool) - Click automation on Ubuntu

* [Xenu](http://home.snafu.de/tilman/xenulink.html) - Desktop link checker for Windows


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
* [Fill out this request form](https://docs.google.com/forms/d/e/1FAIpQLScXPIH0Ssw63yWqyMkUqHVYmz2-ItBMzHiJQ-sOlJwTA8u5AQ/viewform?usp=sf_link) for access to the [Archives Unleashed Slack](https://archivesunleashed.slack.com/), a researcher group of people working with web archives.
* [Invite yourself](https://archivers-slack.herokuapp.com/) to the [Archivers Slack](https://archivers.slack.com), a multi-disciplinary effort for archiving projects run in affiliation with [EDGI](https://envirodatagov.org/archiving/) and [Data Together](http://datatogether.org/).

#### Twitter

* [IIPC](https://twitter.com/NetPreserve)
* [#webarchives](https://twitter.com/search?f=tweets&vertical=default&q=%23webarchives&src=typd)

----

### Deprecated

* [ArchiveFacebook](https://addons.mozilla.org/en-US/firefox/addon/archivefacebook/) (Abandoned) - A [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/) add-on for individuals to archive their Facebook accounts.

* [pywb Wayback Web Recorder (Archiver)](https://github.com/ikreymer/pywb-webrecorder) (Sunsetted) - A bare-bones example of how to create a simple web recording and replay system.

* [Warrick](https://code.google.com/archive/p/warrick/downloads) (Unknown) - An open source downloadable tool or web service for reconstructing websites from web archives, using [Memento](http://mementoweb.org/).
