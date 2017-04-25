# npmtest-mockgoose

#### basic test coverage for  [mockgoose (v7.3.1)](https://github.com/Mockgoose/Mockgoose)  [![npm package](https://img.shields.io/npm/v/npmtest-mockgoose.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-mockgoose) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-mockgoose.svg)](https://travis-ci.org/npmtest/node-npmtest-mockgoose)

#### Mockgoose is an in memory database mock to allow for testing of applications that rely on Mongoose.

[![NPM](https://nodei.co/npm/mockgoose.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mockgoose)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-mockgoose/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-mockgoose/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-mockgoose/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-mockgoose/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-mockgoose/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-mockgoose/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-mockgoose/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-mockgoose/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-mockgoose/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-mockgoose/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-mockgoose/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-mockgoose/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-mockgoose/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-mockgoose/build/test-report.html](https://npmtest.github.io/node-npmtest-mockgoose/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-mockgoose/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-mockgoose/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-mockgoose/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mockgoose/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mockgoose/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mockgoose/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-mockgoose/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-mockgoose/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Anthony McCormick"
    },
    "bugs": {
        "url": "https://github.com/Mockgoose/Mockgoose/issues"
    },
    "dependencies": {
        "async": "2.1.5",
        "debug": "2.2.0",
        "fs-extra": "^2.0.0",
        "https-proxy-agent": "1.0.0",
        "mongodb-prebuilt": "^6.3.1",
        "portfinder": "^1.0.13",
        "rimraf": "^2.6.1",
        "uuid": "^3.0.1"
    },
    "description": "Mockgoose is an in memory database mock to allow for testing of applications that rely on Mongoose.",
    "devDependencies": {
        "@types/async": "~2.0.39",
        "@types/fs-extra": "~0.0.37",
        "@types/mongoose": "^4.7.6",
        "@types/node": "^6.0.58",
        "@types/node-uuid": "0.0.28",
        "chai": "~2.2.0",
        "mocha": "~2.2.4",
        "mongoose": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "8990fd353c6fb3efc0684b745c3d504bb19a2dba",
        "tarball": "https://registry.npmjs.org/mockgoose/-/mockgoose-7.3.1.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "c545f6aa6db638e8e4ee4a9b35fa4b225e4cd464",
    "homepage": "https://github.com/Mockgoose/Mockgoose",
    "keywords": [
        "mongodb",
        "mongoose",
        "datastore",
        "nosql",
        "sql",
        "db",
        "database",
        "mock",
        "stub",
        "in memory"
    ],
    "license": "MIT",
    "main": "built/mockgoose.js",
    "maintainers": [
        {
            "name": "mccormicka"
        },
        {
            "name": "winfinit"
        }
    ],
    "name": "mockgoose",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mockgoose/Mockgoose.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "types": "built/mockgoose.d.ts",
    "version": "7.3.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
