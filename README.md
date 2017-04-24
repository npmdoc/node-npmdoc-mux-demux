# npmdoc-mux-demux

#### api documentation for  [mux-demux (v3.7.9)](http://github.com/dominictarr/mux-demux)  [![npm package](https://img.shields.io/npm/v/npmdoc-mux-demux.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mux-demux) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mux-demux.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mux-demux)

#### multiplex streams

[![NPM](https://nodei.co/npm/mux-demux.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mux-demux)

- [https://npmdoc.github.io/node-npmdoc-mux-demux/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mux-demux/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mux-demux/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mux-demux/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mux-demux/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mux-demux/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dominic Tarr",
        "url": "dominictarr.com"
    },
    "bugs": {
        "url": "https://github.com/dominictarr/mux-demux/issues"
    },
    "dependencies": {
        "duplex": "~1.0.0",
        "json-buffer": "~2.0.4",
        "msgpack-stream": "~0.0.10",
        "stream-combiner": "0.0.2",
        "stream-serializer": "~1.1.1",
        "through": "~2.3.1",
        "xtend": "~1.0.3"
    },
    "description": "multiplex streams",
    "devDependencies": {
        "event-stream": "~3.0.7",
        "tape": "~0.2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "35367718fd3601c80bce2eb762531576d7a4acef",
        "tarball": "https://registry.npmjs.org/mux-demux/-/mux-demux-3.7.9.tgz"
    },
    "homepage": "http://github.com/dominictarr/mux-demux",
    "maintainers": [
        {
            "name": "dominictarr"
        }
    ],
    "name": "mux-demux",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/dominictarr/mux-demux.git"
    },
    "scripts": {
        "test": "set -e; for t in test/*.js; do node $t; done"
    },
    "stability": "stable",
    "testling": {
        "files": "test/*.js",
        "browsers": {
            "ie": [
                8,
                9,
                10
            ],
            "firefox": [
                17,
                18
            ],
            "chrome": [
                23,
                24
            ],
            "safari": [
                5,
                6
            ],
            "opera": [
                12
            ]
        }
    },
    "version": "3.7.9",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
