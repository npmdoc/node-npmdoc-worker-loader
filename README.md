# npmdoc-worker-loader

#### api documentation for  worker-loader (v0.8.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-worker-loader.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-worker-loader) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-worker-loader.svg)](https://travis-ci.org/npmdoc/node-npmdoc-worker-loader)

#### worker loader module for webpack

[![NPM](https://nodei.co/npm/worker-loader.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/worker-loader)

- [https://npmdoc.github.io/node-npmdoc-worker-loader/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-worker-loader/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-worker-loader/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-worker-loader/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-worker-loader/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-worker-loader/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "worker-loader",
    "version": "0.8.0",
    "author": "Tobias Koppers @sokra",
    "description": "worker loader module for webpack",
    "scripts": {
        "test": "mocha",
        "posttest": "eslint ."
    },
    "eslintConfig": {
        "extends": "webpack",
        "rules": {
            "linebreak-style": 0,
            "comma-dangle": [
                "error",
                {
                    "arrays": "always-multiline",
                    "objects": "always-multiline",
                    "imports": "always-multiline",
                    "exports": "always-multiline",
                    "functions": "never"
                }
            ],
            "no-underscore-dangle": 0,
            "no-param-reassign": 0,
            "prefer-destructuring": 0,
            "strict": 0
        }
    },
    "peerDependencies": {
        "webpack": ">=0.9 <2 || ^2.1.0-beta || ^2.2.0"
    },
    "dependencies": {
        "loader-utils": "^1.0.2"
    },
    "devDependencies": {
        "del": "^2.2.2",
        "eslint": "^3.16.0",
        "eslint-config-webpack": "^1.0.0",
        "eslint-plugin-import": "^2.2.0",
        "mocha": "^3.2.0",
        "webpack": "^2.2.1"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/webpack-contrib/worker-loader.git"
    },
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
