# npmdoc-chartist

#### api documentation for  [chartist (v0.11.0)](https://gionkunz.github.io/chartist-js)  [![npm package](https://img.shields.io/npm/v/npmdoc-chartist.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-chartist) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-chartist.svg)](https://travis-ci.org/npmdoc/node-npmdoc-chartist)

#### Simple, responsive charts

[![NPM](https://nodei.co/npm/chartist.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/chartist)

- [https://npmdoc.github.io/node-npmdoc-chartist/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-chartist/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-chartist/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-chartist/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-chartist/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-chartist/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gion Kunz"
    },
    "browser": "dist/chartist.js",
    "bugs": {
        "url": "https://github.com/gionkunz/chartist-js/issues"
    },
    "config": {
        "banner": "/* Chartist.js <%= pkg.version %>\n * Copyright © <%= year %> Gion Kunz\n * Free to use under either the WTFPL license or the MIT license.\n * https://raw.githubusercontent.com/gionkunz/chartist-js/master/LICENSE-WTFPL\n * https://raw.githubusercontent.com/gionkunz/chartist-js/master/LICENSE-MIT\n */\n",
        "src": "src",
        "dist": "dist",
        "site": "site",
        "tmp": ".tmp",
        "public": ".public",
        "test": "test"
    },
    "dependencies": {},
    "description": "Simple, responsive charts",
    "devDependencies": {
        "assemble-dox": "0.0.2",
        "grunt": "^1.0.1",
        "grunt-assemble": "^0.4.0",
        "grunt-concurrent": "^2.3.0",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-concat": "^1.0.1",
        "grunt-contrib-connect": "^1.0.2",
        "grunt-contrib-copy": "^1.0.0",
        "grunt-contrib-cssmin": "^1.0.1",
        "grunt-contrib-htmlmin": "^1.4.0",
        "grunt-contrib-imagemin": "^1.0.0",
        "grunt-contrib-jasmine": "^1.0.3",
        "grunt-contrib-jshint": "^1.0.0",
        "grunt-contrib-uglify": "^1.0.1",
        "grunt-contrib-watch": "^1.0.0",
        "grunt-critical": "^0.2.1",
        "grunt-newer": "^1.1.0",
        "grunt-sass": "^1.1.0",
        "grunt-svgmin": "^3.2.0",
        "grunt-template": "^0.2.3",
        "grunt-umd": "^2.3.1",
        "grunt-usemin": "^3.1.1",
        "handlebars-helpers": "^0.6.1",
        "jasmine-jquery": "^2.1.1",
        "jquery": "^3.0.0",
        "jshint-stylish": "^2.2.0",
        "load-grunt-config": "^0.19.2",
        "lodash": "^4.13.1",
        "seed-random": "^2.2.0",
        "time-grunt": "^1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "84ba5e05490d096d93dcfa9343ebc31ef6a3bd28",
        "tarball": "https://registry.npmjs.org/chartist/-/chartist-0.11.0.tgz"
    },
    "engines": {
        "node": ">=4.6.0"
    },
    "files": [
        "dist",
        "LICENSE-WTFPL",
        "LICENSE-MIT",
        "package.json",
        "README.md"
    ],
    "gitHead": "e2ee06153f099b548530ef517a247fc0dc978cb8",
    "homepage": "https://gionkunz.github.io/chartist-js",
    "keywords": [
        "chartist",
        "responsive charts",
        "charts",
        "charting"
    ],
    "license": "MIT OR WTFPL",
    "licenses": [
        {
            "type": "WTFPL",
            "url": "https://github.com/gionkunz/chartist-js/blob/master/LICENSE-WTFPL"
        },
        {
            "type": "MIT",
            "url": "https://github.com/gionkunz/chartist-js/blob/master/LICENSE-MIT"
        }
    ],
    "main": "dist/chartist.js",
    "maintainers": [
        {
            "name": "gionkunz"
        }
    ],
    "name": "chartist",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/gionkunz/chartist-js.git"
    },
    "scripts": {
        "build": "grunt build",
        "dev": "grunt dev",
        "preview": "grunt preview",
        "public": "grunt public",
        "start": "grunt",
        "test": "grunt test"
    },
    "style": "dist/chartist.min.css",
    "title": "Chartist.js",
    "version": "0.11.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
