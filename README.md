# npmtest-auto-sni

#### basic test coverage for  [auto-sni (v2.1.1)](https://github.com/DylanPiercey/auto-sni)  [![npm package](https://img.shields.io/npm/v/npmtest-auto-sni.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-auto-sni) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-auto-sni.svg)](https://travis-ci.org/npmtest/node-npmtest-auto-sni)

#### Automatically generate tls credentials using letsencrypt.

[![NPM](https://nodei.co/npm/auto-sni.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/auto-sni)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-auto-sni/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-auto-sni/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-auto-sni/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-auto-sni/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-auto-sni/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-auto-sni/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-auto-sni/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-auto-sni/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-auto-sni/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-auto-sni/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-auto-sni/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-auto-sni/build/test-report.html](https://npmtest.github.io/node-npmtest-auto-sni/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-auto-sni/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-auto-sni/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-auto-sni/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-auto-sni/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-auto-sni/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-auto-sni/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-auto-sni/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-auto-sni/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dylan Piercey"
    },
    "bugs": {
        "url": "https://github.com/DylanPiercey/auto-sni/issues"
    },
    "dependencies": {
        "greenlock-express": "^2.0.9"
    },
    "description": "Automatically generate tls credentials using letsencrypt.",
    "devDependencies": {
        "hostile": "^1.3.0",
        "ngrok": "^2.2.6",
        "object-assign": "^4.1.1",
        "snazzy": "^7.0.0",
        "standard": "^10.0.1",
        "supertest": "^3.0.0",
        "tap-spec": "^4.1.1",
        "tape": "^4.6.3"
    },
    "directories": {},
    "dist": {
        "shasum": "e594a1ee1b224d594da4fe3bd55aec2e4b4c4148",
        "tarball": "https://registry.npmjs.org/auto-sni/-/auto-sni-2.1.1.tgz"
    },
    "gitHead": "df48500ce18abf1375c4e390cba9d2a4d5eea550",
    "homepage": "https://github.com/DylanPiercey/auto-sni",
    "keywords": [
        "auto",
        "auto-sni",
        "http",
        "https",
        "lets-encrypt",
        "letsencrypt",
        "letsencrypt-auto",
        "renew",
        "secure",
        "sni",
        "ssl",
        "tls",
        "web"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "dylanpiercey"
        }
    ],
    "name": "auto-sni",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/DylanPiercey/auto-sni.git"
    },
    "scripts": {
        "test": "standard --verbose | snazzy && sudo tape ./test/**/*.test.js | tap-spec"
    },
    "version": "2.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
