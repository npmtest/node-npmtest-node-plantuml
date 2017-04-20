# npmtest-node-plantuml

#### basic test coverage for  node-plantuml (v0.5.0)  [![npm package](https://img.shields.io/npm/v/npmtest-node-plantuml.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-plantuml) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-plantuml.svg)](https://travis-ci.org/npmtest/node-npmtest-node-plantuml)

#### A Node.js module and CLI for running PlantUML

[![NPM](https://nodei.co/npm/node-plantuml.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-plantuml)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-plantuml/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-plantuml/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-plantuml/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-plantuml/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-plantuml/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-plantuml/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-plantuml/tree/gh-pages/build)|

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
    "name": "node-plantuml",
    "version": "0.5.0",
    "description": "A Node.js module and CLI for running PlantUML",
    "main": "index.js",
    "author": "Markus Hedvall <mackanhedvall@gmail.com>",
    "repository": "https://github.com/markushedvall/node-plantuml",
    "license": "MIT",
    "keywords": [
        "plantuml",
        "uml",
        "diagram"
    ],
    "dependencies": {
        "commander": "^2.8.1",
        "node-nailgun-client": "^0.1.0",
        "node-nailgun-server": "^0.1.3",
        "plantuml-encoder": "^1.2.4"
    },
    "devDependencies": {
        "chai": "^3.2.0",
        "mocha": "^2.3.1",
        "shelljs": "^0.5.3",
        "standard": "^5.0.2"
    },
    "scripts": {
        "test": "standard && node test/fixtures/prepare.js && mocha",
        "build": "node nail/build.js"
    },
    "bin": {
        "puml": "index.js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
