# npmdoc-elliptic

#### basic api documentation for  [elliptic (v6.4.0)](https://github.com/indutny/elliptic)  [![npm package](https://img.shields.io/npm/v/npmdoc-elliptic.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-elliptic) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-elliptic.svg)](https://travis-ci.org/npmdoc/node-npmdoc-elliptic)

#### EC cryptography

[![NPM](https://nodei.co/npm/elliptic.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/elliptic)

- [https://npmdoc.github.io/node-npmdoc-elliptic/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-elliptic/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-elliptic/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-elliptic/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-elliptic/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-elliptic/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Fedor Indutny"
    },
    "bugs": {
        "url": "https://github.com/indutny/elliptic/issues"
    },
    "dependencies": {
        "bn.js": "^4.4.0",
        "brorand": "^1.0.1",
        "hash.js": "^1.0.0",
        "hmac-drbg": "^1.0.0",
        "inherits": "^2.0.1",
        "minimalistic-assert": "^1.0.0",
        "minimalistic-crypto-utils": "^1.0.0"
    },
    "description": "EC cryptography",
    "devDependencies": {
        "brfs": "^1.4.3",
        "coveralls": "^2.11.3",
        "grunt": "^0.4.5",
        "grunt-browserify": "^5.0.0",
        "grunt-cli": "^1.2.0",
        "grunt-contrib-connect": "^1.0.0",
        "grunt-contrib-copy": "^1.0.0",
        "grunt-contrib-uglify": "^1.0.1",
        "grunt-mocha-istanbul": "^3.0.1",
        "grunt-saucelabs": "^8.6.2",
        "istanbul": "^0.4.2",
        "jscs": "^2.9.0",
        "jshint": "^2.6.0",
        "mocha": "^2.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "cac9af8762c85836187003c8dfe193e5e2eae5df",
        "tarball": "https://registry.npmjs.org/elliptic/-/elliptic-6.4.0.tgz"
    },
    "files": [
        "lib"
    ],
    "gitHead": "6b0d2b76caae91471649c8e21f0b1d3ba0f96090",
    "homepage": "https://github.com/indutny/elliptic",
    "keywords": [
        "EC",
        "Elliptic",
        "curve",
        "Cryptography"
    ],
    "license": "MIT",
    "main": "lib/elliptic.js",
    "maintainers": [
        {
            "name": "indutny"
        }
    ],
    "name": "elliptic",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/indutny/elliptic.git"
    },
    "scripts": {
        "jscs": "jscs benchmarks/*.js lib/*.js lib/**/*.js lib/**/**/*.js test/index.js",
        "jshint": "jscs benchmarks/*.js lib/*.js lib/**/*.js lib/**/**/*.js test/index.js",
        "lint": "npm run jscs && npm run jshint",
        "test": "npm run lint && npm run unit",
        "unit": "istanbul test _mocha --reporter=spec test/index.js",
        "version": "grunt dist && git add dist/"
    },
    "version": "6.4.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
