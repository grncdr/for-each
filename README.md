# for-each [![build status][1]][2]

[![browser support][3]][4]

A better forEach.

## Example

Like `Array.prototype.forEach` but works on objects

``` js
var forEach = require("for-each")

forEach({ key: "value" }, function (value, key) {
    /* code */
})
```

## Installation

`npm install for-each`

## Contributors

 - Raynos

## MIT Licenced

  [1]: https://secure.travis-ci.org/Raynos/for-each.png
  [2]: http://travis-ci.org/Raynos/for-each
  [3]: https://ci.testling.com/Raynos/for-each.png
  [4]: https://ci.testling.com/Raynos/for-each

