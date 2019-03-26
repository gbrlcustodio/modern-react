# Modern JavaScript

JavaScript is arguably one of the most important languages today. The rise of the web has taken JavaScript places it was never conceived to be. This document intends to briefly introduces modern JS features while comparing it to the old fashioned way of achieving the same result by writing the examples using ES5 only features side-by-side with new ESNext features.

## History

JavaScript was invented by Brendan Eich in 1995 and was first named **Mocha** and released by the name **LiveScript** in conjunction with Netscape browser (Beta). Switched name to **JavaScript** by the end of that same year when Sun and Netscape did a license agreement [[1](#References)].

Was submitted for standardization to the ECMA International and became an ECMA standard in early 1997 and because of trademark reason, the committee was not able to use the JavaScript name, so after some discussions it was decided that the language described by the standard would be called **ECMAScript** [[2](#References)].

ECMA International is an industry association formed in 1961 concerned solely with standardization of information and communications systems [[3](#References)].

The first big changes made since the first ECMA version was released had arrived with _ES3_, shorthand for ECMAScript 3, in december 1999 and brought into play stuffs like _regular expression_, _do-while block_, _exceptions and try/catch blocks_, the _in_ and _instanceof_ operators and more.

The works on ECMAScript 4 begun right after ES3 was released, but, due to strong differences in the committee, ES4 was never released, and util 2009 there were no major releases of a new standard.

The year of 2009 became known as the rebirth of JavaScript. After a long struggle with ES4, the next version was released and ES5 became one of the most supported versions of JavaScript as the compiler target of many transpilers since it's supported by the majority of browser nowadays.

ECMAScript 5 introduced features like [[4](#References)]:

- Getters and Setters
- Trailing commas in array and objects literals
- New Object methods
  - create, defineProperty, keys, seal, freeze, getOwnPropertiesName, etc.
- New Array methods
  - isArray, indexOf, every, some, map, filter, reduce, etc
- New Date methods
  - toISOString, now, toJSON
- Function binding
- JSON
- Immutable global objects
  - undefined, NaN, Infinity
- Strict mode
- JSON support

ECMAScript 6, later renamed to ECMAScript 2015, implemented some of the big features proposed by ECMAScript 4, but with a different mindset. New features were created as syntactic sugar over the existing ones, which eases the transition and development of those new features [[5](#References)].

A short summary of features is described below [[6](#References)]:

- let and const
- Arrow functions
- Classes
- Default parameters
- Array.find and Array.findIndex
- New Number methods
  - isInteger, isSafeInteger
- New Global methods
  - isFinite
  - isNaN
- Template literals
- Promises
- Generators
- Spread syntax
  - At array initializer and argument lists
- Destructuring
- Tail call optimization
- Module system
- New collections
  - Set, Map, WeakSet, WeakMap
- Enhanced Object syntax
  - Property shorthand, computed property names, method properties

From ES6 beyond, the new standard was to release a new ECMAScript version every year, as a consequence, the language became more mature and concise while new features were introduced. By the next year, ECMAScript 2016 (ES7) was released and introduced only two new features:

- Exponential operator `**`
- Array.prototype.includes

ECMAScript 2017 (ES8) was officially released at the end of June that year by TC39 and included:

- Enhanced object properties
  - Object.values(), Object.entries(), Object.getOwnPropertyDescriptors
- String padding
- Async / Await with error handling
- Shared memory and atomics

ECMAScript 2018 (ES9), the last release so far, introduced the following:

- Promise.prototype.finally()
- Asynchronous iteration
- Spread / Rest object properties

## Tools

With the release of ECMAScript 2015, the hype around web development became bigger and more eloquent. A bunch of new tools were, and still, released every day and spread over different domains of computer science. Those tools are responsible for tracking a wide range of issues going from web development to unexplored domains.

### Babel

### Webpack

## Modern features

### Variable declaration

#### Variable scope

### Arrow function

### Default Parameter

### Destructuring

#### Array methods

#### Array.from()

#### Array.of()

#### Array.prototype.map()

#### Array.prototype.filter()

#### Array.prototype.reduce()

#### Array.prototype.find()

#### Array.prototype.findIndex()

#### Array.prototype.every()

#### Array.prototype.some()

### Spread Operator

### Object property shorthand

### Promises

### Template literals

### Module system

#### Named export

#### Default export

### Classes

#### extends

#### super()

### Async / await

### Generators

### Static methods

## References

[1] "Netscape and Sun announce JavaScript", PR Newswire, December 4, 1995. Available at [web archive](https://web.archive.org/web/20070916144913/http://wp.netscape.com/newsref/pr/newsrelease67.html).

[2] JavaScript Versions, W3Schools. Available at [w3schools](https://www.w3schools.com/js/js_versions.asp).

[3] ECMA International home page. Available at [ECMA Homepage](https://www.ecma-international.org/).

[4] ECMAScript 5 Features. Available at [w3schools](https://www.w3schools.com/js/js_es5.asp).

[5] ECMAScript 2015 support in Mozilla. Available at [mozilla](https://developer.mozilla.org/en-US/docs/Web/JavaScript/New_in_JavaScript/ECMAScript_2015_support_in_Mozilla).

[6] ECMAScript® 2015 Language Specification. Available at [ECMA international](http://www.ecma-international.org/ecma-262/6.0/index.html).
