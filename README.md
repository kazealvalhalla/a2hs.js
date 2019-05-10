<h1 align="center">📲 a2hs.js</h1>
<p align="center"><i>Add progressive web application (PWA) to Home Screen on iOS</i></p>

<p align="center">
    <img src="https://badge.fury.io/js/a2hs.js.svg" alt="npm version"/>
    <img src="https://img.shields.io/badge/GZip_size-1.6_KB-green.svg?style=flat" alt="gzip"/>
    <img src="https://data.jsdelivr.com/v1/package/npm/a2hs.js/badge?style=rounded" alt="jsDelivr download"/>
    <img src="https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat" alt="code style: prettier"/>
    <img src="https://img.shields.io/badge/license-MIT-yellow.svg?style=flat" alt="license"/>
</p>

<p align="center">
    A useful modern JavaScript solution for adding (install) a <b>progressive web application</b> (PWA) to the <b>Home screen</b> of your <b>iOS</b> mobile device. Designed for the <b>latest 4 major versions</b> of iOS Safari 9.x-12.2+.
</p>

## Install

```bash
$ npm install --save a2hs.js
```

## Usage

There is two way to use `a2hs.js` in your JS bundle:

```js
/**
 * Simple import
 */

// Import a2hs.js
import AddToHomeScreen from "a2hs.js"

// Init a2hs.js
new AddToHomeScreen({
    fontFamily: "Tahoma, sans-serif",
    backgroundColor: "red",
    color: "white",
    padding: "5px"
}).init()
```