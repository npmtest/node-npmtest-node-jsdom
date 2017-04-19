# npmtest-node-jsdom

#### test coverage for  [node-jsdom (v3.1.5)](https://github.com/darrylwest/node-jsdom)  [![npm package](https://img.shields.io/npm/v/npmtest-node-jsdom.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-jsdom) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-jsdom.svg)](https://travis-ci.org/npmtest/node-npmtest-node-jsdom)

#### A JavaScript implementation of the DOM and HTML standards cloned from the original jsdom branch 3.x

[![NPM](https://nodei.co/npm/node-jsdom.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-jsdom)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-jsdom/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-jsdom/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-jsdom/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-jsdom/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-jsdom/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-jsdom/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-jsdom/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-jsdom/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-jsdom/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-jsdom/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-jsdom/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-jsdom/build/test-report.html](https://npmtest.github.io/node-npmtest-node-jsdom/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-jsdom/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-jsdom/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-jsdom/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-jsdom/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-jsdom/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-jsdom/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-jsdom/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-jsdom/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "browser": {
        "canvas": false,
        "contextify": "./lib/jsdom/contextify-shim.js",
        "request": "browser-request"
    },
    "bugs": {
        "url": "https://github.com/darrylwest/node-jsdom/issues"
    },
    "contributors": [
        {
            "name": "Darryl West"
        },
        {
            "name": "Vincent Greene"
        },
        {
            "name": "Dav Glass"
        },
        {
            "name": "Felix Gnass"
        },
        {
            "name": "Charlie Robbins"
        },
        {
            "name": "Aria Stewart"
        },
        {
            "name": "Matthew",
            "url": "http://github.com/matthewpflueger/"
        },
        {
            "name": "Olivier El Mekki",
            "url": "http://blog.olivier-elmekki.com/"
        },
        {
            "name": "Shimon Dookdin"
        },
        {
            "name": "Daniel Cassidy",
            "url": "http://www.danielcassidy.me.uk/"
        },
        {
            "name": "Sam Ruby",
            "url": "http://intertwingly.net/blog/"
        },
        {
            "name": "hij1nx",
            "url": "http://github.com/hij1nx"
        },
        {
            "name": "Yonathan Randolph",
            "url": "http://github.com/yonran"
        },
        {
            "name": "Martin Davis",
            "url": "http://github.com/waslogic"
        },
        {
            "name": "Andreas Lind Petersen"
        },
        {
            "name": "d-ash",
            "url": "http://github.com/d-ash"
        },
        {
            "name": "Robin Zhong"
        },
        {
            "name": "Alexander Flatter"
        },
        {
            "name": "Heng Liu"
        },
        {
            "name": "Brian McDaniel",
            "url": "http://github.com/brianmcd"
        },
        {
            "name": "John Hurliman"
        },
        {
            "name": "Jimmy Mabey"
        },
        {
            "name": "Gregory Tomlinson"
        },
        {
            "name": "Jason Davies",
            "url": "http://www.jasondavies.com/"
        },
        {
            "name": "Josh Marshall",
            "url": "http://www.ponderingtheobvious.com/"
        },
        {
            "name": "Jason Priestley",
            "url": "https://github.com/jhp"
        },
        {
            "name": "Derek Lindahl",
            "url": "https://github.com/dlindahl"
        },
        {
            "name": "Chris Roebuck",
            "url": "http://www.quillu.com"
        },
        {
            "name": "Avi Deitcher",
            "url": "https://github.com/deitch"
        },
        {
            "name": "Nao Iizuka",
            "url": "https://github.com/iizukanao"
        },
        {
            "name": "Peter Perenyi",
            "url": "https://github.com/sinegar"
        },
        {
            "name": "Tiago Rodrigues",
            "url": "http://trodrigues.net"
        },
        {
            "name": "Samori Gorse",
            "url": "http://github.com/shinuza"
        },
        {
            "name": "John Roberts"
        },
        {
            "name": "Chad Walker",
            "url": "https://github.com/chad3814"
        },
        {
            "name": "Zach Smith",
            "url": "https://github.com/xcoderzach"
        }
    ],
    "dependencies": {
        "acorn": "0.11.0",
        "acorn-globals": "^1.0.2",
        "browser-request": ">= 0.3.1 < 0.4.0",
        "contextify": ">= 0.1.9 < 0.2.0",
        "cssom": ">= 0.3.0 < 0.4.0",
        "cssstyle": ">= 0.2.21 < 0.3.0",
        "escodegen": "^1.6.1",
        "htmlparser2": ">= 3.7.3 < 4.0.0",
        "nwmatcher": ">= 1.3.4 < 2.0.0",
        "parse5": ">= 1.3.1 < 2.0.0",
        "request": ">= 2.44.0 < 3.0.0",
        "xml-name-validator": "^1.0.0",
        "xmlhttprequest": ">= 1.6.0 < 2.0.0"
    },
    "description": "A JavaScript implementation of the DOM and HTML standards cloned from the original jsdom branch 3.x",
    "devDependencies": {
        "browserify": "^8.1.3",
        "colors": "^0.6.2",
        "http-server": "^0.6.1",
        "jshint": "^2.5.0",
        "multiline": "^1.0.1",
        "nodeunit": "~0.8.0",
        "optimist": "*",
        "portfinder": "^0.2.1",
        "q": "^1.0.1",
        "selenium-standalone": "^2.42.0-2.9.0",
        "urlmaster": ">=0.2.15",
        "wd": "^0.2.21"
    },
    "directories": {},
    "dist": {
        "shasum": "f843e5c94afdf63741fcf16565b24e7a60dde5ad",
        "tarball": "https://registry.npmjs.org/node-jsdom/-/node-jsdom-3.1.5.tgz"
    },
    "files": [
        "lib/"
    ],
    "gitHead": "e94fb81f1c50ef318af41f0b1d0575ab3a2c3c78",
    "homepage": "https://github.com/darrylwest/node-jsdom",
    "keywords": [
        "dom",
        "html",
        "whatwg",
        "w3c",
        "jsdom"
    ],
    "license": {
        "type": "MIT",
        "url": "https://github.com/darrylwest/node-jsdom/LICENSE.txt"
    },
    "main": "./lib/jsdom",
    "maintainers": [
        {
            "name": "darryl.west"
        }
    ],
    "name": "node-jsdom",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/darrylwest/node-jsdom.git"
    },
    "scripts": {
        "lint": "jshint lib/ && jshint test/",
        "pretest": "git submodule update --init --recursive",
        "test": "node ./test/runner",
        "test-browser": "node ./test/browser-runner"
    },
    "version": "3.1.5"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
