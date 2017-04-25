# npmtest-standard-format

#### basic test coverage for  [standard-format (v2.2.4)](https://github.com/maxogden/standard-format)  [![npm package](https://img.shields.io/npm/v/npmtest-standard-format.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-standard-format) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-standard-format.svg)](https://travis-ci.org/npmtest/node-npmtest-standard-format)

#### attempts to reformat javascript to comply with feross/standard style

[![NPM](https://nodei.co/npm/standard-format.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/standard-format)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-standard-format/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-standard-format/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-standard-format/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-standard-format/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-standard-format/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-standard-format/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-standard-format/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-standard-format/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-standard-format/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-standard-format/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-standard-format/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-standard-format/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-standard-format/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-standard-format/build/test-report.html](https://npmtest.github.io/node-npmtest-standard-format/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-standard-format/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-standard-format/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-standard-format/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-standard-format/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-standard-format/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-standard-format/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-standard-format/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-standard-format/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "max ogden"
    },
    "bin": {
        "standard-format": "./bin.js"
    },
    "bugs": {
        "url": "https://github.com/maxogden/standard-format/issues"
    },
    "dependencies": {
        "deglob": "^1.0.0",
        "esformatter": "^0.9.0",
        "esformatter-eol-last": "^1.0.0",
        "esformatter-jsx": "^7.0.0",
        "esformatter-literal-notation": "^1.0.0",
        "esformatter-quotes": "^1.0.0",
        "esformatter-remove-trailing-commas": "^1.0.1",
        "esformatter-semicolon-first": "^1.1.0",
        "esformatter-spaced-lined-comment": "^2.0.0",
        "minimist": "^1.1.0",
        "stdin": "0.0.1"
    },
    "description": "attempts to reformat javascript to comply with feross/standard style",
    "devDependencies": {
        "concat-stream": "^1.4.7",
        "debug": "^2.1.1",
        "once": "^1.3.1",
        "skip-stream": "0.0.3",
        "split": "^1.0.0",
        "standard": "*",
        "stream-reduce": "^1.0.3",
        "tap-spec": "^4.1.0",
        "tape": "^4.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "b90fb39a635f749cd4fd117fe4730d31179aaeef",
        "tarball": "https://registry.npmjs.org/standard-format/-/standard-format-2.2.4.tgz"
    },
    "gitHead": "a887dcc27e19afb378941703e4541db9eecaf56b",
    "homepage": "https://github.com/maxogden/standard-format",
    "license": "BSD-2-Clause",
    "main": "index.js",
    "maintainers": [
        {
            "name": "maxogden"
        },
        {
            "name": "jb55"
        },
        {
            "name": "feross"
        },
        {
            "name": "bret"
        },
        {
            "name": "flet"
        }
    ],
    "name": "standard-format",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/maxogden/standard-format.git"
    },
    "scripts": {
        "failing": "standard && tape test/failing/*.js | tap-spec",
        "test": "standard && tape test/*.js | tap-spec",
        "test-file": "<test/test-files/test.js ./bin.js | standard"
    },
    "standard": {
        "ignore": [
            "**test/test-files/**",
            "**test/failing/**"
        ]
    },
    "version": "2.2.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
