**JavaScript Turbo**🔥 A collection of **Javascript** clips for Nova. If you would like to make any suggestions, updates or changes please submit via the GitHub Repo.\
If you find these clips useful consider planting a tree for the world. 🌳 [One Tree Planted](https://onetreeplanted.org/products/australia) \
Happy Coding Dan👨🏻‍💻

JavaScript Turbo is based on: [Atom Turbo JavaScript](https://github.com/extrabacon/atom-turbo-javascript)

## Details

### Declarations

#### `v⇥` var statement

```js
var ${1:name}
```

#### `v=⇥` var assignment

```js
var ${1:name} = ${2:value}
```

#### `l⇥` let statement

```js
let ${1:name}
```

#### `l=⇥` let assignment

```js
let ${1:name} = ${2:value}
```

#### `co⇥` const statement

```js
const ${1:name}
```

#### `co=⇥` const assignment

```js
const ${1:name} = ${2:value}
```

### Flow Control

#### `if⇥` if statement

```js
if (${1:condition}) {
  ${0}
}
```

#### `el⇥` else statement

```js
else {
  ${0}
}
```

#### `ife⇥` else statement

```js
if (${1:condition}) {
  ${0}
} else {

}
```

#### `ei⇥` else if statement

```js
else if (${1:condition}) {
  ${0}
}
```

#### `fl⇥` for loop

```js
for (let ${1:i} = 0, ${2:len} = ${3:iterable}.length; ${1:i} < ${2:len}; ${1:i}++) {
  ${0}
}
```

#### `fi⇥` for in loop

```js
for (let ${1:key} in ${2:source}) {
  if (${2:source}.hasOwnProperty(${1:key})) {
	${0}
  }
}
```

#### `fo⇥` for of loop (ES6)

```js
for (let ${1:key} of ${2:source}) {
  ${0}
}
```

#### `wl⇥` while loop

```js
while (${1:condition}) {
  ${0}
}
```

#### `tc⇥` try/catch

```js
try {
 ${0}
} catch (${1:err}) {

}
```

#### `tf⇥` try/finally

```js
try {
 ${0}
} finally {

}
```

#### `tcf⇥` try/catch/finally

```js
try {
  ${0}
} catch (${1:err}) {

} finally {

}
```

#### `sw⇥` switch case

```js
switch (${1:expr}) {
  case ${2:value}:
	return $0;
  default:
	return;
}
```

### Functions

#### `f⇥` anonymous function

```js
function (${1:arguments}) {${0}}
```

#### `fn⇥` named function

```js
function ${1:name}(${2:arguments}) {
  ${0}
}
```

#### `iife⇥` immediately-invoked function expression (IIFE)

```js
(function (${1:arguments}) {
  ${0}
})(${2});
```

#### `fa⇥` function apply

```js
${1:fn}.apply(${2:this}, ${3:arguments})
```

#### `fc⇥` function call

```js
${1:fn}.call(${2:this}, ${3:arguments})
```

#### `fb⇥` function bind

```js
${1:fn}.bind(${2:this}, ${3:arguments})
```

#### `af⇥` arrow function (ES6)

```js
(${1:arguments}) => ${2:statement}
```

#### `afb⇥` arrow function with body (ES6)

```js
(${1:arguments}) => {
\t${0}
}
```

#### `gf⇥` generator function (ES6)

```js
function* (${1:arguments}) {
  ${0}
}
```

#### `gfn⇥` named generator function (ES6)

```js
function* ${1:name}(${1:arguments}) {
  ${0}
}
```

### Iterables

#### `seq⇥` sequence of 0..n

```js
[...Array(${1:length}).keys()]${0}
```

#### `fe⇥` forEach loop

```js
${1:iterable}.forEach((${2:item}) => {
  ${0}
});
```

#### `map⇥` map function

```js
${1:iterable}.map((${2:item}) => {
  ${0}
});
```

#### `reduce⇥` reduce function

```js
${1:iterable}.reduce((${2:previous}, ${3:current}) => {
  ${0}
}${4:, initial});
```

#### `filter⇥` filter function

```js
${1:iterable}.filter((${2:item}) => {
  ${0}
});
```

#### `find⇥` ES6 find function

```js
${1:iterable}.find((${2:item}) => {
  ${0}
});
```

### Objects and classes

#### `c⇥` class (ES6)

```js
class ${1:name} {
  constructor(${2:arguments}) {
	${0}
  }
}
```

#### `cex⇥` child class (ES6)

```js
class ${1:name} extends ${2:base} {
  constructor(${2:arguments}) {
	super(${2:arguments});
	${0}
  }
}
```

#### `ctor` class constructor (ES6)

```js
constructor(${1:arguments}) {
  super(${1:arguments});${0}
}
```

#### `:⇥` key/value pair

Javascript:

```js
${1:key}: ${2:'value'}
```

JSON:

```json
"${1:key}": ${2:"value"}
```

#### `m⇥` method (ES6 syntax)

```js
${1:method}(${2:arguments}) {
  ${0}
}
```

#### `get⇥` getter (ES6 syntax)

```js
get ${1:property}() {
  ${0}
}
```

#### `set⇥` setter (ES6 syntax)

```js
set ${1:property}(${2:value}) {
  ${0}
}
```

#### `gs⇥` getter and setter (ES6 syntax)

```js
get ${1:property}() {
  ${0}
}
set ${1:property}(${2:value}) {

}
```

#### `proto⇥` prototype method

```js
${1:Class}.prototype.${2:methodName} = function (${3:arguments}) {
  ${0}
};
```

#### `a⇥` Object assign

```js
Object.assign(${1:dest}, ${2:source})
```

#### `ac⇥` Object assign copy (shallow clone)

```js
Object.assign({}, ${1:original}, ${2:source})
```

### Returning values

#### `r⇥` return

```js
return ${0};
```

#### `rth⇥` return this

```js
return this;
```

#### `rn⇥` return null

```js
return null;
```

#### `rt⇥` return true

```js
return true;
```

#### `rf⇥` return false

```js
return false;
```

#### `r0⇥` return 0

```js
return 0;
```

#### `r-1⇥` return -1

```js
return -1;
```

#### `rp⇥` return Promise (ES6)

```js
return new Promise((resolve, reject) => {
  ${0}
});
```

#### `rc⇥` return complex value (such as JSX components)

```js
return (
  ${0}
);
```

### Promises

#### `p⇥` new Promise (ES6)

```js
new Promise((resolve, reject) => {
  ${0}
})
```

#### `then⇥` Promise.then

```js
${1:promise}.then(${2:value} => {
  ${0}
});
```

#### `catch⇥` Promise.catch

```js
${1:promise}.catch(${2:err} => {
  ${0}
});
```

### ES6 modules

#### `ex⇥` module export

```js
export ${1:member};
```

#### `exd⇥` module default export

```js
export default ${1:member};
```

#### `im⇥` module import

```js
import ${1:*} from '${2:module}';
```

#### `ima⇥` module import as

```js
import ${1:*} as ${2:name} from '${3:module}';
```

### BDD testing (Mocha, Jasmine, etc.)

#### `desc⇥` describe

```js
describe('${1:description}', function () {
  ${0}
});
```

#### `cont⇥` context

```js
context('${1:description}', function () {
  ${0}
});
```

#### `it⇥` and `its⇥` synchronous "it"

```js
it('${1:description}', function () {
  ${0}
});
```

#### `ita⇥` asynchronous "it"

```js
it('${1:description}', function (done) {
  ${0}
});
```

#### `bf⇥` before test suite

```js
before(function () {
  ${0}
});
```

#### `bfe⇥` before each test

```js
beforeEach(function () {
  ${0}
});
```

#### `aft⇥` after test suite

```js
after(function () {
  ${0}
});
```

#### `afe⇥` after each test

```js
afterEach(function () {
  ${0}
});
```

### Console

#### `cl⇥` console.log

```js
console.log(${0});
```

#### `ce⇥` console.error

```js
console.error(${0});
```

#### `cw⇥` console.warn

```js
console.warn(${0});
```

### Timers

#### `st⇥` setTimeout

```js
setTimeout(() => {
  ${0}
}, ${1:delay});
```

#### `si⇥` setInterval

```js
setInterval(() => {
  ${0}
}, ${1:delay});
```

#### `sim⇥` setImmediate

```js
setImmediate(() => {
  ${0}
});
```

### DOM specifics

#### `ae⇥` addEventListener

```js
${1:document}.addEventListener('${2:event}', ${3:ev} => {
  ${0}
});
```

#### `gi⇥` getElementById

```js
${1:document}.getElementById('${2:id}')
```

#### `gc⇥` getElementsByClassName

```js
Array.from(${1:document}.getElementsByClassName('${2:class}'))
```

`Array.from` polyfill required for ES5

#### `gt⇥` getElementsByTagName

```js
Array.from(${1:document}.getElementsByTagName('${2:tag}'))
```

`Array.from` polyfill required for ES5

#### `qs⇥` querySelector

```js
${1:document}.querySelector('${2:selector}')
```

#### `qsa⇥` querySelectorAll

```js
Array.from(${1:document}.querySelectorAll('${2:selector}'))
```

`Array.from` polyfill required for ES5

### Node.js specifics

#### `cb⇥` Node.js style callback

```js
function (err${1:, value}) {${0}}
```

#### `re⇥` require a module

```js
require("${1:module}");
```

#### `em⇥` export member

```js
exports.${1:name} = ${2:value};
```

#### `me⇥` module.exports

```js
module.exports = ${1:name};
```

#### `on⇥` attach an event handler

```js
${1:emitter}.on('${2:event}', (${3:arguments}) => {
  ${0}
});
```

#### `xm⇥` Express middleware

```js
function (req, res${1:, next}) {
  ${0}
}
```

#### `xerr⇥` Express error handler

```js
function (err, req, res, next) {
  ${0}
}
```

### Miscellaneous

#### `us⇥` use strict

```js
"use strict";

```

# License

The MIT License (MIT)

Copyright (c) 2014, Nicolas Mercier

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
