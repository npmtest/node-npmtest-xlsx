# test coverage for  [xlsx (v0.9.11)](https://oss.sheetjs.com/js-xlsx/)  [![npm package](https://img.shields.io/npm/v/npmtest-xlsx.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-xlsx) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-xlsx.svg)](https://travis-ci.org/npmtest/node-npmtest-xlsx)
#### Excel (XLSB/XLSX/XLSM/XLS/XML) and ODS (ODS/FODS/UOS) spreadsheet parser and writer

[![NPM](https://nodei.co/npm/xlsx.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/xlsx)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-xlsx/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-xlsx/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-xlsx/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-xlsx/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-xlsx/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-xlsx/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-xlsx/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-xlsx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-xlsx/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-xlsx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-xlsx/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-xlsx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-xlsx/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-xlsx/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-xlsx/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "sheetjs"
    },
    "bin": {
        "xlsx": "./bin/xlsx.njs"
    },
    "browser": {
        "node": false,
        "crypto": false,
        "stream": false,
        "fs": false
    },
    "bugs": {
        "url": "https://github.com/SheetJS/js-xlsx/issues"
    },
    "config": {
        "blanket": {
            "pattern": "xlsx.js"
        }
    },
    "dependencies": {
        "adler-32": "~1.0.0",
        "cfb": "~0.11.1",
        "codepage": "~1.8.0",
        "commander": "~2.9.0",
        "crc-32": "~1.0.0",
        "exit-on-epipe": "~1.0.0",
        "ssf": "~0.9.0"
    },
    "description": "Excel (XLSB/XLSX/XLSM/XLS/XML) and ODS (ODS/FODS/UOS) spreadsheet parser and writer",
    "devDependencies": {
        "mocha": "",
        "uglify-js": "",
        "xlsjs": ""
    },
    "directories": {},
    "dist": {
        "shasum": "cafd6b052acdedd85cfc4798fb1b8aa86adf1e32",
        "tarball": "https://registry.npmjs.org/xlsx/-/xlsx-0.9.11.tgz"
    },
    "engines": {
        "node": ">=0.8"
    },
    "gitHead": "f51feb375a0072ae15461955f37d0047fdf521c8",
    "homepage": "https://oss.sheetjs.com/js-xlsx/",
    "keywords": [
        "excel",
        "xls",
        "xlsx",
        "xlsb",
        "xlsm",
        "ods",
        "office",
        "spreadsheet"
    ],
    "license": "Apache-2.0",
    "main": "./xlsx",
    "maintainers": [
        {
            "name": "sheetjs"
        }
    ],
    "name": "xlsx",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/SheetJS/js-xlsx.git"
    },
    "scripts": {
        "pretest": "git submodule init && git submodule update",
        "test": "make travis"
    },
    "version": "0.9.11"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
