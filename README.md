# npmtest-eventric

#### basic test coverage for  [eventric (v0.26.0)](https://github.com/efacilitation/eventric#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-eventric.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-eventric) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-eventric.svg)](https://travis-ci.org/npmtest/node-npmtest-eventric)

#### behavior-first application development

[![NPM](https://nodei.co/npm/eventric.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eventric)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-eventric/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-eventric/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-eventric/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-eventric/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-eventric/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-eventric/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-eventric/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-eventric/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-eventric/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-eventric/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-eventric/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-eventric/build/test-report.html](https://npmtest.github.io/node-npmtest-eventric/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-eventric/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-eventric/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-eventric/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eventric/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eventric/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eventric/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-eventric/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-eventric/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "eventric",
    "description": "behavior-first application development",
    "keywords": [
        "behavior-first",
        "ddd",
        "bdd",
        "cqrs",
        "eventsourcing",
        "reactive",
        "eventric"
    ],
    "version": "0.26.0",
    "repository": {
        "type": "git",
        "url": "https://github.com/efacilitation/eventric.git"
    },
    "main": "dist/release/eventric.js",
    "scripts": {
        "test": "gulp lint && gulp specs",
        "prepublish": "gulp symlink && gulp build"
    },
    "dependencies": {
        "eventric-remote-inmemory": "0.1.1",
        "eventric-store-inmemory": "0.3.0"
    },
    "devDependencies": {
        "chai": "3.5.0",
        "coffee-loader": "0.7.2",
        "coffee-script": "1.11.1",
        "es6-promise": "4.0.5",
        "gulp": "3.9.1",
        "gulp-coffeelint": "0.6.0",
        "gulp-mocha": "3.0.1",
        "gulp-symlink": "2.1.4",
        "gulp-util": "3.0.7",
        "karma": "1.3.0",
        "karma-mocha": "1.3.0",
        "karma-phantomjs-launcher": "1.0.2",
        "karma-spec-reporter": "0.0.26",
        "mocha": "3.1.2",
        "run-sequence": "1.2.2",
        "sinon": "1.17.6",
        "sinon-chai": "2.8.0",
        "webpack-stream": "3.2.0"
    },
    "author": "efa-GmbH <team@efa-gmbh.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/efacilitation/eventric/issues"
    },
    "homepage": "https://github.com/efacilitation/eventric#readme"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
