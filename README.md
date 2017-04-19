# npmtest-ddos

#### test coverage for  [ddos (v0.1.16)](https://github.com/rook2pawn/node-ddos)  [![npm package](https://img.shields.io/npm/v/npmtest-ddos.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ddos) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ddos.svg)](https://travis-ci.org/npmtest/node-npmtest-ddos)

#### Configurable Denial-Of-Service prevention for http services

[![NPM](https://nodei.co/npm/ddos.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ddos)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ddos/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ddos/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ddos/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ddos/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ddos/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ddos/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ddos/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ddos/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ddos/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ddos/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ddos/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ddos/build/test-report.html](https://npmtest.github.io/node-npmtest-ddos/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ddos/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ddos/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ddos/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ddos/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ddos/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ddos/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ddos/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ddos/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "David Wee",
        "url": "http://rook2pawn.com"
    },
    "bugs": {
        "url": "https://github.com/rook2pawn/node-ddos/issues"
    },
    "dependencies": {
        "hashish": "",
        "response": ""
    },
    "description": "Configurable Denial-Of-Service prevention for http services",
    "devDependencies": {
        "body-parser": "^1.15.2",
        "express": "",
        "koa": "^1.1.2",
        "mocha": "^2.3.4",
        "queuelib": "",
        "request": "",
        "supertest": "^1.1.0",
        "tape": ""
    },
    "directories": {},
    "dist": {
        "shasum": "45c7cc77ebcd3f7a41a500d23d96dbeb2bca34c9",
        "tarball": "https://registry.npmjs.org/ddos/-/ddos-0.1.16.tgz"
    },
    "gitHead": "2640c00a03ac8378b71c135d49bf136db871dd54",
    "homepage": "https://github.com/rook2pawn/node-ddos",
    "keywords": [
        "ddos",
        "rate",
        "limiting"
    ],
    "license": "ISC",
    "main": "index.js",
    "maintainers": [
        {
            "name": "rook2pawn"
        }
    ],
    "name": "ddos",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/rook2pawn/node-ddos.git"
    },
    "scripts": {
        "test": "tape test/test-whitelist.js && tape test/test-post.js && tape test/test-express.js && mocha --harmony test/test-koa.js"
    },
    "version": "0.1.16"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
