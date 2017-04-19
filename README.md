# npmtest-pageres

#### test coverage for  [pageres (v4.4.0)](https://github.com/sindresorhus/pageres#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-pageres.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pageres) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pageres.svg)](https://travis-ci.org/npmtest/node-npmtest-pageres)

#### Capture website screenshots

[![NPM](https://nodei.co/npm/pageres.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pageres)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pageres/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pageres/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pageres/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pageres/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pageres/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pageres/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pageres/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pageres/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pageres/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pageres/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pageres/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pageres/build/test-report.html](https://npmtest.github.io/node-npmtest-pageres/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pageres/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pageres/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pageres/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pageres/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pageres/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pageres/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pageres/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pageres/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sindre Sorhus",
        "url": "sindresorhus.com"
    },
    "babel": {
        "plugins": [
            "transform-async-to-generator",
            "transform-runtime",
            "transform-flow-strip-types",
            "add-module-exports"
        ],
        "presets": [
            "es2015-node4"
        ],
        "sourceMaps": "inline"
    },
    "bugs": {
        "url": "https://github.com/sindresorhus/pageres/issues"
    },
    "dependencies": {
        "array-differ": "^1.0.0",
        "array-uniq": "^1.0.2",
        "babel-runtime": "^6.6.1",
        "easydate": "^2.0.0",
        "filenamify": "^2.0.0",
        "filenamify-url": "^1.0.0",
        "fs-write-stream-atomic": "^1.0.2",
        "get-res": "^3.0.0",
        "lodash.template": "^4.0.1",
        "log-symbols": "^1.0.2",
        "mem": "^1.1.0",
        "mkdirp": "^0.5.0",
        "pify": "^2.3.0",
        "plur": "^2.0.0",
        "protocolify": "^2.0.0",
        "rimraf": "^2.2.8",
        "screenshot-stream": "^4.1.0",
        "unused-filename": "^0.1.0",
        "viewport-list": "^5.0.1"
    },
    "description": "Capture website screenshots",
    "devDependencies": {
        "ava": "*",
        "babel-cli": "^6.7.5",
        "babel-eslint": "^7.1.1",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-transform-async-to-generator": "^6.7.4",
        "babel-plugin-transform-flow-strip-types": "^6.14.0",
        "babel-plugin-transform-runtime": "^6.7.5",
        "babel-preset-es2015-node4": "^2.1.0",
        "cookie": "^0.3.1",
        "coveralls": "^2.11.2",
        "flow-bin": "^0.42.0",
        "get-port": "^3.0.0",
        "get-stream": "^3.0.0",
        "image-size": "^0.5.0",
        "nyc": "^10.0.0",
        "path-exists": "^3.0.0",
        "png-js": "^0.1.1",
        "rfpify": "^1.0.0",
        "sinon": "^2.0.0",
        "xo": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "7ef51f685d64172a422b989d8628755189aa297c",
        "tarball": "https://registry.npmjs.org/pageres/-/pageres-4.4.0.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "files": [
        "dist"
    ],
    "gitHead": "cdd335ae3aa3e725e19c1762abb9715db115c6c8",
    "homepage": "https://github.com/sindresorhus/pageres#readme",
    "keywords": [
        "page",
        "website",
        "site",
        "web",
        "url",
        "resolution",
        "size",
        "screenshot",
        "screenshots",
        "screengrab",
        "screen",
        "snapshot",
        "shot",
        "responsive",
        "gulpfriendly",
        "phantom",
        "phantomjs",
        "image",
        "svg",
        "render",
        "html",
        "headless",
        "capture",
        "pic",
        "picture",
        "png",
        "jpg",
        "jpeg"
    ],
    "license": "MIT",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "kevva"
        },
        {
            "name": "samverschueren"
        },
        {
            "name": "sindresorhus"
        }
    ],
    "name": "pageres",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sindresorhus/pageres.git"
    },
    "scripts": {
        "coveralls": "nyc report --reporter=text-lcov | coveralls",
        "flow": "flow || true",
        "prepublish": "babel lib --out-dir=dist",
        "test": "xo && npm run prepublish && nyc ava"
    },
    "version": "4.4.0",
    "xo": {
        "parser": "babel-eslint",
        "rules": {
            "generator-star-spacing": "off"
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
