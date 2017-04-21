# npmdoc-axon-rpc

#### api documentation for  axon-rpc (v0.0.3)  [![npm package](https://img.shields.io/npm/v/npmdoc-axon-rpc.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-axon-rpc) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-axon-rpc.svg)](https://travis-ci.org/npmdoc/node-npmdoc-axon-rpc)

#### Remote procedure calls built on top of axon.

[![NPM](https://nodei.co/npm/axon-rpc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/axon-rpc)

- [https://npmdoc.github.io/node-npmdoc-axon-rpc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-axon-rpc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-axon-rpc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-axon-rpc/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-axon-rpc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-axon-rpc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "axon-rpc",
    "version": "0.0.3",
    "description": "Remote procedure calls built on top of axon.",
    "keywords": [
        "axon",
        "rpc",
        "cloud"
    ],
    "author": "TJ Holowaychuk <tj@learnboost.com>",
    "contributors": [
        {
            "name": "Bret Copeland",
            "url": "https://github.com/bretcope"
        }
    ],
    "dependencies": {
        "debug": "*",
        "commander": "1.0.5"
    },
    "devDependencies": {
        "axon": "2.0.0",
        "better-assert": "*",
        "mocha": "*"
    },
    "bin": {
        "arpc": "bin/arpc"
    },
    "main": "index",
    "scripts": {
        "test": "mocha --reporter spec"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/visionmedia/axon-rpc.git"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
