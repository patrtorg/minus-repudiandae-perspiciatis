# @patrtorg/minus-repudiandae-perspiciatis <sup>[![Version Badge][2]][1]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][5]][6]
[![dev dependency status][7]][8]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][11]][1]

Returns an array of Typed Array names that are available in the current environment.

## Example

```js
var availableTypedArrays = require('@patrtorg/minus-repudiandae-perspiciatis');
var assert = require('assert');

assert.deepStrictEqual(
	availableTypedArrays().sort(),
	[
		'Int8Array',
		'Uint8Array',
		'Uint8ClampedArray',
		'Int16Array',
		'Uint16Array',
		'Int32Array',
		'Uint32Array',
		'Float32Array',
		'Float64Array',
		'BigInt64Array',
		'BigUint64Array'
	].sort()
);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[1]: https://npmjs.org/package/@patrtorg/minus-repudiandae-perspiciatis
[2]: https://versionbadg.es/inspect-js/@patrtorg/minus-repudiandae-perspiciatis.svg
[5]: https://david-dm.org/inspect-js/@patrtorg/minus-repudiandae-perspiciatis.svg
[6]: https://david-dm.org/inspect-js/@patrtorg/minus-repudiandae-perspiciatis
[7]: https://david-dm.org/inspect-js/@patrtorg/minus-repudiandae-perspiciatis/dev-status.svg
[8]: https://david-dm.org/inspect-js/@patrtorg/minus-repudiandae-perspiciatis#info=devDependencies
[11]: https://nodei.co/npm/@patrtorg/minus-repudiandae-perspiciatis.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@patrtorg/minus-repudiandae-perspiciatis.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@patrtorg/minus-repudiandae-perspiciatis.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@patrtorg/minus-repudiandae-perspiciatis
[codecov-image]: https://codecov.io/gh/inspect-js/@patrtorg/minus-repudiandae-perspiciatis/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@patrtorg/minus-repudiandae-perspiciatis/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@patrtorg/minus-repudiandae-perspiciatis
[actions-url]: https://github.com/patrtorg/minus-repudiandae-perspiciatis/actions
