# isobject [![NPM version](https://badge.fury.io/js/isobject.svg)](http://badge.fury.io/js/isobject)

> Returns true if the value is an object and not an array or null.

## Install
```bash
npm i isobject --save
```

## Usage

```js
var isObject = require('isobject');
console.log(isObject(null));
//=> 'false'
console.log(isObject([]));
//=> 'false'
console.log(isObject({}));
//=> 'true'
```

## Author

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 

## License
Copyright (c) 2015 Jon Schlinkert  
Released under the MIT license

***

_This file was generated by [verb](https://github.com/assemble/verb) on February 25, 2015._