# npmdoc-imager.js

#### api documentation for  imager.js (v0.5.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-imager.js.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-imager.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-imager.js.svg)](https://travis-ci.org/npmdoc/node-npmdoc-imager.js)

#### Imager.js is an alternative solution to the issue of how to handle responsive image loading, created by developers at BBC News.

[![NPM](https://nodei.co/npm/imager.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/imager.js)

- [https://npmdoc.github.io/node-npmdoc-imager.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-imager.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-imager.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-imager.js/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-imager.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-imager.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "imager.js",
    "version": "0.5.0",
    "description": "Imager.js is an alternative solution to the issue of how to handle responsive image loading, created by developers at BBC News.",
    "main": "Imager.js",
    "scripts": {
        "test": "npm run test-pre && ./node_modules/karma/bin/karma start",
        "test-pre": "jshint Imager.js",
        "test-watch": "./node_modules/karma/bin/karma start --auto-watch --no-single-run",
        "build": "uglifyjs ./Imager.js -c -m -o ./Imager.min.js --source-map ./Imager.map.js && mv -f Imager.{map,min}.js ./dist"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/BBC-News/Imager.js.git"
    },
    "keywords": [
        "responsive",
        "srcset",
        "images",
        "resize",
        "polyfill",
        "shim",
        "img",
        "PictureFill"
    ],
    "license": "Apache-2.0",
    "devDependencies": {
        "components-jquery": "git://github.com/components/jquery.git#1.10.2",
        "expect.js": "^0.2.0",
        "jshint": "^2.4.3",
        "karma": "^0.12.31",
        "karma-browserstack-launcher": "^0.1.1",
        "karma-chrome-launcher": "^0.1.0",
        "karma-expect": "^1.0.0",
        "karma-firefox-launcher": "^0.1.3",
        "karma-html2js-preprocessor": "^0.1.0",
        "karma-ievms": "^0.0.4",
        "karma-mocha": "^0.1.9",
        "karma-phantomjs-launcher": "^0.1.4",
        "karma-sauce-launcher": "^0.2.10",
        "karma-sinon": "^1.0.3",
        "mocha": "^1.17.1",
        "sinon": "^1.8.1",
        "uglify-js": "^2.4.3"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
