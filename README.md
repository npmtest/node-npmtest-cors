# npmtest-cors

#### basic test coverage for  [cors (v2.8.3)](https://github.com/expressjs/cors#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-cors.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cors) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cors.svg)](https://travis-ci.org/npmtest/node-npmtest-cors)

#### Node.js CORS middleware

[![NPM](https://nodei.co/npm/cors.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cors)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cors/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cors/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cors/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cors/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cors/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cors/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cors/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cors/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cors/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cors/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cors/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cors/build/test-report.html](https://npmtest.github.io/node-npmtest-cors/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cors/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cors/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cors/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cors/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cors/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cors/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cors/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cors/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Troy Goode",
        "url": "https://github.com/troygoode/"
    },
    "bugs": {
        "url": "https://github.com/expressjs/cors/issues"
    },
    "dependencies": {
        "object-assign": "^4",
        "vary": "^1"
    },
    "description": "Node.js CORS middleware",
    "devDependencies": {
        "basic-auth-connect": "^1.0.0",
        "body-parser": "^1.12.4",
        "eslint": "^0.21.2",
        "express": "^4.12.4",
        "istanbul": "^0.4.5",
        "mocha": "^2.2.5",
        "should": "^6.0.3",
        "supertest": "^1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "4cf78e1d23329a7496b2fc2225b77ca5bb5eb802",
        "tarball": "https://registry.npmjs.org/cors/-/cors-2.8.3.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "90a7881d8bf9c273ca9183e3ca95f74ce9f5aee2",
    "homepage": "https://github.com/expressjs/cors#readme",
    "keywords": [
        "cors",
        "express",
        "connect",
        "middleware"
    ],
    "license": "MIT",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "troygoode"
        },
        {
            "name": "dougwilson"
        }
    ],
    "name": "cors",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/expressjs/cors.git"
    },
    "scripts": {
        "lint": "eslint lib test",
        "test": "npm run lint && istanbul cover node_modules/mocha/bin/_mocha"
    },
    "version": "2.8.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
