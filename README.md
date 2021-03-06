# npmtest-isomorphic-fetch

#### basic test coverage for  [isomorphic-fetch (v2.2.1)](https://github.com/matthew-andrews/isomorphic-fetch/issues)  [![npm package](https://img.shields.io/npm/v/npmtest-isomorphic-fetch.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-isomorphic-fetch) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-isomorphic-fetch.svg)](https://travis-ci.org/npmtest/node-npmtest-isomorphic-fetch)

#### Isomorphic WHATWG Fetch API, for Node & Browserify

[![NPM](https://nodei.co/npm/isomorphic-fetch.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/isomorphic-fetch)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-isomorphic-fetch/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-isomorphic-fetch/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-isomorphic-fetch/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-isomorphic-fetch/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-isomorphic-fetch/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-isomorphic-fetch/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-isomorphic-fetch/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-isomorphic-fetch/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-isomorphic-fetch/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-isomorphic-fetch/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-isomorphic-fetch/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-isomorphic-fetch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-isomorphic-fetch/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-isomorphic-fetch/build/test-report.html](https://npmtest.github.io/node-npmtest-isomorphic-fetch/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-isomorphic-fetch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-isomorphic-fetch/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-isomorphic-fetch/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-isomorphic-fetch/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-isomorphic-fetch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-isomorphic-fetch/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-isomorphic-fetch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-isomorphic-fetch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matt Andrews"
    },
    "browser": "fetch-npm-browserify.js",
    "bugs": {
        "url": "https://github.com/matthew-andrews/isomorphic-fetch/issues"
    },
    "dependencies": {
        "node-fetch": "^1.0.1",
        "whatwg-fetch": ">=0.10.0"
    },
    "description": "Isomorphic WHATWG Fetch API, for Node & Browserify",
    "devDependencies": {
        "chai": "^1.10.0",
        "es6-promise": "^2.0.1",
        "jshint": "^2.5.11",
        "lintspaces-cli": "0.0.4",
        "mocha": "^2.1.0",
        "nock": "^0.56.0",
        "npm-prepublish": "^1.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "611ae1acf14f5e81f729507472819fe9733558a9",
        "tarball": "https://registry.npmjs.org/isomorphic-fetch/-/isomorphic-fetch-2.2.1.tgz"
    },
    "gitHead": "43437dc5b381e391b73522d71cea23fc72675154",
    "homepage": "https://github.com/matthew-andrews/isomorphic-fetch/issues",
    "license": "MIT",
    "main": "fetch-npm-node.js",
    "maintainers": [
        {
            "name": "financial-times"
        },
        {
            "name": "mattandrews"
        }
    ],
    "name": "isomorphic-fetch",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/matthew-andrews/isomorphic-fetch.git"
    },
    "scripts": {
        "files": "find . -name '*.js' ! -path './node_modules/*' ! -path './bower_components/*'",
        "test": "jshint 'npm run -s files' && lintspaces -i js-comments -e .editorconfig 'npm run -s files' && mocha"
    },
    "version": "2.2.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
