# npmdoc-gulp-wrap

#### api documentation for  [gulp-wrap (v0.13.0)](https://github.com/adamayres/gulp-wrap#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-wrap.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-wrap) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-wrap.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-wrap)

#### A gulp plugin to wrap the stream contents with a template.

[![NPM](https://nodei.co/npm/gulp-wrap.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-wrap)

- [https://npmdoc.github.io/node-npmdoc-gulp-wrap/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-wrap/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-wrap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-wrap/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-wrap/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-wrap/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Adam Ayres",
        "url": "https://github.com/adamayres"
    },
    "bugs": {
        "url": "https://github.com/adamayres/gulp-wrap/issues"
    },
    "contributors": [
        {
            "name": "Shinnosuke Watanabe",
            "url": "https://github.com/shinnn"
        }
    ],
    "dependencies": {
        "consolidate": "^0.14.1",
        "es6-promise": "^3.1.2",
        "fs-readfile-promise": "^2.0.1",
        "gulp-util": "^3.0.3",
        "js-yaml": "^3.2.6",
        "lodash": "^4.11.1",
        "node.extend": "^1.1.2",
        "through2": "^2.0.1",
        "tryit": "^1.0.1",
        "vinyl-bufferstream": "^1.0.1"
    },
    "description": "A gulp plugin to wrap the stream contents with a template.",
    "devDependencies": {
        "eslint": "^2.9.0",
        "expect.js": "^0.3.1",
        "istanbul": "^0.4.3",
        "istanbul-coveralls": "^1.0.1",
        "jscs": "^3.0.3",
        "mocha": "^2.1.0",
        "simple-bufferstream": "1.0.0",
        "vinyl": "^1.1.1"
    },
    "directories": {},
    "dist": {
        "shasum": "90fb0b4a27a266433832ff7c6122db5c1ee894c6",
        "tarball": "https://registry.npmjs.org/gulp-wrap/-/gulp-wrap-0.13.0.tgz"
    },
    "engines": {
        "node": ">=0.10",
        "npm": ">=1.4.3"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "11cd463ddcd19becb868e19af40e34be5513253d",
    "homepage": "https://github.com/adamayres/gulp-wrap#readme",
    "jscsConfig": {
        "preset": "google",
        "maximumLineLength": 98,
        "requireBlocksOnNewline": true,
        "validateLineBreaks": "LF"
    },
    "keywords": [
        "gulpplugin",
        "wrap",
        "template",
        "lodash",
        "consolidate",
        "gulp"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/adamayres/gulp-wrap/blob/master/LICENSE"
        }
    ],
    "maintainers": [
        {
            "name": "adamayres"
        },
        {
            "name": "shinnn"
        }
    ],
    "name": "gulp-wrap",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/adamayres/gulp-wrap.git"
    },
    "scripts": {
        "coverage": "istanbul cover _mocha",
        "coveralls": "${npm_package_scripts_coverage} && istanbul-coveralls",
        "pretest": "jscs *.js test/test.js && eslint *.js test/test.js",
        "test": "_mocha"
    },
    "version": "0.13.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
