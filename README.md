DisableMonitor 

IT BUILT ON 10.15 SDK
*I will give instructions to build in the future*
==============
Adds the missing feature to disable a monitor on your Mac!

Easily disable, enable or change the resolution of a monitor! 


![](https://raw.githubusercontent.com/Eun/DisableMonitor/res/screenshot1.png)

[![Download](https://raw.githubusercontent.com/Eun/DisableMonitor/res/download.png)](https://github.com/Eun/DisableMonitor/releases/)

Console Usage
============
You can use DisableMonitor with the console.  
Following switches are available:
```
$ /Applications/DisableMonitor.app/Contents/MacOS/DisableMonitor --help
usage: DisableMonitor [options]
Options:
-l, --list         list all attached monitors
-d, --disable ID   disable monitor with specified id
-e, --enable ID    enable monitor with specified id
-h, --help         show this help
```

Example Usage:
```
$ /Applications/DisableMonitor.app/Contents/MacOS/DisableMonitor --list
 ID         Name
----------- -----------------
 188823026  SyncMaster (1)
 188834480  SyncMaster (2)
----------- -----------------
$ /Applications/DisableMonitor.app/Contents/MacOS/DisableMonitor --disable 188834480
```

(More switches might be coming)


Contribution
============

You can contribute to this project! Just create a fork, do the changes and do a pull request.  
Add new features, languages or what ever you think could enhance the app.

Building
========

Building requires the [OSX 10.6 Framework](https://github.com/Eun/Mac_OSX_SDKs)

Changelog
=========

1.92:
* Issue #27 Fixed

1.9:
* Automatic update checks
* Code cleaning
* Rules BETA (Issue #13)
* Updated console usage

1.8:
* Added Yosemite White Icon
* Added posibility to disable mirrored monitor (Issue #9)

1.7:
* Added Updater
* Added Quit Menu (Alternative Menu)
* Added Start Screensaver Menu (Alternative Menu)
* Added console usage (Issue #8)
* Added About Dialog

1.6:
* Added Icons
* Added Lock Screens
* Fixed Issues #5 & #6

1.5:
* Minor Bugfixes

1.4:
* Manage Resolutions
+ Ratio

1.3:
* Support for 10.6

1.2:
* Move windows from disabled monitor to an active one

1.1: 
* Resolution can now be changed!
* Bugfixes
* improved stability
* added German language

Notes
-----
App Icon by http://ionicons.com/
