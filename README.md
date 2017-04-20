# npmtest-raccoon

#### basic test coverage for  raccoon (v0.2.8)  [![npm package](https://img.shields.io/npm/v/npmtest-raccoon.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-raccoon) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-raccoon.svg)](https://travis-ci.org/npmtest/node-npmtest-raccoon)

#### A Collaborative Filtering Recommendation Engine for Node.js utilizing Redis

[![NPM](https://nodei.co/npm/raccoon.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/raccoon)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-raccoon/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-raccoon/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-raccoon/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-raccoon/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-raccoon/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-raccoon/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-raccoon/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-raccoon/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-raccoon/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-raccoon/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-raccoon/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-raccoon/build/test-report.html](https://npmtest.github.io/node-npmtest-raccoon/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-raccoon/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-raccoon/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-raccoon/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-raccoon/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-raccoon/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-raccoon/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-raccoon/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-raccoon/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "raccoon",
    "author": "Guy Morita",
    "description": "A Collaborative Filtering Recommendation Engine for Node.js utilizing Redis",
    "version": "0.2.8",
    "repository": {
        "type": "git",
        "url": "https://github.com/guymorita/recommendationRaccoon.git"
    },
    "dependencies": {
        "async": "~2.1.x",
        "bluebird": "~3.4.x",
        "redis": "~2.6.x",
        "underscore": "~1.8.x"
    },
    "main": "./index.js",
    "engines": {
        "node": ">= 6.0.0"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/guymorita/recommendationRaccoon/LICENSE"
        }
    ],
    "keywords": [
        "recommend",
        "recommended",
        "recommendation",
        "engine",
        "collaborative",
        "filtering",
        "middleware",
        "redis"
    ],
    "license": "MIT",
    "readmeFilename": "README.md",
    "bugs": {
        "url": "https://github.com/guymorita/recommendationRaccoon/issues"
    },
    "devDependencies": {
        "chai": "~3.5.0",
        "grunt": "^1.0.1",
        "grunt-contrib-jshint": "^1.1.0",
        "grunt-contrib-watch": "^1.0.0",
        "grunt-mocha-cov": "^0.4.0",
        "mocha": "~3.2.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
