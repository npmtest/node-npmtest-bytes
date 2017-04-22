# npmtest-bytes

#### basic test-coverage for  [bytes (v2.5.0)](https://github.com/visionmedia/bytes.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-bytes.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bytes) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bytes.svg)](https://travis-ci.org/npmtest/node-npmtest-bytes)

#### Utility to parse a string bytes to bytes and vice-versa

[![NPM](https://nodei.co/npm/bytes.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bytes)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bytes/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bytes/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bytes/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bytes/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bytes/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bytes/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bytes/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bytes/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bytes/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bytes/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bytes/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bytes/build/test-report.html](https://npmtest.github.io/node-npmtest-bytes/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bytes/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bytes/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bytes/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bytes/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bytes/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bytes/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bytes/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bytes/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk",
        "url": "http://tjholowaychuk.com"
    },
    "bugs": {
        "url": "https://github.com/visionmedia/bytes.js/issues"
    },
    "component": {
        "scripts": {
            "bytes/index.js": "index.js"
        }
    },
    "contributors": [
        {
            "name": "Jed Watson"
        },
        {
            "name": "Théo FIDRY"
        }
    ],
    "dependencies": {},
    "description": "Utility to parse a string bytes to bytes and vice-versa",
    "devDependencies": {
        "mocha": "1.21.5",
        "nyc": "10.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "4c9423ea2d252c270c41b2bdefeff9bb6b62c06a",
        "tarball": "https://registry.npmjs.org/bytes/-/bytes-2.5.0.tgz"
    },
    "engines": {
        "node": ">= 0.6"
    },
    "files": [
        "History.md",
        "LICENSE",
        "Readme.md",
        "index.js"
    ],
    "gitHead": "a4b9af2bf289175f12b3538eb172f2489844b1ec",
    "homepage": "https://github.com/visionmedia/bytes.js#readme",
    "keywords": [
        "byte",
        "bytes",
        "utility",
        "parse",
        "parser",
        "convert",
        "converter"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        },
        {
            "name": "tjholowaychuk"
        }
    ],
    "name": "bytes",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/visionmedia/bytes.js.git"
    },
    "scripts": {
        "test": "mocha --check-leaks --reporter spec",
        "test-ci": "nyc --reporter=text npm test",
        "test-cov": "nyc --reporter=html --reporter=text npm test"
    },
    "version": "2.5.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
