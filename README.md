# npmtest-grunt-zip

#### basic test coverage for  [grunt-zip (v0.17.1)](https://github.com/twolfson/grunt-zip)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-zip.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-zip) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-zip.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-zip)

#### Zip and unzip files via a grunt plugin

[![NPM](https://nodei.co/npm/grunt-zip.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-zip)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-zip/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-zip/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-zip/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-zip/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-zip/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-zip/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-zip/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-zip/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-zip/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-zip/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-zip/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-zip/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-zip/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-zip/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-zip/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-zip/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-zip/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-zip/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-zip/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-zip/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-zip/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "grunt-zip",
    "description": "Zip and unzip files via a grunt plugin",
    "version": "0.17.1",
    "homepage": "https://github.com/twolfson/grunt-zip",
    "author": {
        "name": "Todd Wolfson",
        "url": "http://twolfson.com/"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/twolfson/grunt-zip.git"
    },
    "bugs": {
        "url": "https://github.com/twolfson/grunt-zip/issues"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/twolfson/grunt-zip/blob/master/LICENSE-MIT"
        }
    ],
    "main": "grunt.js",
    "bin": "bin/grunt-zip",
    "engines": {
        "node": ">= 0.10.0"
    },
    "scripts": {
        "test": "rm -r test/actual &> /dev/null && mocha"
    },
    "dependencies": {
        "grunt-retro": "~0.6.0",
        "jszip": "~2.5.0"
    },
    "devDependencies": {
        "grunt": "~0.4.0",
        "underscore.string": "~2.3.1",
        "grunt-contrib-clean": "~0.4.0",
        "grunt-contrib-jshint": "~0.7.2",
        "grunt-contrib-watch": "~0.5.3",
        "grunt-cli": "~0.1.11",
        "mocha": "~1.20.1",
        "chai": "~1.9.1",
        "shell-quote": "~1.4.1"
    },
    "keywords": [
        "gruntplugin",
        "grunt",
        "zip",
        "unzip",
        "compress",
        "decompress"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
