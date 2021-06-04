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
import { CircleProgress } from "evzonic/tiny-circular-progress-bar";

new CircleProgress(".progress", {
  max: 100,
  value: 60,

  textFormat: "percent",
});
```
