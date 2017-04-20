# npmtest-swagger

#### basic test coverage for  [swagger (v0.7.5)](https://github.com/swagger-api/swagger-node#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-swagger.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-swagger) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-swagger.svg)](https://travis-ci.org/npmtest/node-npmtest-swagger)

#### The Swagger command-line. Provides Swagger utilities and project lifecycle support.

[![NPM](https://nodei.co/npm/swagger.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/swagger)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-swagger/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-swagger/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-swagger/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-swagger/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-swagger/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-swagger/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-swagger/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-swagger/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-swagger/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-swagger/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-swagger/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-swagger/build/test-report.html](https://npmtest.github.io/node-npmtest-swagger/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-swagger/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-swagger/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-swagger/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-swagger/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-swagger/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-swagger/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-swagger/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-swagger/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Scott Ganyo"
    },
    "bin": {
        "swagger": "bin/swagger.js",
        "swagger-project": "bin/swagger-project.js"
    },
    "bugs": {
        "url": "https://github.com/swagger-api/swagger-node/issues"
    },
    "dependencies": {
        "async": "^1.2.1",
        "commander": "^2.7.1",
        "connect": "^3.3.5",
        "debug": "^2.1.3",
        "fs-extra": "^0.24.0",
        "inquirer": "^0.10.0",
        "js-yaml": "^3.3.0",
        "lodash": "^3.10.0",
        "mocha": "^2.2.1",
        "nodemon": "^1.3.7",
        "serve-static": "^1.9.2",
        "swagger-converter": "^0.2.0",
        "swagger-editor": "^2.9.2",
        "swagger-test-templates": "^1.2.0",
        "swagger-tools": "^0.9.0"
    },
    "description": "The Swagger command-line. Provides Swagger utilities and project lifecycle support.",
    "devDependencies": {
        "chai": "^3.0.0",
        "mock-stdin": "^0.3.0",
        "proxyquire": "^1.4.0",
        "should": "^7.1.0",
        "sinon": "^1.15.4",
        "superagent": "^1.1.0",
        "supertest": "^1.1.0",
        "tmp": "^0.0.28",
        "z-schema": "^3.14.0"
    },
    "directories": {},
    "dist": {
        "shasum": "3be6ee3d392c3b006fc7a9b5b2d60c7e834860fd",
        "tarball": "https://registry.npmjs.org/swagger/-/swagger-0.7.5.tgz"
    },
    "gitHead": "91356200dee38487f3ecb7d67df3cb9dfc34af60",
    "homepage": "https://github.com/swagger-api/swagger-node#readme",
    "keywords": [
        "swagger",
        "api",
        "apis",
        "connect",
        "express"
    ],
    "license": "Apache 2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "wordnik"
        },
        {
            "name": "swagger-api"
        },
        {
            "name": "scottganyo"
        }
    ],
    "name": "swagger",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/swagger-api/swagger-node.git"
    },
    "scripts": {
        "coverage": "istanbul cover _mocha -- -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons",
        "start": "node app.js",
        "test": "mocha -u exports -R spec test/config.js test/util test/commands test/commands/project test/project-skeletons"
    },
    "version": "0.7.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
