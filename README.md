# tiny-circular-progress-bar

The tiniest circular progress bar

![npm (scoped)](https://img.shields.io/npm/v/@evzonic/tiny-circular-progress-bar)
![npm bundle size](https://img.shields.io/bundlephobia/min/@evzonic/tiny-circular-progress-bar)

Creates a tiny circular progress bar.

## Install

```
npm i @evzonic/tiny-circular-progress-bar
```

## Usage

```js
const tiny = require("@bamblehorse/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
