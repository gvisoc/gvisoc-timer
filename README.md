# \<gvisoc-timer\> [![Build Status](https://travis-ci.org/gvisoc/gvisoc-timer.svg?branch=master)](https://travis-ci.org/gvisoc/gvisoc-timer.svg?branch=master)

A basic parameterizable timer that only works when its attributes are coherent (avoiding overflows). It is strongly recommended to read component's documentation by browsing [http://localhost:8080/components/gvisoc-timer/](http://localhost:8080/components/gvisoc-timer) after running `polymer serve`, because it has all the detail on some caveats found during the development of this component and how I avoided them. It also has links to the corresponding document where you can find the rationale behind those caveats.

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application
Issuing the following command at the root of the project will bring the default browser showing the component's information page.
```
$ polymer serve --open
```

In order to see a demo of the component, navigate to [http://localhost:8080/demo](http://localhost:8080/demo). You can edit the component declaration by editing it inside the tags `<template>...</template>` in the `[project root]/demo/index.html` file.

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

**Note**: the archetype that is used at this time to generate this project ("basic", aka `polymer init`) provides several broken links that cause `bundled` build to fail.  This is currently being fixed (by me, for this project)

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests
The tests are automated whenever you push changes to Github by means of Travis CI. For running your tests locally:
```
$ polymer test
```

