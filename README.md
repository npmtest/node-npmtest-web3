# npmtest-web3

#### test coverage for  [web3 (v0.18.4)](https://github.com/ethereum/web3.js)  [![npm package](https://img.shields.io/npm/v/npmtest-web3.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-web3) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-web3.svg)](https://travis-ci.org/npmtest/node-npmtest-web3)

#### Ethereum JavaScript API, middleware to talk to a ethereum node over RPC

[![NPM](https://nodei.co/npm/web3.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/web3)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-web3/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-web3/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-web3/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-web3/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-web3/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-web3/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-web3/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-web3/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-web3/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-web3/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-web3/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-web3/build/test-report.html](https://npmtest.github.io/node-npmtest-web3/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-web3/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-web3/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-web3/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-web3/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-web3/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-web3/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-web3/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-web3/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "ethdev.com"
    },
    "authors": [
        {
            "name": "Marek Kotewicz",
            "url": "https://github.com/debris"
        },
        {
            "name": "Fabian Vogelsteller",
            "homepage": "http://frozeman.de"
        },
        {
            "name": "Marian Oancea",
            "url": "https://github.com/cubedro"
        },
        {
            "name": "Gav Wood",
            "homepage": "http://gavwood.com"
        },
        {
            "name": "Jeffery Wilcke",
            "url": "https://github.com/obscuren"
        }
    ],
    "browser": {
        "xmlhttprequest": "./lib/utils/browser-xhr.js"
    },
    "bugs": {
        "url": "https://github.com/ethereum/web3.js/issues"
    },
    "dependencies": {
        "bignumber.js": "git+https://github.com/debris/bignumber.js.git#94d7146671b9719e00a09c29b01a691bc85048c2",
        "crypto-js": "^3.1.4",
        "utf8": "^2.1.1",
        "xhr2": "*",
        "xmlhttprequest": "*"
    },
    "description": "Ethereum JavaScript API, middleware to talk to a ethereum node over RPC",
    "devDependencies": {
        "bower": ">=1.4.1",
        "browserify": ">=10.0",
        "chai": "^3.0.0",
        "coveralls": "^2.11.2",
        "del": ">=2.0.2",
        "exorcist": "^0.4.0",
        "gulp": ">=3.9.0",
        "gulp-jshint": ">=1.5.0",
        "gulp-rename": ">=1.2.0",
        "gulp-replace": "^0.5.3",
        "gulp-streamify": "0.0.5",
        "gulp-uglify": ">=1.2.0",
        "istanbul": "^0.4.4",
        "jshint": ">=2.5.0",
        "mocha": ">=2.3.3",
        "sandboxed-module": "^2.0.2",
        "vinyl-source-stream": "^1.1.0"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "81ec1784145491f2eaa8955b31c06049e07c5e7d",
        "tarball": "https://registry.npmjs.org/web3/-/web3-0.18.4.tgz"
    },
    "gitHead": "76f8798cb5c796073ba3605130cc14a152570312",
    "homepage": "https://github.com/ethereum/web3.js",
    "keywords": [
        "ethereum",
        "javascript",
        "API"
    ],
    "license": "LGPL-3.0",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "debris"
        },
        {
            "name": "frozeman"
        }
    ],
    "name": "web3",
    "namespace": "ethereum",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/ethereum/web3.js.git"
    },
    "scripts": {
        "build": "gulp",
        "lint": "jshint *.js lib",
        "test": "mocha",
        "test-coveralls": "istanbul cover _mocha -- -R spec && cat coverage/lcov.info | coveralls --verbose",
        "watch": "gulp watch"
    },
    "version": "0.18.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
