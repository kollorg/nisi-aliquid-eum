# @kollorg/nisi-aliquid-eum <sup>[![Version Badge][2]][1]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][5]][6]
[![dev dependency status][7]][8]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][11]][1]

Determine if the JS environment has `Symbol.toStringTag` support. Supports spec, or shams.

## Example

```js
var hasSymbolToStringTag = require('@kollorg/nisi-aliquid-eum');

hasSymbolToStringTag() === true; // if the environment has native Symbol.toStringTag support. Not polyfillable, not forgeable.

var hasSymbolToStringTagKinda = require('@kollorg/nisi-aliquid-eum/shams');
hasSymbolToStringTagKinda() === true; // if the environment has a Symbol.toStringTag sham that mostly follows the spec.
```

## Supported Symbol shams
 - get-own-property-symbols [npm](https://www.npmjs.com/package/get-own-property-symbols) | [github](https://github.com/WebReflection/get-own-property-symbols)
 - core-js [npm](https://www.npmjs.com/package/core-js) | [github](https://github.com/zloirock/core-js)

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[1]: https://npmjs.org/package/@kollorg/nisi-aliquid-eum
[2]: https://versionbadg.es/inspect-js/@kollorg/nisi-aliquid-eum.svg
[5]: https://david-dm.org/inspect-js/@kollorg/nisi-aliquid-eum.svg
[6]: https://david-dm.org/inspect-js/@kollorg/nisi-aliquid-eum
[7]: https://david-dm.org/inspect-js/@kollorg/nisi-aliquid-eum/dev-status.svg
[8]: https://david-dm.org/inspect-js/@kollorg/nisi-aliquid-eum#info=devDependencies
[11]: https://nodei.co/npm/@kollorg/nisi-aliquid-eum.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@kollorg/nisi-aliquid-eum.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@kollorg/nisi-aliquid-eum.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@kollorg/nisi-aliquid-eum
[codecov-image]: https://codecov.io/gh/inspect-js/@kollorg/nisi-aliquid-eum/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@kollorg/nisi-aliquid-eum/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@kollorg/nisi-aliquid-eum
[actions-url]: https://github.com/kollorg/nisi-aliquid-eum/actions
