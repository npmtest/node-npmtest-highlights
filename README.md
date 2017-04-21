# npmtest-highlights

#### basic test coverage for  [highlights (v3.0.1)](https://github.com/atom/highlights)  [![npm package](https://img.shields.io/npm/v/npmtest-highlights.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-highlights) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-highlights.svg)](https://travis-ci.org/npmtest/node-npmtest-highlights)

#### Syntax highlighter

[![NPM](https://nodei.co/npm/highlights.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/highlights)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-highlights/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-highlights/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-highlights/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-highlights/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-highlights/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-highlights/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-highlights/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-highlights/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-highlights/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-highlights/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-highlights/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-highlights/build/test-report.html](https://npmtest.github.io/node-npmtest-highlights/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-highlights/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-highlights/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-highlights/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-highlights/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-highlights/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-highlights/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-highlights/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-highlights/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "highlights",
    "version": "3.0.1",
    "description": "Syntax highlighter",
    "main": "lib/highlights.js",
    "scripts": {
        "test": "grunt test",
        "prepublish": "grunt prepublish",
        "pretest": "git submodule update --init --recursive",
        "version": "standard-version"
    },
    "bin": "bin/highlights",
    "repository": {
        "type": "git",
        "url": "https://github.com/atom/highlights"
    },
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/atom/highlights/issues"
    },
    "homepage": "https://github.com/atom/highlights",
    "dependencies": {
        "first-mate": "^7.0.2",
        "first-mate-select-grammar": "^1.0.1",
        "fs-plus": "^3.0.0",
        "once": "^1.3.2",
        "season": "^6.0.0",
        "underscore-plus": "^1.5.1",
        "yargs": "^4.7.1"
    },
    "devDependencies": {
        "grunt": "^1.0.1",
        "grunt-cli": "^1.2.0",
        "grunt-coffeelint": "0.0.16",
        "grunt-contrib-coffee": "^1.0.0",
        "grunt-shell": "^1.3.0",
        "jasmine-focused": "^1.0.4",
        "language-erlang": "^2.0.0",
        "standard-version": "^2.3.1"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
