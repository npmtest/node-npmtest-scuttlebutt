# test coverage for  [scuttlebutt (v5.6.15)](https://github.com/dominictarr/scuttlebutt)  [![npm package](https://img.shields.io/npm/v/npmtest-scuttlebutt.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-scuttlebutt) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-scuttlebutt.svg)](https://travis-ci.org/npmtest/node-npmtest-scuttlebutt)
#### replicate data via scuttlebutt protocol

[![NPM](https://nodei.co/npm/scuttlebutt.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/scuttlebutt)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-scuttlebutt/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-scuttlebutt/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-scuttlebutt/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-scuttlebutt/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-scuttlebutt/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-scuttlebutt/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-scuttlebutt/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-scuttlebutt/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-scuttlebutt/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-scuttlebutt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-scuttlebutt/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-scuttlebutt/build/test-report.html](https://npmtest.github.io/node-npmtest-scuttlebutt/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-scuttlebutt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-scuttlebutt/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-scuttlebutt/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-scuttlebutt/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-scuttlebutt/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-scuttlebutt/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-scuttlebutt/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-scuttlebutt/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dominic Tarr",
        "url": "http://dominictarr.com"
    },
    "bugs": {
        "url": "https://github.com/dominictarr/scuttlebutt/issues"
    },
    "dependencies": {
        "duplex": "~1.0.0",
        "iterate": "0.1.0",
        "monotonic-timestamp": "~0.0.8",
        "stream-serializer": "1.1.2"
    },
    "description": "replicate data via scuttlebutt protocol",
    "devDependencies": {
        "event-stream": "~3.0",
        "macgyver": "~1.10",
        "request": "~2.16.6",
        "tape": "~0.1.5"
    },
    "directories": {},
    "dist": {
        "shasum": "8599a8fa5c3ebb1867d1c5c39ea719f4ed6d7a88",
        "tarball": "https://registry.npmjs.org/scuttlebutt/-/scuttlebutt-5.6.15.tgz"
    },
    "gitHead": "7b7f89ab569329334daaa1ed4e9a3ecbed224a66",
    "homepage": "https://github.com/dominictarr/scuttlebutt",
    "maintainers": [
        {
            "name": "dominictarr"
        }
    ],
    "name": "scuttlebutt",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/dominictarr/scuttlebutt.git"
    },
    "scripts": {
        "test": "set -e; for test in test/*.js; do node $test; done"
    },
    "testling": {
        "files": "test/*.js",
        "browsers": {
            "ie": [
                8,
                9,
                10
            ],
            "firefox": [
                17,
                18
            ],
            "chrome": [
                23,
                24
            ],
            "safari": [
                5,
                6
            ],
            "opera": [
                12
            ]
        }
    },
    "version": "5.6.15"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
