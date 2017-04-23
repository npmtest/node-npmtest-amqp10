# npmtest-amqp10

#### basic test coverage for  [amqp10 (v3.5.2)](https://github.com/noodlefrenzy/node-amqp10)  [![npm package](https://img.shields.io/npm/v/npmtest-amqp10.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-amqp10) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-amqp10.svg)](https://travis-ci.org/npmtest/node-npmtest-amqp10)

#### Native AMQP-1.0 client for node.js

[![NPM](https://nodei.co/npm/amqp10.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/amqp10)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-amqp10/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-amqp10/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-amqp10/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-amqp10/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-amqp10/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-amqp10/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-amqp10/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-amqp10/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-amqp10/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-amqp10/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-amqp10/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-amqp10/build/test-report.html](https://npmtest.github.io/node-npmtest-amqp10/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-amqp10/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-amqp10/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-amqp10/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-amqp10/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-amqp10/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-amqp10/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-amqp10/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-amqp10/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "noodlefrenzy",
        "url": "http://www.mikelanzetta.com"
    },
    "bugs": {
        "url": "https://github.com/noodlefrenzy/node-amqp10/issues"
    },
    "contributors": [
        {
            "name": "mbroadst",
            "url": "https://github.com/mbroadst"
        }
    ],
    "dependencies": {
        "bl": "^1.1.2",
        "bluebird": "^3.4.6",
        "buffer-builder": "^0.2.0",
        "debug": "^2.3.3",
        "lodash": "^4.17.2",
        "node-int64": "^0.4.0",
        "stately.js": "^1.3.0"
    },
    "description": "Native AMQP-1.0 client for node.js",
    "devDependencies": {
        "benchmark": "^2.1.2",
        "chai": "^3.5.0",
        "chai-as-promised": "^6.0.0",
        "chai-string": "^1.3.0",
        "conventional-changelog-cli": "^1.2.0",
        "gh-pages": "^0.12.0",
        "istanbul": "^0.4.5",
        "jsdoc": "^3.4.2",
        "jshint": "^2.9.4",
        "mocha": "^3.2.0",
        "qmf2": "^0.1.5",
        "stream-buffers": "^3.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "5857c0c5c61cbc82235d8d14df75325dd7405448",
        "tarball": "https://registry.npmjs.org/amqp10/-/amqp10-3.5.2.tgz"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "gitHead": "fc99e24d9265548f1f4c9e0aabc5ecdefcb6c7cf",
    "homepage": "https://github.com/noodlefrenzy/node-amqp10",
    "keywords": [
        "amqp",
        "amqp 1.0",
        "amqp-1-0",
        "amqp10",
        "messaging",
        "queues"
    ],
    "license": "MIT",
    "main": "./lib",
    "maintainers": [
        {
            "name": "mbroadst"
        },
        {
            "name": "noodlefrenzy"
        }
    ],
    "name": "amqp10",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/noodlefrenzy/node-amqp10.git"
    },
    "scripts": {
        "version": "make changelog && git add CHANGELOG.md && make docs"
    },
    "version": "3.5.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
