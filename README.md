# npmdoc-node-protobuf

#### basic api documentation for  node-protobuf (v1.4.3)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-protobuf.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-protobuf) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-protobuf.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-protobuf)

#### A Node.js protocol buffer wrapper

[![NPM](https://nodei.co/npm/node-protobuf.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-protobuf)

- [https://npmdoc.github.io/node-npmdoc-node-protobuf/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-protobuf/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-protobuf/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-protobuf/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-protobuf/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-protobuf/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-protobuf",
    "version": "1.4.3",
    "description": "A Node.js protocol buffer wrapper",
    "author": "Dmitry Gorbunov <atskiisotona@gmail.com",
    "license": "MIT",
    "main": "protobuf.js",
    "repository": "https://github.com/fuwaneko/node-protobuf",
    "dependencies": {
        "bindings": "^1.2.1",
        "nan": "^2.3.5"
    },
    "engines": [
        "node >= 0.12.0"
    ],
    "licence": "MIT",
    "devDependencies": {
        "grunt": "^1.0.0",
        "grunt-release": "^0.14.0",
        "mocha": "^3.1.0"
    },
    "scripts": {
        "test": "./node_modules/.bin/mocha ./test/test.js -R spec",
        "format": "for source in src/* protobuf.js; do clang-format -style=file -i $source; done"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
