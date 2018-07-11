# GraphvizPreview—SublimeText Plugin

Simply highlight a graphviz snippet in your file, and hit `super+shift+g` to view it.  You can also click in the the body of a snippet.  Easy!

![Example video of plugin](https://packagecontrol.io/readmes/img/376d256c225f965ec94ee25c42e66c60a98a55a7.gif)

## Install

Install the package `GraphvizPreview` through [Package Control](https://packagecontrol.io/packages/GraphvizPreview).  Works with Sublime Text 2 and Sublime Text 3 Beta.

### Install Dependencies

This package also requires `dot` to be installed.

#### MacOS

Install graphviz using [Homebrew](http://brew.sh/)

```
brew install graphviz
```

## Installation (Manual)

For windows: 
* Download and install GraphViz. 
* Add the GraphViz bin folder to the env PATH variable (C:\Program Files (x86)\Graphviz\bin)

Common: 
* Download the zip.
* Rename resulting folder to `GraphvizPreview`.
* Place the folder in your Sublime Text Packages folder.

## Changelog

### Next release

* Add Windows & Linux Support
* Configurable hot key
* Configurable `dot` binary location

### v0.1.1

* Added Sublime Text 3 Support

### v0.1.0

* Created preview plugin for Sublime Text 2 on Mac OS
