# npmdoc-mammoth

#### api documentation for  [mammoth (v1.3.5)](https://github.com/mwilliamson/mammoth.js#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-mammoth.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mammoth) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mammoth.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mammoth)

#### Convert Word documents from docx to simple HTML and Markdown

[![NPM](https://nodei.co/npm/mammoth.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mammoth)

- [https://npmdoc.github.io/node-npmdoc-mammoth/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mammoth/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mammoth/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mammoth/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mammoth/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mammoth/build/screenCapture.npmPackageDependencyTree.svg)



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
        "shasum": "62f77b689e60e49a6677cba7109209daffa01e78",
        "tarball": "https://registry.npmjs.org/mammoth/-/mammoth-1.3.5.tgz"
    },
    "gitHead": "cedd2d6d5401b78030318f9e64f684d6ea86085d",
    "homepage": "https://github.com/mwilliamson/mammoth.js#readme",
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
    "version": "1.3.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
