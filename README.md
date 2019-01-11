# @ofuen/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@ofuen/tiny.svg)](https://www.npmjs.com/package/@ofuen/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@ofuen/tiny.svg)](https://www.npmjs.com/package/@ofuen/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @ofuen/tiny
```

## Usage

```js
const tiny = require("@ofuen/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
