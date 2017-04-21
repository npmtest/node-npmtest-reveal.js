# npmtest-reveal.js

#### basic test coverage for  [reveal.js (v3.4.1)](http://lab.hakim.se/reveal-js)  [![npm package](https://img.shields.io/npm/v/npmtest-reveal.js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-reveal.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-reveal.js.svg)](https://travis-ci.org/npmtest/node-npmtest-reveal.js)

#### The HTML Presentation Framework

[![NPM](https://nodei.co/npm/reveal.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/reveal.js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-reveal.js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-reveal.js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-reveal.js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-reveal.js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-reveal.js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-reveal.js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-reveal.js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-reveal.js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-reveal.js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-reveal.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-reveal.js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-reveal.js/build/test-report.html](https://npmtest.github.io/node-npmtest-reveal.js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-reveal.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-reveal.js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-reveal.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-reveal.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-reveal.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-reveal.js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-reveal.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-reveal.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "reveal.js",
    "version": "3.4.1",
    "description": "The HTML Presentation Framework",
    "homepage": "http://lab.hakim.se/reveal-js",
    "subdomain": "revealjs",
    "main": "js/reveal.js",
    "scripts": {
        "test": "grunt test",
        "start": "grunt serve"
    },
    "author": {
        "name": "Hakim El Hattab",
        "web": "http://hakim.se"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/hakimel/reveal.js.git"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "dependencies": {
        "express": "~4.14.0",
        "grunt-cli": "~1.2.0",
        "mustache": "~2.2.1",
        "socket.io": "^1.4.8"
    },
    "devDependencies": {
        "grunt": "~1.0.1",
        "grunt-autoprefixer": "~3.0.3",
        "grunt-contrib-connect": "~0.11.2",
        "grunt-contrib-cssmin": "~0.14.0",
        "grunt-contrib-jshint": "~0.11.3",
        "grunt-contrib-qunit": "~1.2.0",
        "grunt-contrib-uglify": "~0.9.2",
        "grunt-contrib-watch": "~1.0.0",
        "grunt-sass": "~1.2.0",
        "grunt-retire": "~0.3.10",
        "grunt-zip": "~0.17.1",
        "node-sass": "~3.13.0"
    },
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
