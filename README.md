# isobject [![NPM version](https://img.shields.io/npm/v/isobject.svg?style=flat)](https://www.npmjs.com/package/isobject) [![NPM downloads](https://img.shields.io/npm/dm/isobject.svg?style=flat)](https://npmjs.org/package/isobject) [![Linux Build Status](https://img.shields.io/travis/jonschlinkert/isobject.svg?style=flat&label=Travis)](https://travis-ci.org/jonschlinkert/isobject)

> Returns true if the value is an object and not an array or null.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install --save isobject
```

Use [is-plain-object](https://github.com/jonschlinkert/is-plain-object) if you want only objects that are created by the `Object` constructor.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install isobject
```

Install with [bower](http://bower.io/)

```sh
$ bower install isobject
```

## Usage

```js
var isObject = require('isobject');
```

**True**

All of the following return `true`:

```js
isObject({});
isObject(Object.create({}));
isObject(Object.create(Object.prototype));
isObject(Object.create(null));
isObject({});
isObject(new Foo);
isObject(/foo/);
```

**False**

All of the following return `false`:

```js
isObject();
isObject(function () {});
isObject(1);
isObject([]);
isObject(undefined);
isObject(null);
```

## About

### Related projects

* [extend-shallow](https://www.npmjs.com/package/extend-shallow): Extend an object with the properties of additional objects. node.js/javascript util. | [homepage](https://github.com/jonschlinkert/extend-shallow "Extend an object with the properties of additional objects. node.js/javascript util.")
* [is-plain-object](https://www.npmjs.com/package/is-plain-object): Returns true if an object was created by the `Object` constructor. | [homepage](https://github.com/jonschlinkert/is-plain-object "Returns true if an object was created by the `Object` constructor.")
* [kind-of](https://www.npmjs.com/package/kind-of): Get the native type of a value. | [homepage](https://github.com/jonschlinkert/kind-of "Get the native type of a value.")
* [merge-deep](https://www.npmjs.com/package/merge-deep): Recursively merge values in a javascript object. | [homepage](https://github.com/jonschlinkert/merge-deep "Recursively merge values in a javascript object.")

### Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](../../issues/new).

### Contributors

| **Commits** | **Contributor** | 
| --- | --- |
| 29 | [jonschlinkert](https://github.com/jonschlinkert) |
| 1 | [LeSuisse](https://github.com/LeSuisse) |
| 1 | [tmcw](https://github.com/tmcw) |

### Building docs

_(This document was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme) (a [verb](https://github.com/verbose/verb) generator), please don't edit the readme directly. Any changes to the readme must be made in [.verb.md](.verb.md).)_

To generate the readme and API documentation with [verb](https://github.com/verbose/verb):

```sh
$ npm install -g verb verb-generate-readme && verb
```

### Running tests

Install dev dependencies:

```sh
$ npm install -d && npm test
```

### Author

**Jon Schlinkert**

* [github/jonschlinkert](https://github.com/jonschlinkert)
* [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

### License

Copyright © 2016, [Jon Schlinkert](https://github.com/jonschlinkert).
Released under the [MIT license](LICENSE).

***

_This file was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme), v0.2.0, on December 01, 2016._