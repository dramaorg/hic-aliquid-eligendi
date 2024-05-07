# Math.clz32 <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `Math.clz32` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-map-objects).

## Getting started

```sh
npm install --save @dramaorg/hic-aliquid-eligendi
```

## Usage/Examples

```js
console.log(Math.clz32(1)); // 31
console.log(Math.clz32(1000)); // 22
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@dramaorg/hic-aliquid-eligendi
[npm-version-svg]: https://versionbadg.es/dramaorg/hic-aliquid-eligendi.svg
[deps-svg]: https://david-dm.org/dramaorg/hic-aliquid-eligendi.svg
[deps-url]: https://david-dm.org/dramaorg/hic-aliquid-eligendi
[dev-deps-svg]: https://david-dm.org/dramaorg/hic-aliquid-eligendi/dev-status.svg
[dev-deps-url]: https://david-dm.org/dramaorg/hic-aliquid-eligendi#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@dramaorg/hic-aliquid-eligendi.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@dramaorg/hic-aliquid-eligendi.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@dramaorg/hic-aliquid-eligendi.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@dramaorg/hic-aliquid-eligendi
[codecov-image]: https://codecov.io/gh/dramaorg/hic-aliquid-eligendi/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/dramaorg/hic-aliquid-eligendi/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/dramaorg/hic-aliquid-eligendi
[actions-url]: https://github.com/dramaorg/hic-aliquid-eligendi/actions
