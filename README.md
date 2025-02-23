NativeScript Augmented Reality
==============================

[![Build Status][build-status]][build-url]
[![NPM version][npm-image]][npm-url]
[![Downloads][downloads-image]][npm-url]
[![Twitter Follow][twitter-image]][twitter-url]

[build-status]:https://travis-ci.org/EddyVerbruggen/nativescript-ar.svg?branch=master
[build-url]:https://travis-ci.org/EddyVerbruggen/nativescript-ar
[npm-image]:http://img.shields.io/npm/v/nativescript-ar.svg
[npm-url]:https://npmjs.org/package/nativescript-ar
[downloads-image]:http://img.shields.io/npm/dm/nativescript-ar.svg
[twitter-image]:https://img.shields.io/twitter/follow/eddyverbruggen.svg?style=social&label=Follow%20me
[twitter-url]:https://twitter.com/eddyverbruggen

> Tip: give this [article by TJ](https://www.nativescript.org/blog/getting-started-with-augmented-reality-in-nativescript) a read if you want a nice introduction to AR in NativeScript. It uses an older version of the plugin, but it's still quite relevant.

### Supported platforms
* iPhone SE, 6s, iPad Pro, iPad 2017, or newer support ARKit. Running iOS 11 or newer.
* [Many Android devices](https://developers.google.com/ar/discover/supported-devices#android_play) support ARCore nowadays. Obviously the faster the device, the better the experience.

## Installation
From the command prompt go to your app's root folder and execute:
```bash
tns plugin add nativescript-ar
```

## Embedding an AR view
- [I'm Using NativeScript with Angular](docs/ar-angular.md)
- [I'm Using NativeScript with Vue](docs/ar-vue.md)
- [I'm Using NativeScript with XML](docs/ar-xml.md)

## Types of AR experiences
- [World tracking](docs/tracking-world.md): augment the world around you
- [Face tracking](docs/tracking-faces.md): augment a face
- [Image tracking](docs/tracking-images.md): augment 2D images your camera finds

## Using the AR API
- [AR API](docs/api.md)
