# jstransformer-coffeecup

[CoffeeCup](http://npm.im/coffeecup) support for [JSTransformers](http://github.com/jstransformers).

[![Build Status](https://img.shields.io/travis/jstransformers/jstransformer-coffeecup/master.svg)](https://travis-ci.org/jstransformers/jstransformer-coffeecup)
[![Coverage Status](https://img.shields.io/coveralls/jstransformers/jstransformer-coffeecup/master.svg)](https://coveralls.io/r/jstransformers/jstransformer-coffeecup?branch=master)
[![Dependency Status](https://img.shields.io/david/jstransformers/jstransformer-coffeecup/master.svg)](http://david-dm.org/jstransformers/jstransformer-coffeecup)
[![NPM version](https://img.shields.io/npm/v/jstransformer-coffeecup.svg)](https://www.npmjs.org/package/jstransformer-coffeecup)

## Installation

    npm install jstransformer-coffeecup

## API

```js
var coffeecup = require('jstransformer')(require('jstransformer-coffeecup'))

coffeecup.render('h1 @title', { title: 'Hello World!' }).body
//=> <h1>Hello World!</h1>
```

## License

MIT
