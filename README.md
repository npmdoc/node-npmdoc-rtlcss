# npmdoc-rtlcss

#### basic api documentation for  [rtlcss (v2.1.2)](http://rtlcss.com/)  [![npm package](https://img.shields.io/npm/v/npmdoc-rtlcss.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-rtlcss) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-rtlcss.svg)](https://travis-ci.org/npmdoc/node-npmdoc-rtlcss)

#### Framework for transforming cascading style sheets (CSS) from left-to-right (LTR) to right-to-left (RTL)

[![NPM](https://nodei.co/npm/rtlcss.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rtlcss)

- [https://npmdoc.github.io/node-npmdoc-rtlcss/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rtlcss/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rtlcss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rtlcss/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-rtlcss/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-rtlcss/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mohammad Younes"
    },
    "bin": {
        "rtlcss": "./bin/rtlcss.js"
    },
    "bugs": {
        "url": "https://github.com/MohammadYounes/rtlcss/issues?state=open"
    },
    "dependencies": {
        "chalk": "^1.0.0",
        "findup": "^0.1.5",
        "mkdirp": "^0.5.1",
        "postcss": "^5.0.0",
        "strip-json-comments": "^2.0.0"
    },
    "description": "Framework for transforming cascading style sheets (CSS) from left-to-right (LTR) to right-to-left (RTL)",
    "devDependencies": {
        "mocha": "^2.0.0",
        "standard": "^6.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "a5626edc9e7f6017f2d8df30c8bf622bd193a8fc",
        "tarball": "https://registry.npmjs.org/rtlcss/-/rtlcss-2.1.2.tgz"
    },
    "gitHead": "5894fcfb864aabe2b5671a3df9ad195b84df97aa",
    "homepage": "http://rtlcss.com/",
    "keywords": [
        "rtl",
        "css",
        "ltr",
        "rtlcss",
        "framework",
        "style",
        "mirror",
        "flip",
        "convert",
        "transform"
    ],
    "license": "MIT",
    "main": "./lib/rtlcss.js",
    "maintainers": [
        {
            "name": "myounes"
        }
    ],
    "name": "rtlcss",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/MohammadYounes/rtlcss.git"
    },
    "scripts": {
        "lint": "standard && node ./lib/rtlcss.js",
        "test": "npm run lint && mocha -R spec"
    },
    "version": "2.1.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
