# npmtest-lazo

#### basic test coverage for  [lazo (v3.0.1)](https://github.com/lazojs/lazo)  [![npm package](https://img.shields.io/npm/v/npmtest-lazo.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-lazo) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-lazo.svg)](https://travis-ci.org/npmtest/node-npmtest-lazo)

#### A client-server web framework built on Node.js that allows front-end developers to easily create a 100% SEO compliant, component MVC structured web application with an optimized first page load.

[![NPM](https://nodei.co/npm/lazo.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/lazo)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-lazo/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-lazo/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-lazo/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-lazo/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-lazo/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-lazo/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-lazo/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-lazo/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-lazo/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-lazo/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-lazo/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-lazo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-lazo/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-lazo/build/test-report.html](https://npmtest.github.io/node-npmtest-lazo/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-lazo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-lazo/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-lazo/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-lazo/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lazo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lazo/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-lazo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-lazo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "lazo": "lazo.js"
    },
    "bugs": {
        "url": "https://github.com/lazojs/lazo/issues"
    },
    "dependencies": {
        "async": "0.6.2",
        "backbone": "1.1.1",
        "continuation-local-storage": "3.1.0",
        "crumb": "3.1.0",
        "flexo.js": "0.2.x",
        "forever": "0.10.8",
        "fs-extra": "0.6.3",
        "handlebars": "2.0.0",
        "hapi": "6.7.1",
        "hermes-conrad": "1.x.x",
        "htmlparser": "1.7.7",
        "htmlparser-tostring": "0.0.2",
        "jquery": "1.11.1",
        "jquery.cookie": "1.4.1",
        "lodash": "2.4.1",
        "node-dir": "0.1.5",
        "request": "2.40.0",
        "requirejs": "2.1.11",
        "requirejs-plugins": "1.0.2",
        "requirejs-text": "2.0.12",
        "underscore": "1.6.0",
        "yargs": "3.6.0"
    },
    "description": "A client-server web framework built on Node.js that allows front-end developers to easily create a 100% SEO compliant, component MVC structured web application with an optimized first page load.",
    "devDependencies": {
        "grunt": "0.4.5",
        "grunt-contrib-requirejs": "0.4.x",
        "grunt-contrib-watch": "0.5.x",
        "grunt-exec": "0.4.6",
        "intern": "2.1.1",
        "phantomjs": "1.9.13",
        "selenium-server": "2.43.1",
        "sinon": "1.10.3",
        "sinon-chai": "2.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "a264c46aa88be3e434e44d58342bfe8edc4bf65f",
        "tarball": "https://registry.npmjs.org/lazo/-/lazo-3.0.1.tgz"
    },
    "gitHead": "7134e096b8e03c6881fdcf20d720342c722fbaac",
    "homepage": "https://github.com/lazojs/lazo",
    "keywords": [
        "backbone",
        "requirejs",
        "hapi",
        "mvc",
        "client-server",
        "lazo",
        "lazojs",
        "isomorphic javascript",
        "SEO"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "/blob/master/LICENSE-MIT"
        }
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "jstrimpel"
        },
        {
            "name": "cbarnes"
        },
        {
            "name": "mdavis52"
        },
        {
            "name": "paulknepper"
        },
        {
            "name": "rodfernandez"
        }
    ],
    "name": "lazo",
    "optionalDependencies": {},
    "private": false,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/lazojs/lazo.git"
    },
    "scripts": {
        "prepublish": "node bin/postinstall; grunt requirejs",
        "start": "lazo",
        "test": "grunt test"
    },
    "version": "3.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
