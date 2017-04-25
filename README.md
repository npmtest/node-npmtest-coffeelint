# npmtest-coffeelint

#### basic test coverage for  [coffeelint (v1.16.0)](http://www.coffeelint.org)  [![npm package](https://img.shields.io/npm/v/npmtest-coffeelint.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-coffeelint) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-coffeelint.svg)](https://travis-ci.org/npmtest/node-npmtest-coffeelint)

#### Lint your CoffeeScript

[![NPM](https://nodei.co/npm/coffeelint.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/coffeelint)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-coffeelint/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-coffeelint/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-coffeelint/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-coffeelint/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-coffeelint/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-coffeelint/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-coffeelint/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-coffeelint/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-coffeelint/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-coffeelint/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-coffeelint/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-coffeelint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-coffeelint/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-coffeelint/build/test-report.html](https://npmtest.github.io/node-npmtest-coffeelint/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-coffeelint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-coffeelint/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-coffeelint/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-coffeelint/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-coffeelint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-coffeelint/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-coffeelint/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-coffeelint/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matthew Perpick"
    },
    "bin": {
        "coffeelint": "./bin/coffeelint"
    },
    "bugs": {
        "url": "https://github.com/clutchski/coffeelint/issues"
    },
    "dependencies": {
        "coffee-script": "~1.11.0",
        "glob": "^7.0.6",
        "ignore": "^3.0.9",
        "optimist": "^0.6.1",
        "resolve": "^0.6.3",
        "strip-json-comments": "^1.0.2"
    },
    "description": "Lint your CoffeeScript",
    "devDependencies": {
        "underscore": ">=1.4.4",
        "vows": ">=0.8.1"
    },
    "directories": {},
    "dist": {
        "shasum": "83d8ed1dafde3a677de44e7b8a18be607761e6d8",
        "tarball": "https://registry.npmjs.org/coffeelint/-/coffeelint-1.16.0.tgz"
    },
    "engines": {
        "node": ">=0.8.0",
        "npm": ">=1.3.7"
    },
    "gitHead": "2013313ff7b9ecd28d99b5c71abb51fbfa450bfe",
    "homepage": "http://www.coffeelint.org",
    "keywords": [
        "lint",
        "coffeescript",
        "coffee-script"
    ],
    "license": "MIT",
    "main": "./lib/coffeelint.js",
    "maintainers": [
        {
            "name": "clutchski"
        },
        {
            "name": "thomas.frossman"
        },
        {
            "name": "asaayers"
        },
        {
            "name": "swang"
        }
    ],
    "name": "coffeelint",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/clutchski/coffeelint.git"
    },
    "scripts": {
        "compile": "cake compile",
        "lint": "cake compile && ./bin/coffeelint .",
        "lint-csv": "cake compile && ./bin/coffeelint --csv .",
        "lint-jslint": "cake compile && ./bin/coffeelint --jslint .",
        "postpublish": "cake postpublish",
        "posttest": "npm run lint",
        "prepublish": "cake prepublish",
        "pretest": "cake compile",
        "publish": "cake publish",
        "test": "./vowsrunner.js --spec test/*.coffee test/*.litcoffee",
        "testrule": "npm run compile && ./vowsrunner.js --spec"
    },
    "version": "1.16.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
