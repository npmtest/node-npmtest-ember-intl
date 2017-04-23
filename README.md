# npmtest-ember-intl

#### basic test coverage for  [ember-intl (v2.27.0)](https://github.com/ember-intl/ember-intl)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-intl.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-intl) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-intl.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-intl)

#### Ember toolbox for internationalization.

[![NPM](https://nodei.co/npm/ember-intl.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-intl)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-intl/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-intl/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-intl/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-intl/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-intl/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-intl/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-intl/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-intl/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-intl/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-intl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-intl/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-intl/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-intl/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-intl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-intl/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-intl/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-intl/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-intl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-intl/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-intl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-intl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "jason.mitchell.w@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/ember-intl/ember-intl/issues"
    },
    "dependencies": {
        "broccoli-caching-writer": "^3.0.3",
        "broccoli-cldr-data": "^1.0.0",
        "broccoli-funnel": "^1.0.1",
        "broccoli-merge-trees": "^2.0.0",
        "broccoli-source": "^1.1.0",
        "broccoli-stew": "^1.2.0",
        "chalk": "^1.0.0",
        "cldr-core": "28.0.0",
        "ember-assign-polyfill": "^2.0.1",
        "ember-cli-babel": "^5.1.7",
        "ember-cli-import-polyfill": "^0.2.0",
        "ember-getowner-polyfill": "1.2.2",
        "ember-intl-format-cache": "^2.4.0",
        "ember-intl-messageformat": "^2.4.0",
        "ember-intl-relativeformat": "^2.4.0",
        "exists-sync": "0.0.4",
        "extend": "^3.0.0",
        "has-unicode": "^2.0.1",
        "intl": "1.0.1",
        "intl-messageformat-parser": "^1.2.0",
        "js-yaml": "^3.3.1",
        "json-stable-stringify": "^1.0.0",
        "locale-emoji": "^0.2.0",
        "mkdirp": "^0.5.0",
        "silent-error": "^1.0.0",
        "walk-sync": "^0.3.1"
    },
    "description": "Ember toolbox for internationalization.",
    "devDependencies": {
        "broccoli-asset-rev": "^2.4.5",
        "chai": "^3.5.0",
        "dependency-check": "^2.5.1",
        "ember-cli": "^2.10.0",
        "ember-cli-app-version": "^3.0.0",
        "ember-cli-dependency-checker": "^1.3.0",
        "ember-cli-eslint": "3.0.3",
        "ember-cli-htmlbars": "^1.0.10",
        "ember-cli-htmlbars-inline-precompile": "^0.3.3",
        "ember-cli-inject-live-reload": "^1.4.1",
        "ember-cli-qunit": "3.1.2",
        "ember-cli-release": "^0.2.9",
        "ember-cli-test-loader": "^2.0.0",
        "ember-cli-uglify": "^1.2.0",
        "ember-code-snippet": "^1.2.0",
        "ember-disable-prototype-extensions": "^1.1.0",
        "ember-export-application-global": "^2.0.0",
        "ember-load-initializers": "^1.0.0",
        "ember-resolver": "^4.1.0",
        "ember-string-ishtmlsafe-polyfill": "1.1.0",
        "eslint": "^3.13.1",
        "eslint-plugin-prettier": "^2.0.1",
        "fs-extra": "^2.0.0",
        "loader.js": "^4.2.3",
        "mocha": "^3.2.0",
        "prettier": "^0.22.0"
    },
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "dist": {
        "shasum": "7d0395559db0b4d849b16e05ef839293fa41adea",
        "tarball": "https://registry.npmjs.org/ember-intl/-/ember-intl-2.27.0.tgz"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config",
        "demoURL": "https://ember-intl.github.io/"
    },
    "engines": {
        "node": ">= 4.0.0"
    },
    "gitHead": "06cd7136eba49421800a82e8aebf496a639fc978",
    "greenkeeper": {
        "ignore": [
            "intl",
            "cldr-core"
        ]
    },
    "homepage": "https://github.com/ember-intl/ember-intl",
    "keywords": [
        "ember-addon",
        "i18n",
        "ember-intl",
        "ember-i18n",
        "ember",
        "internationalization"
    ],
    "license": "BSD-3-Clause",
    "maintainers": [
        {
            "name": "caridy"
        },
        {
            "name": "ericf"
        },
        {
            "name": "jasonmit"
        },
        {
            "name": "stefanpenner"
        },
        {
            "name": "turbo87"
        }
    ],
    "name": "ember-intl",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/ember-intl/ember-intl.git"
    },
    "scripts": {
        "build": "ember build",
        "prepublish": "node ./node_modules/dependency-check/cli.js ./package.json",
        "prettier": "prettier --single-quote --print-width 120 --write \"{blueprints,config,lib,app,addon,tests,tests-node}/**/*.js\"",
        "start": "ember server",
        "test": "npm run tests-node && ember test",
        "testall": "npm run tests-node && ember try:testall",
        "tests-node": "./node_modules/mocha/bin/mocha tests-node/**/*.*"
    },
    "version": "2.27.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
