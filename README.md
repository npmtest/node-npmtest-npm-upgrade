# npmtest-npm-upgrade

#### basic test coverage for  [npm-upgrade (v1.0.2)](https://github.com/th0r/npm-upgrade)  [![npm package](https://img.shields.io/npm/v/npmtest-npm-upgrade.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-npm-upgrade) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-npm-upgrade.svg)](https://travis-ci.org/npmtest/node-npmtest-npm-upgrade)

#### Interactive CLI utility to easily update outdated NPM dependencies

[![NPM](https://nodei.co/npm/npm-upgrade.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npm-upgrade)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-npm-upgrade/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-upgrade/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-npm-upgrade/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-npm-upgrade/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-npm-upgrade/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-npm-upgrade/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-npm-upgrade/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-npm-upgrade/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-npm-upgrade/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm-upgrade/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-npm-upgrade/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-npm-upgrade/build/test-report.html](https://npmtest.github.io/node-npmtest-npm-upgrade/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-npm-upgrade/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-npm-upgrade/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-npm-upgrade/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npm-upgrade/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm-upgrade/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm-upgrade/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-npm-upgrade/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-npm-upgrade/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Yuriy Grunin"
    },
    "bin": {
        "npm-upgrade": "./lib/bin/cli.js"
    },
    "bugs": {
        "url": "https://github.com/th0r/npm-upgrade/issues"
    },
    "changelog": "https://github.com/th0r/npm-upgrade/blob/master/CHANGELOG.md",
    "dependencies": {
        "babel-runtime": "6.23.0",
        "bluebird": "3.5.0",
        "chalk": "1.1.3",
        "cli-table": "0.3.1",
        "del": "2.2.2",
        "got": "6.7.1",
        "inquirer": "3.0.6",
        "lodash": "4.17.4",
        "npm": "^3.10.6",
        "npm-check-updates": "2.10.3",
        "opener": "1.4.3",
        "semver": "5.3.0",
        "yargs": "7.0.2"
    },
    "description": "Interactive CLI utility to easily update outdated NPM dependencies",
    "devDependencies": {
        "babel-core": "6.24.0",
        "babel-eslint": "7.1.1",
        "babel-plugin-transform-runtime": "6.23.0",
        "babel-preset-env": "1.2.2",
        "babel-preset-stage-2": "6.22.0",
        "bun": "0.0.11",
        "eslint": "3.18.0",
        "eslint-plugin-babel": "4.1.1",
        "gulp": "3.9.1",
        "gulp-babel": "6.1.2",
        "gulp-plumber": "1.1.0",
        "gulp-util": "3.0.8",
        "gulp-watch": "4.3.11"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "762700480845d214ff7f6f4def6976afe17c562d",
        "tarball": "https://registry.npmjs.org/npm-upgrade/-/npm-upgrade-1.0.2.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "lib",
        "src",
        "db"
    ],
    "gitHead": "f4f1f598e9e26ccbc514fa3efe6b285b24d788f6",
    "homepage": "https://github.com/th0r/npm-upgrade",
    "keywords": [
        "npm",
        "update",
        "outdated",
        "dependencies",
        "cli",
        "interactive",
        "automatic",
        "changelog",
        "ignore"
    ],
    "license": "MIT",
    "main": "./lib/bin/cli.js",
    "maintainers": [
        {
            "name": "th0r"
        }
    ],
    "name": "npm-upgrade",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/th0r/npm-upgrade.git"
    },
    "scripts": {
        "prepublish": "gulp build"
    },
    "version": "1.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
