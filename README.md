# npmtest-node-plantuml

#### basic test coverage for  [node-plantuml (v0.5.0)](https://github.com/markushedvall/node-plantuml)  [![npm package](https://img.shields.io/npm/v/npmtest-node-plantuml.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-plantuml) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-plantuml.svg)](https://travis-ci.org/npmtest/node-npmtest-node-plantuml)

#### A Node.js module and CLI for running PlantUML

[![NPM](https://nodei.co/npm/node-plantuml.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-plantuml)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-plantuml/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-plantuml/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-plantuml/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-plantuml/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-plantuml/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-node-plantuml/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-node-plantuml/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-plantuml/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-plantuml/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-plantuml/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-plantuml/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-plantuml/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-plantuml/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-plantuml/build/test-report.html](https://npmtest.github.io/node-npmtest-node-plantuml/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-plantuml/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-plantuml/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-plantuml/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-plantuml/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-plantuml/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-plantuml/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-plantuml/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-plantuml/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Markus Hedvall"
    },
    "bin": {
        "puml": "index.js"
    },
    "bugs": {
        "url": "https://github.com/markushedvall/node-plantuml/issues"
    },
    "dependencies": {
        "commander": "^2.8.1",
        "node-nailgun-client": "^0.1.0",
        "node-nailgun-server": "^0.1.3",
        "plantuml-encoder": "^1.2.4"
    },
    "description": "A Node.js module and CLI for running PlantUML",
    "devDependencies": {
        "chai": "^3.2.0",
        "mocha": "^2.3.1",
        "shelljs": "^0.5.3",
        "standard": "^5.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "03c2ed856e6b272c714a1568453a747c266fdc1f",
        "tarball": "https://registry.npmjs.org/node-plantuml/-/node-plantuml-0.5.0.tgz"
    },
    "gitHead": "0b8d48c58c9632536180c4b10fe7e9af67a48f7d",
    "homepage": "https://github.com/markushedvall/node-plantuml",
    "keywords": [
        "plantuml",
        "uml",
        "diagram"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "markushedvall"
        }
    ],
    "name": "node-plantuml",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/markushedvall/node-plantuml.git"
    },
    "scripts": {
        "build": "node nail/build.js",
        "test": "standard && node test/fixtures/prepare.js && mocha"
    },
    "version": "0.5.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
