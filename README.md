# storage [![NPM version](https://badge.fury.io/js/storage.svg)](http://badge.fury.io/js/storage)

> Basic object store for node.js

## Install with [npm](npmjs.org)

```bash
npm i storage --save
```

## Run tests

```bash
npm test
```

## Usage

```js
var storage = require('storage');
```

## API
### [Storage](index.js#L29)

Create a new instance of `Storage`, optionally passing a default `cache` object to initialize with.

* `cache` **{Object}**    

```js
var Storage = require('storage');
var storage = new Storage();
```

### [.set](index.js#L41)

* `key` **{String}**    
* `value` **{*}**    

Assign `value` to `key`.

### [.get](index.js#L54)

* `key` **{String}**    
* `returns` **{*}**: Returns the stored value of `key`  

Get the stored vale of `key`.

## Author

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 

## License
Copyright (c) 2014 Jon Schlinkert  
Released under the MIT license

***
