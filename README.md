# npmtest-ursa

#### basic test coverage for  [ursa (v0.9.4)](https://github.com/quartzjer/ursa)  [![npm package](https://img.shields.io/npm/v/npmtest-ursa.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ursa) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ursa.svg)](https://travis-ci.org/npmtest/node-npmtest-ursa)

#### RSA public/private key OpenSSL bindings for node and io.js

[![NPM](https://nodei.co/npm/ursa.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ursa)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ursa/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ursa/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ursa/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ursa/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ursa/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-ursa/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-ursa/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ursa/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ursa/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ursa/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ursa/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ursa/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ursa/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ursa/build/test-report.html](https://npmtest.github.io/node-npmtest-ursa/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ursa/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ursa/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ursa/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ursa/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ursa/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ursa/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ursa/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ursa/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dan Bornstein",
        "url": "http://www.milk.com/"
    },
    "bugs": {
        "url": "https://github.com/quartzjer/ursa/issues"
    },
    "dependencies": {
        "bindings": "^1.2.1",
        "nan": "^2.3.3"
    },
    "description": "RSA public/private key OpenSSL bindings for node and io.js",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "0a2abfb7dc4267f733b0f8f2fc7f2c895d40a413",
        "tarball": "https://registry.npmjs.org/ursa/-/ursa-0.9.4.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "216ad542b6722c560d24555b4ea0a76051654e6c",
    "gypfile": true,
    "homepage": "https://github.com/quartzjer/ursa",
    "keywords": [
        "crypto",
        "key",
        "openssl",
        "private",
        "public",
        "rsa",
        "sign",
        "signature",
        "verify",
        "verification",
        "hash",
        "digest"
    ],
    "license": "Apache-2.0",
    "main": "lib/ursa.js",
    "maintainers": [
        {
            "name": "danfuzz"
        },
        {
            "name": "dpup"
        },
        {
            "name": "nicks"
        },
        {
            "name": "azulus"
        },
        {
            "name": "quartzjer"
        }
    ],
    "name": "ursa",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/quartzjer/ursa.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "node test/test.js"
    },
    "version": "0.9.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
