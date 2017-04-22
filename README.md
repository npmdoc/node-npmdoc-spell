# npmdoc-spell

#### api documentation for  [spell (v1.0.0)](http://github.com/dscape/spell)  [![npm package](https://img.shields.io/npm/v/npmdoc-spell.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-spell) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-spell.svg)](https://travis-ci.org/npmdoc/node-npmdoc-spell)

#### javascript dictionary module for node.js, and the browser

[![NPM](https://nodei.co/npm/spell.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/spell)

- [https://npmdoc.github.io/node-npmdoc-spell/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-spell/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-spell/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-spell/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-spell/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-spell/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nuno Job",
        "url": "http://nunojob.com"
    },
    "bugs": {
        "url": "https://github.com/dscape/spell/issues"
    },
    "contributors": [
        {
            "name": "Pedro Teixeira",
            "url": "http://metaduck.com"
        }
    ],
    "dependencies": {},
    "description": "javascript dictionary module for node.js, and the browser",
    "devDependencies": {
        "mocha": "0.3.6",
        "should": "0.3.2"
    },
    "directories": {},
    "dist": {
        "shasum": "10a3b9b056a184b64a1b120e2425f6f7a250aa85",
        "tarball": "https://registry.npmjs.org/spell/-/spell-1.0.0.tgz"
    },
    "engines": {
        "node": ">=0.3.6"
    },
    "homepage": "http://github.com/dscape/spell",
    "keywords": [
        "spell",
        "speller",
        "dictionary",
        "nlp",
        "dict",
        "spell check"
    ],
    "main": "./spell.js",
    "maintainers": [
        {
            "name": "dscape"
        }
    ],
    "name": "spell",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/dscape/spell.git"
    },
    "scripts": {
        "perf1": "node --prof --trace-opt --trace-bailout --trace-deopt test/perf.js 1",
        "perf2": "node --prof --trace-opt --trace-bailout --trace-deopt test/perf.js 2",
        "test": "./node_modules/mocha/bin/mocha --globals _test_spell -r should test/spell.js"
    },
    "version": "1.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
