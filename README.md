# npmdoc-purecss

#### api documentation for  [purecss (v0.6.2)](http://purecss.io)  [![npm package](https://img.shields.io/npm/v/npmdoc-purecss.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-purecss) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-purecss.svg)](https://travis-ci.org/npmdoc/node-npmdoc-purecss)

#### Pure is a ridiculously tiny CSS library you can use to start any web project.

[![NPM](https://nodei.co/npm/purecss.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/purecss)

- [https://npmdoc.github.io/node-npmdoc-purecss/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-purecss/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-purecss/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-purecss/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-purecss/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-purecss/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "purecss",
    "version": "0.6.2",
    "repository": {
        "type": "git",
        "url": "git://github.com/yahoo/pure.git"
    },
    "scripts": {
        "pretest": "grunt build",
        "test": "grunt test && tap test/*.js",
        "prepublish": "grunt release"
    },
    "files": "build/",
    "devDependencies": {
        "autoprefixer": "^6.3.1",
        "bower": "^1.3.7",
        "grunt": "^1.0.1",
        "grunt-cli": "^1.2.0",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-compress": "^1.3.0",
        "grunt-contrib-concat": "^1.0.1",
        "grunt-contrib-copy": "^1.0.0",
        "grunt-contrib-csslint": "^2.0.0",
        "grunt-contrib-cssmin": "^1.0.2",
        "grunt-contrib-watch": "^1.0.0",
        "grunt-css-selectors": "^1.1.0",
        "grunt-postcss": "^0.8.0",
        "grunt-pure-grids": "^1.0.0",
        "grunt-stripmq": "0.0.6",
        "tap": "^8.0.1"
    },
    "description": "Pure is a ridiculously tiny CSS library you can use to start any web project.",
    "bugs": {
        "url": "https://github.com/yahoo/pure/issues"
    },
    "homepage": "http://purecss.io",
    "main": "index.js",
    "browser": "build/pure-min.css",
    "keywords": [
        "pure",
        "css",
        "purecss",
        "yahoo"
    ],
    "authors": [
        "ericf <edf@ericf.me>",
        "tilomitra <tilomitra@gmail.com>",
        "msweeney <matt.sweeney@yahoo.com>",
        "jamesalley <manalagi001@yahoo.com>"
    ],
    "license": "BSD"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
