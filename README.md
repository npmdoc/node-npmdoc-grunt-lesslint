# npmdoc-grunt-lesslint

#### api documentation for  [grunt-lesslint (v4.0.0)](http://jgable.github.io/grunt-lesslint)  [![npm package](https://img.shields.io/npm/v/npmdoc-grunt-lesslint.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-grunt-lesslint) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-grunt-lesslint.svg)](https://travis-ci.org/npmdoc/node-npmdoc-grunt-lesslint)

#### Grunt task for validating LESS files with CSS Lint

[![NPM](https://nodei.co/npm/grunt-lesslint.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-lesslint)

- [https://npmdoc.github.io/node-npmdoc-grunt-lesslint/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-lesslint/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-lesslint/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-lesslint/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-grunt-lesslint/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-grunt-lesslint/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jacob Gable"
    },
    "bugs": {
        "url": "https://github.com/jgable/grunt-lesslint/issues"
    },
    "contributors": [
        {
            "name": "David Pärsson"
        }
    ],
    "dependencies": {
        "async": "^1.5.2",
        "cache-swap": "~0.2.3",
        "chalk": "^1.1.3",
        "csslint": "^1.0.5",
        "less": "~2.7.1",
        "lodash": "^4.12.0",
        "source-map": "~0.5.6",
        "strip-json-comments": "^2.0.1",
        "strip-path": "~1.0.0"
    },
    "description": "Grunt task for validating LESS files with CSS Lint",
    "devDependencies": {
        "grunt": "~0.4.5",
        "grunt-cli": "~0.1.13",
        "grunt-coffeelint": "~0.0.8",
        "grunt-contrib-coffee": "~1.0.0",
        "grunt-shell": "^1.3.0",
        "jasmine-focused": "~1.0.4",
        "rimraf": "^2.5.2",
        "tmp": "~0.0.23",
        "xml2js": "~0.4.1"
    },
    "directories": {},
    "dist": {
        "shasum": "f90f3b74acfcf6aab6e22f72f4d5873b06c9f6f8",
        "tarball": "https://registry.npmjs.org/grunt-lesslint/-/grunt-lesslint-4.0.0.tgz"
    },
    "gitHead": "873285303e59ab200efe28514d4ad7f59d37ffbf",
    "homepage": "http://jgable.github.io/grunt-lesslint",
    "keywords": [
        "css",
        "grunt",
        "gruntplugin",
        "less",
        "lint"
    ],
    "license": "MIT",
    "main": "tasks/less-lint-task",
    "maintainers": [
        {
            "name": "atom"
        },
        {
            "name": "david.parsson"
        },
        {
            "name": "jgable"
        },
        {
            "name": "kevinsawicki"
        }
    ],
    "name": "grunt-lesslint",
    "optionalDependencies": {},
    "peerDependencies": {
        "grunt": ">=0.4.5"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jgable/grunt-lesslint.git"
    },
    "scripts": {
        "prepublish": "grunt clean lint coffee",
        "test": "grunt test"
    },
    "version": "4.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
