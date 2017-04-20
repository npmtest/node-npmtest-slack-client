# npmtest-slack-client

#### basic test coverage for  [slack-client (v2.0.6)](https://github.com/slackhq/node-slack-client#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-slack-client.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-slack-client) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-slack-client.svg)](https://travis-ci.org/npmtest/node-npmtest-slack-client)

#### A library for creating a Slack client

[![NPM](https://nodei.co/npm/slack-client.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/slack-client)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-slack-client/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-slack-client/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-slack-client/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-slack-client/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-slack-client/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-slack-client/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-slack-client/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-slack-client/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-slack-client/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-slack-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-slack-client/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-slack-client/build/test-report.html](https://npmtest.github.io/node-npmtest-slack-client/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-slack-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-slack-client/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-slack-client/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-slack-client/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-slack-client/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-slack-client/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-slack-client/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-slack-client/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Slack Technologies, Inc."
    },
    "bugs": {
        "url": "http://github.com/slackhq/node-slack-client/issues"
    },
    "dependencies": {
        "async": "^1.5.0",
        "eventemitter3": "^1.1.1",
        "https-proxy-agent": "^1.0.0",
        "inherits": "^2.0.1",
        "lodash": "^3.10.1",
        "request": "^2.64.0",
        "retry": "^0.8.0",
        "url-join": "0.0.1",
        "winston": "^2.1.1",
        "ws": "^1.0.1"
    },
    "deprecated": "Use @slack/client instead, this package is no longer maintained",
    "description": "A library for creating a Slack client",
    "devDependencies": {
        "chai": "^3.3.0",
        "coveralls": "^2.11.6",
        "eslint": "^1.10.3",
        "eslint-config-airbnb": "^3.0.1",
        "istanbul": "^0.4.2",
        "istanbul-coveralls": "^1.0.3",
        "mocha": "~2.3.3",
        "mocha-lcov-reporter": "^1.0.0",
        "nock": "^2.15.0",
        "sinon": "^1.17.1"
    },
    "directories": {},
    "dist": {
        "shasum": "78eb89f7f527620e145ccd7b1d8d16bd670bb383",
        "tarball": "https://registry.npmjs.org/slack-client/-/slack-client-2.0.6.tgz"
    },
    "engines": {
        "node": ">= 0.12.x",
        "npm": ">= 1.1.x"
    },
    "gitHead": "8da0c2b08a8210609b612a2389c90c838a1ff408",
    "homepage": "https://github.com/slackhq/node-slack-client#readme",
    "keywords": [
        "slack"
    ],
    "license": "MIT",
    "main": "./index",
    "maintainers": [
        {
            "name": "grantmd"
        },
        {
            "name": "l12s"
        },
        {
            "name": "paulhammond"
        }
    ],
    "name": "slack-client",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/slackhq/node-slack-client.git"
    },
    "scripts": {
        "cover": "istanbul cover --report lcovonly _mocha -- --recursive",
        "coveralls": "npm run cover && istanbul-coveralls",
        "lint": "eslint . --ignore-path .gitignore",
        "test": "mocha --recursive --reporter spec test"
    },
    "version": "2.0.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
