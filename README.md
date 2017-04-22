# npmtest-generator-electron

#### basic test coverage for  generator-electron (v1.20.0)  [![npm package](https://img.shields.io/npm/v/npmtest-generator-electron.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-generator-electron) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-generator-electron.svg)](https://travis-ci.org/npmtest/node-npmtest-generator-electron)

#### Scaffold out an Electron app boilerplate

[![NPM](https://nodei.co/npm/generator-electron.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generator-electron)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-generator-electron/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-electron/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-generator-electron/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-generator-electron/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-generator-electron/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-generator-electron/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-generator-electron/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-generator-electron/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-generator-electron/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-electron/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-generator-electron/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-generator-electron/build/test-report.html](https://npmtest.github.io/node-npmtest-generator-electron/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-generator-electron/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-generator-electron/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-generator-electron/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generator-electron/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-electron/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-electron/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-generator-electron/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-generator-electron/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "generator-electron",
    "version": "1.20.0",
    "description": "Scaffold out an Electron app boilerplate",
    "license": "MIT",
    "repository": "sindresorhus/generator-electron",
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "scripts": {
        "test": "xo && mocha"
    },
    "files": [
        "app"
    ],
    "keywords": [
        "yeoman-generator",
        "boilerplate",
        "template",
        "scaffold",
        "node",
        "desktop",
        "app",
        "application",
        "electron"
    ],
    "dependencies": {
        "humanize-url": "^1.0.1",
        "normalize-url": "^1.2.0",
        "superb": "^1.1.3",
        "underscore.string": "^3.0.3",
        "yeoman-generator": "^0.22.5"
    },
    "devDependencies": {
        "mocha": "*",
        "xo": "*",
        "yeoman-assert": "^2.0.0",
        "yeoman-test": "^1.1.0"
    },
    "xo": {
        "envs": [
            "node",
            "mocha"
        ],
        "ignores": [
            "app/templates/**"
        ]
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
