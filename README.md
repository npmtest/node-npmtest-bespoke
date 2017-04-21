# npmtest-bespoke

#### basic test coverage for  bespoke (v1.1.0)  [![npm package](https://img.shields.io/npm/v/npmtest-bespoke.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-bespoke) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-bespoke.svg)](https://travis-ci.org/npmtest/node-npmtest-bespoke)

#### DIY Presentation Micro-Framework

[![NPM](https://nodei.co/npm/bespoke.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/bespoke)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-bespoke/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-bespoke/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-bespoke/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-bespoke/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-bespoke/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-bespoke/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-bespoke/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-bespoke/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-bespoke/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-bespoke/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-bespoke/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-bespoke/build/test-report.html](https://npmtest.github.io/node-npmtest-bespoke/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-bespoke/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-bespoke/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-bespoke/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-bespoke/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-bespoke/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-bespoke/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-bespoke/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-bespoke/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "bespoke",
    "title": "Bespoke.js",
    "version": "1.1.0",
    "description": "DIY Presentation Micro-Framework",
    "author": {
        "name": "Mark Dalgleish",
        "url": "http://markdalgleish.com"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "scripts": {
        "test": "gulp",
        "coveralls": "gulp coveralls"
    },
    "main": "./lib/bespoke.js",
    "repository": {
        "type": "git",
        "url": "git://github.com/markdalgleish/bespoke.js.git"
    },
    "devDependencies": {
        "browserify": "~4.1.5",
        "function-bind": "~0.1.0",
        "gulp": "^3.8.0",
        "gulp-clean": "~0.2.4",
        "gulp-coveralls": "~0.1.0",
        "gulp-gzip": "0.0.8",
        "gulp-header": "~1.0.2",
        "gulp-jshint": "~1.3.4",
        "gulp-karma": "0.0.2",
        "gulp-micro": "~0.1.2",
        "gulp-rename": "^1.2.0",
        "gulp-uglify": "~0.3.0",
        "istanbul": "^0.2.11",
        "jshint-stylish": "~0.1.5",
        "karma": "~0.10.9",
        "karma-browserify": "~0.2.1",
        "karma-coverage": "~0.1.5",
        "karma-jasmine": "~0.1.5",
        "karma-phantomjs-launcher": "~0.1.4",
        "karma-script-launcher": "~0.1.0",
        "lodash": "~2.4.1",
        "requirejs": "~2.1.10",
        "vinyl-map": "^1.0.1",
        "vinyl-source-stream": "~0.1.1",
        "vinyl-buffer": "0.0.0",
        "gulp-util": "^2.2.16"
    },
    "licenses": [
        {
            "type": "MIT",
            "url": "http://mit-license.org/markdalgleish"
        }
    ],
    "keywords": [
        "presentation",
        "html5",
        "keynote",
        "powerpoint"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
