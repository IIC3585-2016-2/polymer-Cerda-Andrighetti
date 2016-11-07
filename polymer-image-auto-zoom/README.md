# \<polymer-image-auto-zoom\>

Displays an image and auto-zooms it on hover

Based on [Mouseover Popup Image Viewer](http://w9p.co/userscripts/mpiv/)

## Usage

Replace `<img>` tags with `<polymer-image-auto-zoom>` tags:
```html
<img src="logo2.png" width="200px" />
```
```html
<polymer-image-auto-zoom src="logo2.png" width=200></polymer-image-auto-zoom>
```

## Demo

- Run `polymer serve`
- Open <http://localhost:8080/components/polymer-image-auto-zoom/demo/no-polymer.html>, click on the images
- Click the link at the bottom of the page, hover the mouse pointer over the images

--------------------------------------------

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
