# api documentation for  [csurf (v1.9.0)](https://github.com/expressjs/csurf)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-csurf.svg)](https://travis-ci.org/npmdoc/node-npmdoc-csurf)
#### CSRF token middleware

[![NPM](https://nodei.co/npm/csurf.png?downloads=true)](https://www.npmjs.com/package/csurf)

[![apidoc](https://npmdoc.github.io/node-npmdoc-csurf/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-csurf_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-csurf/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-csurf/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Ong",
        "email": "me@jongleberry.com",
        "url": "http://jongleberry.com"
    },
    "bugs": {
        "url": "https://github.com/expressjs/csurf/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson",
            "email": "doug@somethingdoug.com"
        }
    ],
    "dependencies": {
        "cookie": "0.3.1",
        "cookie-signature": "1.0.6",
        "csrf": "~3.0.3",
        "http-errors": "~1.5.0"
    },
    "description": "CSRF token middleware",
    "devDependencies": {
        "body-parser": "1.15.1",
        "connect": "3.4.1",
        "cookie-parser": "1.4.3",
        "cookie-session": "~1.1.0",
        "eslint": "2.10.2",
        "eslint-config-standard": "5.3.1",
        "eslint-plugin-promise": "1.3.1",
        "eslint-plugin-standard": "1.3.2",
        "istanbul": "0.4.3",
        "mocha": "2.5.3",
        "supertest": "1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "49d2c6925ffcec7b7de559597c153fa533364133",
        "tarball": "https://registry.npmjs.org/csurf/-/csurf-1.9.0.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "files": [
        "HISTORY.md",
        "LICENSE",
        "index.js"
    ],
    "gitHead": "6359a0298e1e3e937abb96c21958b2a4419d0301",
    "homepage": "https://github.com/expressjs/csurf",
    "keywords": [
        "csrf",
        "tokens",
        "middleware",
        "express"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "defunctzombie",
            "email": "shtylman@gmail.com"
        },
        {
            "name": "dougwilson",
            "email": "doug@somethingdoug.com"
        },
        {
            "name": "fishrock123",
            "email": "fishrock123@rocketmail.com"
        },
        {
            "name": "jongleberry",
            "email": "jonathanrichardong@gmail.com"
        },
        {
            "name": "mscdex",
            "email": "mscdex@mscdex.net"
        },
        {
            "name": "tjholowaychuk",
            "email": "tj@vision-media.ca"
        }
    ],
    "name": "csurf",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/expressjs/csurf.git"
    },
    "scripts": {
        "lint": "eslint **/*.js",
        "test": "mocha --check-leaks --reporter spec --bail test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --check-leaks --reporter dot test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --check-leaks --reporter spec test/"
    },
    "version": "1.9.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module csurf](#apidoc.module.csurf)



# <a name="apidoc.module.csurf"></a>[module csurf](#apidoc.module.csurf)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
