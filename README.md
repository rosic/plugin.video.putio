Important Notice
---------------------------------------

This addon was developed for put.io APIv1. put.io team has recently released
APIv2 and they are about to pull the plug for old one. Hopefully there is also
good news! My ex-colleague [Aybars Badur](https://github.com/ybrs) has forked 
this addon and created an APIv2 compatible version. You can get it from 
[here](https://github.com/ybrs/putio-xbmc-v2).

This addon is included in Dharma (10.x) release addons repository but not in latest
Eden (11.x) release. If the development continues, we'll apply for the new repository.


About put.io
---------------------------------------

[put.io](http://put.io) is a storage service that fetches media files (from various 
sources) and lets you stream them immediately. You can use it to stream video, listen
to your music and share your library with friends. Your files are always a few touches
away within various devices and software.

This addon uses put.io's publicly available API which is written in Python. Any
issues about this addon can be either reported via github issues or help.put.io

This addon is now officialy supported by put.io.

About XBMC
---------------------------------------

[XBMC](http://xbmc.org) is an open source media center software which runs on most major
platforms and is able to play nearly all media formats. It can stream from various
sources by itself or through third party addons (written in Python) which can be
downloaded from its repositories.

Installation
---------------------------------------

Just zip this directory and install it via XBMC's related menu.

You need to have an api key & secret pair belonging to an active put.io account
in order to use this addon. After installation, you should go to its settings
and enter those information into the related fields.

TODO
---------------------------------------

* Download items to the specified folder in settings using wget/curl or some Python lib
* Download progress bar
* Fill in audio/video information in listing (API doesn't expose much for now)
* Search
* Next/previous in listing

