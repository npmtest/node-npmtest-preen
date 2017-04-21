# npmtest-preen

#### basic test coverage for  [preen (v1.2.0)](https://github.com/braddenver/preen)  [![npm package](https://img.shields.io/npm/v/npmtest-preen.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-preen) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-preen.svg)](https://travis-ci.org/npmtest/node-npmtest-preen)

#### preen unwanted files in packages installed via Bower

[![NPM](https://nodei.co/npm/preen.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/preen)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-preen/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-preen/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-preen/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-preen/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-preen/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-preen/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-preen/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-preen/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-preen/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-preen/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-preen/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-preen/build/test-report.html](https://npmtest.github.io/node-npmtest-preen/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-preen/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-preen/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-preen/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-preen/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-preen/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-preen/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-preen/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-preen/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "preen",
    "version": "1.2.0",
    "homepage": "https://github.com/braddenver/preen",
    "description": "preen unwanted files in packages installed via Bower",
    "main": "./lib/preen.js",
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1"
    },
    "dependencies": {
        "async": "~0.2.9",
        "bower": "0.10.x",
        "fs.extra": "1.2.x",
        "readdirp": "0.3.x",
        "minimatch": "0.2.x",
        "optimist": "0.6.x",
        "winston": "~0.7.3"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/BradDenver/Preen.git"
    },
    "keywords": [
        "Bower",
        "gulpfriendly"
    ],
    "author": "Brad Denver",
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/braddenver/preen/blob/master/LICENSE-MIT"
        }
    ],
    "bugs": {
        "url": "https://github.com/BradDenver/Preen/issues"
    },
    "bin": {
        "preen": "./bin/preen"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
