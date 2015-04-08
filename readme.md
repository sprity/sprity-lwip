# css-sprite-lwip

[![NPM version](https://badge.fury.io/js/css-sprite-lwip.svg)](http://badge.fury.io/js/css-sprite-lwip) [![Build Status](https://travis-ci.org/aslansky/css-sprite-lwip.svg?branch=master)](https://travis-ci.org/aslansky/css-sprite-lwip) [![Dependencies](https://david-dm.org/aslansky/css-sprite-lwip.svg)](https://david-dm.org/aslansky/css-sprite-lwip)

> Image processor for [css-sprite](https://npmjs.org/package/css-sprite) that uses [lwip](https://github.com/EyalAr/lwip) as the image processing library

> [css-sprite's](https://npmjs.org/package/css-sprite) default image processor

> javascript only, no external library dependencies

## Requirements

- [css-sprite](https://npmjs.org/package/css-sprite) version >= 1.0

## Install

By default `css-sprite-lwip` is installed width `css-sprite`.

```sh
npm install css-sprite
```

If you want to use the command line interface of `css-sprite` install it globally.

```
npm install css-sprite -g
```

## Options

* **lwip-interpolation:** Optional interpolation method. Defaults to "lanczos". Possible values:
  * nearest-neighbor
  * moving-average
  * linear
  * grid
  * cubic
  * lanczos

## Usage

See [css-sprite](https://npmjs.org/package/css-sprite) documentation
