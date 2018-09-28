# @zachfejes/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@zachfejes/tiny.svg)](https://github.com/zachfejes/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@zachfejes/tiny.svg)](https://github.com/zachfejes/tiny)

Removes all spaces from a string.

## Install
```
    $ npm install @zachfejes/tiny
```


## Usage

```
    const tiny = require("@zachfejes/tiny");

    tiny("So much space!");
    //=> "Somuchspace!"

    tiny(1337);
    //=> Uncaught TypeError: Tiny wants a string!
    //      at tiny (<anonymous>:2:41)
    //      at <anonymous>:1:1
```