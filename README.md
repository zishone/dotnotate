# dotnotate [![NPM](https://img.shields.io/npm/v/dotnotate)](https://www.npmjs.com/package/dotnotate) [![Build](https://github.com/zishone/dotnotate/workflows/build/badge.svg)](https://github.com/zishone/dotnotate/actions?query=workflow%3Abuild) [![codecov](https://codecov.io/gh/zishone/dotnotate/branch/main/graph/badge.svg?token=ZTGMHRjFc3)](https://codecov.io/gh/zishone/dotnotate) [![License](https://img.shields.io/github/license/zishone/dotnotate)](https://github.com/zishone/dotnotate/blob/master/LICENSE)
A utility function to convert JSON objects to dotnotation

## Installation
```shell
$ npm i @zishone/dotnotate
```

## Usage
### 1. Import dotnotate
```javascript
const { dotnotate } = require('@zishone/dotnotate');
```
### 2. Dotnotate
```javascript
const obj = { a: { b: { c: 1 } } };

const dotnotatedObj = dotnotate(obj);

console.log(JSON.stringify(dotnotatedObj, null, 2))
// {
//   'a.b.c': 1
// }
```

## Authors
* **Zishran Garces**

See also the list of [contributors](https://github.com/zishone/dotnotate/contributors) who participated in this project.

## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/zishone/dotnotate/blob/master/LICENSE) file for details.
