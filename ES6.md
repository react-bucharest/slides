ES6+
====

**TODO**:
 - check that ES6 features are actually ES6 and ES7+ features are not ES6

What is ES6
-----------

- next version of JavaScript
- inspired from CoffeeScript

ES6 Features
------------

- `let`/`const`
  - block scoping vs function scoping
  - temporal dead zone
  - `const` is not really const
- arrow functions
  - `this` scope
  - performance considerations
  - shorthands (`(x) => {}` vs `x => {}`, `x => 2*x`)
- `import` / `export` statements
  - they work great in the browser, with Babel / Webpack
- default parameters
- rest/spread operator + property shorthand
  - functional-style pattern matching
  - awesome with Redux
  - `Object.assign({}, obj, { key: key })` vs `{ ...obj, key }`
- promises
  - standardized!
  - how they solve callback hell
  - they work great with arrow functions
  - `Promise.all`, `Promise.race`, `Promise.resolve` / `Promise.reject`

How to use ES6
--------------

### caniuse.com / node.green

### Natively (in Node) -- check your Node version

### Lots of tools for compiling (Browserify, Webpack, Traceur, Babel, etc.)

- Babel
  - Plugins and Presets
  - I'd rather use ESNext features rather than just ES6 -- if you're going to compile, do it all the way
  - I use stage 0 (plus whatever else I need, like JSX or Flow)
- Webpack
  - Plugins
- NPM scripts to make your life easier
  - `package.json` for frontend code!
  - `npm init` / `npm install --save`

ES7+ Sneak Peek
---------------

**NOTE**: this should take as little time as possible

- `async` / `await`
- decorators
- Python-like array comprehensions and generator comprehensions
- typed objects
- you can use all this today!

### Closing words
- The JS language is a jungle right now. Make the best of it!
