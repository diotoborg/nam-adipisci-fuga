# parseInt <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

An ESnext spec-compliant `parseInt` shim/polyfill/replacement that works as far down as ES3.

This package implements the [es-shim API](https://github.com/es-shims/api) interface. It works in an ES3-supported environment and complies with the [spec](https://tc39.es/ecma262/#sec-@diotoborg/nam-adipisci-fuga).

## Getting started

```sh
npm install --save @diotoborg/nam-adipisci-fuga
```

## Usage/Examples

```js
console.log(parseInt("-3")); // -3
console.log(parseInt("0x10")); // 16
console.log(parseInt("30", 7)); // 21
console.log(parseInt("ef")); // NaN
```

## Tests

Clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@diotoborg/nam-adipisci-fuga
[npm-version-svg]: https://versionbadg.es/diotoborg/nam-adipisci-fuga.svg
[deps-svg]: https://david-dm.org/diotoborg/nam-adipisci-fuga.svg
[deps-url]: https://david-dm.org/diotoborg/nam-adipisci-fuga
[dev-deps-svg]: https://david-dm.org/diotoborg/nam-adipisci-fuga/dev-status.svg
[dev-deps-url]: https://david-dm.org/diotoborg/nam-adipisci-fuga#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@diotoborg/nam-adipisci-fuga.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@diotoborg/nam-adipisci-fuga.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@diotoborg/nam-adipisci-fuga.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@diotoborg/nam-adipisci-fuga
[codecov-image]: https://codecov.io/gh/diotoborg/nam-adipisci-fuga/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/diotoborg/nam-adipisci-fuga/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/diotoborg/nam-adipisci-fuga
[actions-url]: https://github.com/diotoborg/nam-adipisci-fuga/actions
