# Nacho - A minimal, highly customizable flexbox framework

[![npm version](https://badge.fury.io/js/nacho.svg)](https://badge.fury.io/js/nacho)
[![Build Status](https://travis-ci.org/Linkd-Inc/nacho.svg?branch=master)](https://travis-ci.org/Linkd-Inc/nacho)


## Installation

To add nacho to your web page, simply paste this code into the `head` of your document,
```html
<link rel="stylesheet" href="https://unpkg.com/nacho/dist/nacho.min.css">
<!-- or -->
<link rel="stylesheet" href="https://unpkg.com/nacho/dist/nacho.css">
```
or you can install nacho using a package manager like [npm](https://npmjs.com/package/nacho)
```bash
$ npm install nacho
```
If you want you can still download nacho [here](https://github.com/WireFlare/nacho/releases/download/v0.0.1/nacho.min.css).

### Example:

```html
<div>
  <div class="row">
    <!-- For column width, use the number / 12 -->
    <div class="col-xs-3"></div>
    <div class="col-sm-3"></div>
    <div class="col-md-3"></div>
    <div class="col-lg-3"></div>
  </div>
  <div class="col">
    <!-- The col parent class makes items stack vertically -->
    <div></div>
    <div></div>
    <div></div>
  </div>
</div>
```

## License

Copyright (c) 2017 Wireflare. Licensed under the MIT License (MIT)
