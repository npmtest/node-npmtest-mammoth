# npmtest-mammoth

#### basic test coverage for  [mammoth (v1.3.6)](https://github.com/mwilliamson/mammoth.js)  [![npm package](https://img.shields.io/npm/v/npmtest-mammoth.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mammoth) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mammoth.svg)](https://travis-ci.org/npmtest/node-npmtest-mammoth)

#### Convert Word documents from docx to simple HTML and Markdown

[![NPM](https://nodei.co/npm/mammoth.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mammoth)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mammoth/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mammoth/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mammoth/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mammoth/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mammoth/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-mammoth/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-mammoth/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mammoth/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mammoth/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mammoth/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mammoth/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mammoth/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mammoth/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mammoth/build/test-report.html](https://npmtest.github.io/node-npmtest-mammoth/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mammoth/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mammoth/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mammoth/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mammoth/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mammoth/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mammoth/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mammoth/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mammoth/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michael Williamson"
    },
    "bin": {
        "mammoth": "bin/mammoth"
    },
    "browser": {
        "./lib/unzip.js": "./browser/unzip.js",
        "./lib/docx/files.js": "./browser/docx/files.js"
    },
    "bugs": {
        "url": "https://github.com/mwilliamson/mammoth.js/issues"
    },
    "dependencies": {
        "argparse": "~1.0.3",
        "bluebird": "~3.4.0",
        "jszip": "~2.5.0",
        "lop": "~0.4.0",
        "path-is-absolute": "^1.0.0",
        "sax": "~1.1.1",
        "underscore": "~1.6.0",
        "xmlbuilder": "~2.6.4"
    },
    "description": "Convert Word documents from docx to simple HTML and Markdown",
    "devDependencies": {
        "browserify": "~13.0.1",
        "browserify-prepend-licenses": "~1.0.0",
        "duck": "~0.1.11",
        "eslint": "2.13.1",
        "flow-bin": "^0.32.0",
        "hamjest": "2.13.0",
        "mocha": "~2.2.5",
        "temp": "~0.7.0",
        "uglify-js": "~2.4.8"
    },
    "directories": {},
    "dist": {
        "shasum": "9469203bd338dda19ff9066a06c4257076db97c7",
        "tarball": "https://registry.npmjs.org/mammoth/-/mammoth-1.3.6.tgz"
    },
    "homepage": "https://github.com/mwilliamson/mammoth.js",
    "keywords": [
        "docx",
        "html",
        "office",
        "word",
        "markdown",
        "md"
    ],
    "license": "BSD-2-Clause",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "mwilliamson"
        }
    ],
    "name": "mammoth",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mwilliamson/mammoth.js.git"
    },
    "scripts": {
        "prepublish": "make mammoth.browser.min.js",
        "pretest": "eslint lib tests",
        "test": "mocha 'test/**/*.tests.js'"
    },
    "version": "1.3.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
