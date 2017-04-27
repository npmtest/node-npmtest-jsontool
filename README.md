# npmtest-jsontool

#### basic test coverage for  [jsontool (v7.0.2)](https://github.com/trentm/json)  [![npm package](https://img.shields.io/npm/v/npmtest-jsontool.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jsontool) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jsontool.svg)](https://travis-ci.org/npmtest/node-npmtest-jsontool)

#### a 'json' command for massaging JSON on the command line

[![NPM](https://nodei.co/npm/jsontool.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jsontool)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jsontool/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsontool/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jsontool/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jsontool/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jsontool/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-jsontool/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-jsontool/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jsontool/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jsontool/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jsontool/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jsontool/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jsontool/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jsontool/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jsontool/build/test-report.html](https://npmtest.github.io/node-npmtest-jsontool/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jsontool/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jsontool/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jsontool/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jsontool/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jsontool/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jsontool/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jsontool/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jsontool/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Trent Mick",
        "url": "http://trentm.com"
    },
    "bin": {
        "json": "./lib/jsontool.js"
    },
    "bugs": {
        "url": "https://github.com/trentm/json/issues"
    },
    "contributors": [
        {
            "name": "Trent Mick",
            "url": "http://trentm.com"
        },
        {
            "name": "Yaniv Aknin",
            "url": "https://github.com/yaniv-aknin"
        },
        {
            "name": "Fred Kuo",
            "url": "https://github.com/fkuo"
        },
        {
            "name": "Bill Pijewski",
            "url": "https://github.com/pijewski"
        },
        {
            "name": "Isaac Schlueter",
            "url": "https://github.com/isaacs"
        }
    ],
    "dependencies": {},
    "deprecated": "jsontool is now called simply 'json'.  Please update your dependencies.",
    "description": "a 'json' command for massaging JSON on the command line",
    "devDependencies": {
        "ansidiff": "1.0",
        "async": "0.1.22",
        "ben": "0.0.x",
        "nodeunit": "0.8.x",
        "semver": "1.1.0",
        "uglify-js": "1.1.x"
    },
    "directories": {
        "man": "./man/man1"
    },
    "dist": {
        "shasum": "e29d3d1b0766ba4e179a18a96578b904dca43207",
        "tarball": "https://registry.npmjs.org/jsontool/-/jsontool-7.0.2.tgz"
    },
    "engines": [
        "node >=0.4.0"
    ],
    "homepage": "https://github.com/trentm/json",
    "keywords": [
        "json",
        "jsontool",
        "filter",
        "command",
        "shell"
    ],
    "main": "./lib/jsontool.js",
    "maintainers": [
        {
            "name": "trentm"
        }
    ],
    "man": [
        "/Users/trentm/.npm/jsontool/7.0.2/package/man/man1/json.1"
    ],
    "name": "jsontool",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/trentm/json.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "7.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
