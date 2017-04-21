# npmtest-negotiator

#### basic test coverage for  [negotiator (v0.6.1)](https://github.com/jshttp/negotiator#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-negotiator.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-negotiator) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-negotiator.svg)](https://travis-ci.org/npmtest/node-npmtest-negotiator)

#### HTTP content negotiation

[![NPM](https://nodei.co/npm/negotiator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/negotiator)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-negotiator/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-negotiator/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-negotiator/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-negotiator/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-negotiator/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-negotiator/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-negotiator/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-negotiator/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-negotiator/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-negotiator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-negotiator/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-negotiator/build/test-report.html](https://npmtest.github.io/node-npmtest-negotiator/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-negotiator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-negotiator/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-negotiator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-negotiator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-negotiator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-negotiator/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-negotiator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-negotiator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/jshttp/negotiator/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        },
        {
            "name": "Federico Romero"
        },
        {
            "name": "Isaac Z. Schlueter",
            "url": "http://blog.izs.me/"
        }
    ],
    "dependencies": {},
    "description": "HTTP content negotiation",
    "devDependencies": {
        "istanbul": "0.4.3",
        "mocha": "~1.21.5"
    },
    "directories": {},
    "dist": {
        "shasum": "2b327184e8992101177b28563fb5e7102acd0ca9",
        "tarball": "https://registry.npmjs.org/negotiator/-/negotiator-0.6.1.tgz"
    },
    "engines": {
        "node": ">= 0.6"
    },
    "files": [
        "lib/",
        "HISTORY.md",
        "LICENSE",
        "index.js",
        "README.md"
    ],
    "gitHead": "751c381c32707f238143cd65d78520e16f4ef9e5",
    "homepage": "https://github.com/jshttp/negotiator#readme",
    "keywords": [
        "http",
        "content negotiation",
        "accept",
        "accept-language",
        "accept-encoding",
        "accept-charset"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        },
        {
            "name": "federomero"
        },
        {
            "name": "jongleberry"
        }
    ],
    "name": "negotiator",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jshttp/negotiator.git"
    },
    "scripts": {
        "test": "mocha --reporter spec --check-leaks --bail test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/"
    },
    "version": "0.6.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
