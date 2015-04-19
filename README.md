# unique-by

[![build status][build-png]][build]
[![Coverage Status][cover-png]][cover]
[![Davis Dependency status][dep-png]][dep]
[![NPM][npm-png]][npm]

Create a unique array of objects.

## Example

```js
var uniqueBy = require('unique-by');

uniqueBy(arr, function getValue(obj) {
  return obj.someKey;
});

uniqueBy(arr, 'someKey');
```

## Installation

`npm install unique-by`

## Tests

`npm test`

## NPM scripts

 - `npm run cover` This runs the tests with code coverage
 - `npm run lint` This will run the linter on your code
 - `npm test` This will run the tests.
 - `npm run trace` This will run your tests in tracing mode.
 - `npm run travis` This is run by travis.CI to run your tests
 - `npm run view-cover` This will show code coverage in a browser

## Contributors

 - Matt Morgan

## MIT Licenced

  [build-png]: https://secure.travis-ci.org/mlmorg/unique-by.png
  [build]: https://travis-ci.org/mlmorg/unique-by
  [cover-png]: https://coveralls.io/repos/mlmorg/unique-by/badge.png
  [cover]: https://coveralls.io/r/mlmorg/unique-by
  [dep-png]: https://david-dm.org/mlmorg/unique-by.png
  [dep]: https://david-dm.org/mlmorg/unique-by
  [test-png]: https://ci.testling.com/mlmorg/unique-by.png
  [tes]: https://ci.testling.com/mlmorg/unique-by
  [npm-png]: https://nodei.co/npm/unique-by.png?stars&downloads
  [npm]: https://nodei.co/npm/unique-by
