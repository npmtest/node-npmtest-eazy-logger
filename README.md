# npmtest-eazy-logger

#### basic test coverage for  [eazy-logger (v3.0.2)](https://github.com/shakyshane/easy-logger)  [![npm package](https://img.shields.io/npm/v/npmtest-eazy-logger.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-eazy-logger) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-eazy-logger.svg)](https://travis-ci.org/npmtest/node-npmtest-eazy-logger)

#### Simple cli logger

[![NPM](https://nodei.co/npm/eazy-logger.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eazy-logger)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-eazy-logger/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-eazy-logger/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-eazy-logger/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-eazy-logger/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-eazy-logger/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-eazy-logger/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-eazy-logger/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-eazy-logger/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-eazy-logger/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-eazy-logger/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-eazy-logger/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-eazy-logger/build/test-report.html](https://npmtest.github.io/node-npmtest-eazy-logger/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-eazy-logger/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-eazy-logger/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-eazy-logger/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eazy-logger/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eazy-logger/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eazy-logger/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-eazy-logger/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-eazy-logger/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "eazy-logger",
    "description": "Simple cli logger",
    "version": "3.0.2",
    "homepage": "https://github.com/shakyshane/easy-logger",
    "author": {
        "name": "Shane Osbourne"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/shakyshane/easy-logger.git"
    },
    "bugs": {
        "url": "https://github.com/shakyshane/easy-logger/issues"
    },
    "licenses": [
        {
            "type": "Apache 2.0",
            "url": "https://github.com/shakyshane/easy-logger/blob/master/LICENSE"
        }
    ],
    "files": [
        "index.js",
        "lodash.custom.js",
        "example.js"
    ],
    "main": "index.js",
    "engines": {
        "node": ">= 0.8.0"
    },
    "scripts": {
        "lint": "jshint index.js test/*.js",
        "test": "npm run lint && mocha",
        "lodash": "lodash include=cloneDeep,merge exports=node",
        "cover": "istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js && rm -rf ./coverage"
    },
    "dependencies": {
        "tfunk": "^3.0.1"
    },
    "devDependencies": {
        "chai": "^3.5.0",
        "chalk": "^1.1.1",
        "coveralls": "^2.11.2",
        "jshint": "^2.6.0",
        "lodash-cli": "4.12.0",
        "mocha": "^2.1.0",
        "sinon": "^1.12.2"
    },
    "keywords": [
        "plugins"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
