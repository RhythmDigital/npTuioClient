npTuioClient
============

TUIO Client plugin for web browsers.

This is a TUIO Client implemented as a NPAPI-based browser plugin. It
uses [reacTIVision's](http://reactivision.sourceforge.net/) TUIO
Client as a base.

The plugin constantly calls a javascript function `tuio_callback`
whenever a new touch event arrives. Having this function called, the
rest is up to you :)

Check also the included examples to see how to use this plugin.

The plugin has been tested and works on Firefox 3.0.10, Google
Chrome 2.0.172.33, and Safari 4.0 on Windows XP. It also works under
Firefox 3 on Ubuntu 8.04.

It doesn't work on Opera 9.64 on Windows XP nor Internet Explorer. 
Since Internet Explorer can't use NPAPI-based plugin, the plugin has
to be ported first to an ActiveX-based plugin.

Download
--------

Download the windows binary build from
<http://cloud.github.com/downloads/fajran/npTuioClient/npTuioClient-0.1-win.zip>

Compile
-------

### Windows

Open the Visual C++ project/solution file and build.

### Linux

TODO: The Makefile is broken. 

Installation
------------

### Windows

Put the plugin file `npTuioClient.dll` under Firefox'/Mozilla'
`plugin` directory. Mine is `C:\Program Files\Mozilla
Firefox\Plugins`.

### Linux

Put the plugin file under `~/.mozilla/plugins`
