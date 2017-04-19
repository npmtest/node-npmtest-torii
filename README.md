# npmtest-torii

#### test coverage for  [torii (v0.8.2)](https://github.com/vestorly/torii#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-torii.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-torii) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-torii.svg)](https://travis-ci.org/npmtest/node-npmtest-torii)

#### A set of clean abstractions for authentication in Ember.js

[![NPM](https://nodei.co/npm/torii.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/torii)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-torii/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-torii/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-torii/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-torii/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-torii/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-torii/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-torii/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-torii/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-torii/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-torii/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-torii/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-torii/build/test-report.html](https://npmtest.github.io/node-npmtest-torii/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-torii/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-torii/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-torii/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-torii/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-torii/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-torii/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-torii/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-torii/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Vestorly"
    },
    "bugs": {
        "url": "https://github.com/vestorly/torii/issues"
    },
    "contributors": [
        {
            "name": "Matt Beale"
        },
        {
            "name": "Cory Forsyth"
        },
        {
            "name": "Vestorly"
        }
    ],
    "dependencies": {
        "broccoli-funnel": "^1.0.1",
        "broccoli-merge-trees": "^1.1.1",
        "broccoli-string-replace": "^0.1.1",
        "ember-cli-babel": "^5.1.3"
    },
    "description": "A set of clean abstractions for authentication in Ember.js",
    "devDependencies": {
        "broccoli-asset-rev": "^2.1.2",
        "connect-redirection": "0.0.1",
        "ember-cli": "1.13.8",
        "ember-cli-app-version": "0.5.0",
        "ember-cli-content-security-policy": "0.4.0",
        "ember-cli-dependency-checker": "^1.0.1",
        "ember-cli-htmlbars": "0.7.9",
        "ember-cli-htmlbars-inline-precompile": "^0.2.0",
        "ember-cli-ic-ajax": "0.2.1",
        "ember-cli-inject-live-reload": "^1.3.1",
        "ember-cli-qunit": "^1.0.0",
        "ember-cli-release": "0.2.3",
        "ember-cli-sri": "^1.0.3",
        "ember-cli-uglify": "^1.2.0",
        "ember-disable-prototype-extensions": "^1.0.0",
        "ember-disable-proxy-controllers": "^1.0.0",
        "ember-export-application-global": "^1.0.3",
        "ember-try": "^0.2.12",
        "grunt": "~0.4.2",
        "grunt-banner": "^0.2.3",
        "grunt-cli": "~0.1.11",
        "grunt-contrib-clean": "~0.6.0",
        "grunt-contrib-concat": "~0.5.0",
        "grunt-contrib-connect": "~0.7.1",
        "grunt-contrib-jshint": "~0.10.0",
        "grunt-contrib-uglify": "~0.6.0",
        "grunt-contrib-watch": "~0.6.1",
        "grunt-contrib-yuidoc": "~0.5.0",
        "grunt-es3-safe-recast": "^0.1.0",
        "grunt-es6-module-transpiler": "~0.6.0",
        "grunt-testem-mincer": "~0.5.18",
        "jshint": "~2.5.6",
        "load-grunt-config": "~0.14.0",
        "load-grunt-tasks": "~1.0.0"
    },
    "directories": {
        "lib": "lib"
    },
    "dist": {
        "shasum": "60688b5ce0bc148dedf764df3c4c41f55da3f866",
        "tarball": "https://registry.npmjs.org/torii/-/torii-0.8.2.tgz"
    },
    "ember-addon": {
        "demoUrl": "http://vestorly.github.io/torii/demo.html",
        "configPath": "tests/dummy/config"
    },
    "files": [
        "index.js",
        "addon/",
        "app/",
        "test-support/",
        "bower.json"
    ],
    "gitHead": "8d3c83b4b4161e04ee8c6765941499d137ed6ed0",
    "homepage": "https://github.com/vestorly/torii#readme",
    "keywords": [
        "authentication",
        "ember.js",
        "ember-addon"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "bantic"
        },
        {
            "name": "mitchlloyd"
        },
        {
            "name": "mixonic"
        }
    ],
    "name": "torii",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/vestorly/torii.git"
    },
    "scripts": {
        "test": "ember try:testall"
    },
    "version": "0.8.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
