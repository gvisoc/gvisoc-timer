# \<gvisoc-timer\>

A basic parameterizable timer.

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

```
$ polymer test
```
**Note**: the archetype that is used at this time to generate this project ("basic", aka `polymer init`) provides several broken links that cause the test suite to properly work. This is currently being fixed (by me, for this project).

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
