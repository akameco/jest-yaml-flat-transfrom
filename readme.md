# jest-yaml-flat-transfrom [![Build Status](https://travis-ci.org/akameco/jest-yaml-flat-transfrom.svg?branch=master)](https://travis-ci.org/akameco/jest-yaml-flat-transfrom)

> transform yaml to flatten object


## Install

```
$ npm install jest-yaml-flat-transfrom
```

## Usage

package.json

```json
{
  "jest": {
    "moduleFileExtensions": [
      "js",
      "jsx",
      "json",
      "yml"
    ],
    "transform": {
      "\\.yml$": "jest-yaml-flat-transform"
    }
  }
}
```

## License

MIT © [akameco](http://akameco.github.io)
