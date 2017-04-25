# npmdoc-orchestrator

#### basic api documentation for  [orchestrator (v0.3.8)](https://github.com/robrich/orchestrator)  [![npm package](https://img.shields.io/npm/v/npmdoc-orchestrator.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-orchestrator) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-orchestrator.svg)](https://travis-ci.org/npmdoc/node-npmdoc-orchestrator)

#### A module for sequencing and executing tasks and dependencies in maximum concurrency

[![NPM](https://nodei.co/npm/orchestrator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/orchestrator)

- [https://npmdoc.github.io/node-npmdoc-orchestrator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-orchestrator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-orchestrator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-orchestrator/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-orchestrator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-orchestrator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rob Richardson",
        "url": "http://robrich.org/"
    },
    "bugs": {
        "url": "https://github.com/robrich/orchestrator/issues"
    },
    "dependencies": {
        "end-of-stream": "~0.1.5",
        "sequencify": "~0.0.7",
        "stream-consume": "~0.1.0"
    },
    "description": "A module for sequencing and executing tasks and dependencies in maximum concurrency",
    "devDependencies": {
        "event-stream": "~3.3.4",
        "gulp-uglify": "^2.0.0",
        "jshint": "^2.9.4",
        "map-stream": "~0.0.6",
        "merge-stream": "~1.0.0",
        "mocha": "~3.1.2",
        "q": "~1.4.1",
        "should": "~11.1.1",
        "vinyl-fs": "~2.4.4"
    },
    "directories": {},
    "dist": {
        "shasum": "14e7e9e2764f7315fbac184e506c7aa6df94ad7e",
        "tarball": "https://registry.npmjs.org/orchestrator/-/orchestrator-0.3.8.tgz"
    },
    "gitHead": "8d14e9df94450edf5dae1a16b7a8f051f26670fa",
    "homepage": "https://github.com/robrich/orchestrator",
    "keywords": [
        "async",
        "task",
        "parallel",
        "compose"
    ],
    "license": "MIT",
    "main": "./index.js",
    "maintainers": [
        {
            "name": "robrich"
        }
    ],
    "name": "orchestrator",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/robrich/orchestrator.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "version": "0.3.8",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
