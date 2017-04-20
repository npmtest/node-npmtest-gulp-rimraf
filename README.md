# npmtest-gulp-rimraf

#### basic test coverage for  [gulp-rimraf (v0.2.1)](https://github.com/robrich/gulp-rimraf)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-rimraf.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-rimraf) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-rimraf.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-rimraf)

#### rimraf plugin for gulp

[![NPM](https://nodei.co/npm/gulp-rimraf.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-rimraf)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-rimraf/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-rimraf/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-rimraf/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-rimraf/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-rimraf/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-rimraf/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-rimraf/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-rimraf/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-rimraf/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-rimraf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-rimraf/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-rimraf/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-rimraf/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-rimraf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-rimraf/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-rimraf/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-rimraf/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-rimraf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-rimraf/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-rimraf/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-rimraf/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-rimraf",
    "description": "rimraf plugin for gulp",
    "version": "0.2.1",
    "homepage": "https://github.com/robrich/gulp-rimraf",
    "repository": "git://github.com/robrich/gulp-rimraf.git",
    "author": "Rob Richardson (http://robrich.org/)",
    "main": "./index.js",
    "keywords": [
        "gulpplugin",
        "rimraf",
        "clean",
        "remove",
        "delete",
        "gulp-clean"
    ],
    "dependencies": {
        "gulp-util": "^3.0.7",
        "rimraf": "^2.5.4",
        "through2": "^2.0.1"
    },
    "devDependencies": {
        "jshint": "^2.9.4",
        "mocha": "^3.1.2",
        "should": "^11.1.1",
        "vinyl": "^1.2.0"
    },
    "scripts": {
        "test": "mocha && jshint ."
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
