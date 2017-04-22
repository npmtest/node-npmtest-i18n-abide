# npmtest-i18n-abide

#### basic test coverage for  [i18n-abide (v0.0.25)](https://github.com/mozilla/i18n-abide)  [![npm package](https://img.shields.io/npm/v/npmtest-i18n-abide.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-i18n-abide) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-i18n-abide.svg)](https://travis-ci.org/npmtest/node-npmtest-i18n-abide)

#### Express/connect module for Node i18n and l10n support

[![NPM](https://nodei.co/npm/i18n-abide.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/i18n-abide)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-i18n-abide/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-i18n-abide/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-i18n-abide/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-i18n-abide/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-i18n-abide/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-i18n-abide/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-i18n-abide/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-i18n-abide/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-i18n-abide/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-i18n-abide/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-i18n-abide/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-i18n-abide/build/test-report.html](https://npmtest.github.io/node-npmtest-i18n-abide/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-i18n-abide/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-i18n-abide/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-i18n-abide/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-i18n-abide/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-i18n-abide/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-i18n-abide/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-i18n-abide/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-i18n-abide/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Austin King",
        "url": "http://ozten.com"
    },
    "bin": {
        "check-l10n-config": "bin/check-l10n-config.js",
        "check-po": "bin/check-po.sh",
        "compile-json": "bin/compile-json",
        "compile-mo": "bin/compile-mo.sh",
        "every-locale.js": "bin/every-locale.js",
        "extract-pot": "bin/extract-pot",
        "merge-po": "bin/merge-po.sh",
        "po2json.js": "bin/po2json.js"
    },
    "bugs": {
        "url": "http://github.com/mozilla/i18n-abide/issues"
    },
    "dependencies": {
        "async": "0.9.0",
        "gobbledygook": "https://github.com/lloyd/gobbledygook/tarball/354042684056e57ca77f036989e907707a36cff2",
        "jsxgettext": "0.7.0",
        "optimist": "0.6.1",
        "plist": "1.1.0"
    },
    "description": "Express/connect module for Node i18n and l10n support",
    "devDependencies": {
        "vows": "0.5.13"
    },
    "directories": {},
    "dist": {
        "shasum": "4a582e2c2e7b1987ca40c51f4ed9d2020d118e4e",
        "tarball": "https://registry.npmjs.org/i18n-abide/-/i18n-abide-0.0.25.tgz"
    },
    "engines": {
        "node": ">= 0.6.2"
    },
    "gitHead": "95ee7906a3c04eb73a4e657733aaaa9760a3edf3",
    "homepage": "https://github.com/mozilla/i18n-abide",
    "keywords": [
        "express",
        "connect",
        "l10n",
        "i18n",
        "gettext"
    ],
    "licenses": [
        {
            "type": "MPL 2.0",
            "url": "http://www.mozilla.org/MPL/2.0/"
        }
    ],
    "main": "lib/i18n.js",
    "maintainers": [
        {
            "name": "ozten"
        },
        {
            "name": "fmarier"
        },
        {
            "name": "zaach"
        }
    ],
    "name": "i18n-abide",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/mozilla/i18n-abide.git"
    },
    "scripts": {
        "test": "NODE_PATH=lib node_modules/.bin/vows tests/*-tests.js --spec"
    },
    "version": "0.0.25"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
