[js-graph-weighted](http://aureooms.github.io/js-graph-weighted)
==

Weighted graph code bricks for JavaScript

[![License](https://img.shields.io/github/license/aureooms/js-graph-weighted.svg?style=flat)](https://raw.githubusercontent.com/aureooms/js-graph-weighted/master/LICENSE)
[![NPM version](https://img.shields.io/npm/v/@aureooms/js-graph-weighted.svg?style=flat)](https://www.npmjs.org/package/@aureooms/js-graph-weighted)
[![Bower version](https://img.shields.io/bower/v/@aureooms/js-graph-weighted.svg?style=flat)](http://bower.io/search/?q=@aureooms/js-graph-weighted)
[![Build Status](https://img.shields.io/travis/aureooms/js-graph-weighted.svg?style=flat)](https://travis-ci.org/aureooms/js-graph-weighted)
[![Coverage Status](https://img.shields.io/coveralls/aureooms/js-graph-weighted.svg?style=flat)](https://coveralls.io/r/aureooms/js-graph-weighted)
[![Dependencies Status](https://img.shields.io/david/aureooms/js-graph-weighted.svg?style=flat)](https://david-dm.org/aureooms/js-graph-weighted#info=dependencies)
[![devDependencies Status](https://img.shields.io/david/dev/aureooms/js-graph-weighted.svg?style=flat)](https://david-dm.org/aureooms/js-graph-weighted#info=devDependencies)
[![Code Climate](https://img.shields.io/codeclimate/github/aureooms/js-graph-weighted.svg?style=flat)](https://codeclimate.com/github/aureooms/js-graph-weighted)
[![NPM downloads per month](https://img.shields.io/npm/dm/@aureooms/js-graph-weighted.svg?style=flat)](https://www.npmjs.org/package/@aureooms/js-graph-weighted)
[![GitHub issues](https://img.shields.io/github/issues/aureooms/js-graph-weighted.svg?style=flat)](https://github.com/aureooms/js-graph-weighted/issues)
[![Inline docs](http://inch-ci.org/github/aureooms/js-graph-weighted.svg?branch=master&style=shields)](http://inch-ci.org/github/aureooms/js-graph-weighted)

Can be managed through [jspm](https://github.com/jspm/jspm-cli),
[duo](https://github.com/duojs/duo),
[component](https://github.com/componentjs/component),
[bower](https://github.com/bower/bower),
[ender](https://github.com/ender-js/Ender),
[jam](https://github.com/caolan/jam),
[spm](https://github.com/spmjs/spm),
and [npm](https://github.com/npm/npm).

## Install

### jspm
```terminal
jspm install github:aureooms/js-graph-weighted
# or
jspm install npm:@aureooms/js-graph-weighted
```
### duo
No install step needed for duo!

### component
```terminal
component install aureooms/js-graph-weighted
```

### bower
```terminal
bower install @aureooms/js-graph-weighted
```

### ender
```terminal
ender add @aureooms/js-graph-weighted
```

### jam
```terminal
jam install @aureooms/js-graph-weighted
```

### spm
```terminal
spm install @aureooms/js-graph-weighted --save
```

### npm
```terminal
npm install @aureooms/js-graph-weighted --save
```

## Require
### jspm
```js
let graphweighted = require( "github:aureooms/js-graph-weighted" ) ;
// or
import graphweighted from '@aureooms/js-graph-weighted' ;
```
### duo
```js
let graphweighted = require( "aureooms/js-graph-weighted" ) ;
```

### component, ender, spm, npm
```js
let graphweighted = require( "@aureooms/js-graph-weighted" ) ;
```

### bower
The script tag exposes the global variable `graphweighted`.
```html
<script src="bower_components/@aureooms/js-graph-weighted/js/dist/graph-weighted.min.js"></script>
```
Alternatively, you can use any tool mentioned [here](http://bower.io/docs/tools/).

### jam
```js
require( [ "@aureooms/js-graph-weighted" ] , function ( graphweighted ) { ... } ) ;
```