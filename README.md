# npmtest-fauxton

#### basic test coverage for  fauxton (v1.1.11)  [![npm package](https://img.shields.io/npm/v/npmtest-fauxton.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-fauxton) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-fauxton.svg)](https://travis-ci.org/npmtest/node-npmtest-fauxton)

#### Fauxton is a modular CouchDB dashboard and Futon replacement.

[![NPM](https://nodei.co/npm/fauxton.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/fauxton)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-fauxton/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-fauxton/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-fauxton/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-fauxton/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-fauxton/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-fauxton/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-fauxton/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-fauxton/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-fauxton/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-fauxton/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-fauxton/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-fauxton/build/test-report.html](https://npmtest.github.io/node-npmtest-fauxton/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-fauxton/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-fauxton/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-fauxton/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-fauxton/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-fauxton/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-fauxton/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-fauxton/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-fauxton/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "fauxton",
    "version": "1.1.11",
    "description": "Fauxton is a modular CouchDB dashboard and Futon replacement.",
    "main": "./index.js",
    "directories": {
        "test": "test"
    },
    "bin": {
        "fauxton": "./bin/fauxton"
    },
    "babel": {
        "presets": [
            "es2015",
            "react"
        ]
    },
    "devDependencies": {
        "babel-jest": "^18.0.0",
        "bootstrap": "^3.3.7",
        "enzyme": "^2.7.1",
        "es5-shim": "4.5.4",
        "fetch-mock": "^5.9.3",
        "jest": "^18.1.0",
        "less": "^2.7.2",
        "less-loader": "^2.2.3",
        "mocha": "~3.1.2",
        "mocha-loader": "^1.1.0",
        "mocha-phantomjs": "git+https://github.com/garrensmith/mocha-phantomjs.git",
        "nightwatch": "~0.9.0",
        "phantomjs-prebuilt": "^2.1.7",
        "react-addons-test-utils": "~15.4.2",
        "redux-devtools": "^3.3.1",
        "redux-mock-store": "^1.2.1",
        "sinon": "git+https://github.com/sinonjs/sinon.git"
    },
    "dependencies": {
        "async": "~0.2.6",
        "babel": "^6.3.26",
        "babel-cli": "^6.22.2",
        "babel-core": "^6.22.1",
        "babel-loader": "^6.2.9",
        "babel-plugin-transform-object-assign": "^6.8.0",
        "babel-plugin-transform-object-rest-spread": "^6.23.0",
        "babel-preset-es2015": "^6.22.0",
        "babel-preset-react": "^6.22.0",
        "babel-register": "^6.22.0",
        "backbone": "^1.1.0",
        "base-64": "^0.1.0",
        "bluebird": "^3.4.6",
        "brace": "^0.7.0",
        "chai": "^3.5.0",
        "clean-css": "^4.0.5",
        "clipboard": "^1.5.16",
        "couchapp": "~0.11.0",
        "css-loader": "^0.26.1",
        "d3": "^3.4.11",
        "eslint": "^3.14.1",
        "eslint-loader": "^1.3.0",
        "eslint-plugin-react": "^6.7.1",
        "exports-loader": "^0.6.2",
        "expose-loader": "0.7.1",
        "express": "^4.14.1",
        "extract-text-webpack-plugin": "~2.1.0",
        "file-loader": "^0.10.0",
        "flux": "^3.1.0",
        "fs-extra": "^2.0.0",
        "grunt": "~1.0.1",
        "grunt-cli": "~1.2.0",
        "grunt-contrib-clean": "~1.0.0",
        "grunt-contrib-copy": "~1.0.0",
        "grunt-couchapp": "~0.2.1",
        "grunt-exec": "~1.0.1",
        "grunt-shell": "^2.0.1",
        "html-webpack-plugin": "^2.28.0",
        "http-proxy": "^1.16.0",
        "imports-loader": "^0.7.0",
        "jquery": "^2.2.0",
        "jsondiffpatch": "^0.1.41",
        "less": "^2.3.1",
        "less-loader": "^2.2.3",
        "lodash": "^3.10.1",
        "mkdirp": "^0.5.1",
        "moment": "^2.17.1",
        "nano": "~5.12.0",
        "optimist": "^0.6.1",
        "pouchdb-adapter-http": "^6.1.2",
        "pouchdb-core": "^6.1.2",
        "react": "~15.4.1",
        "react-addons-css-transition-group": "~15.4.2",
        "react-bootstrap": "^0.30.7",
        "react-dom": "~15.4.1",
        "react-redux": "^5.0.0",
        "react-select": "1.0.0-rc.2",
        "redux": "^3.6.0",
        "redux-thunk": "^2.1.0",
        "request": "^2.54.0",
        "semver": "^5.1.0",
        "send": "^0.14.2",
        "style-loader": "^0.13.1",
        "underscore": "~1.4.2",
        "url": "~0.7.9",
        "url-loader": "^0.5.7",
        "urls": "~0.0.3",
        "url-polyfill": "git+https://github.com/webcomponents/URL.git",
        "uuid": "^3.0.1",
        "velocity-animate": "^1.4.2",
        "velocity-react": "1.2.0",
        "visualizeRevTree": "git+https://github.com/neojski/visualizeRevTree.git#gh-pages",
        "webpack": "~2.2.1",
        "webpack-dev-server": "~2.4.1",
        "whatwg-fetch": "~2.0.1"
    },
    "scripts": {
        "stylecheck": "eslint --ext=js,jsx .",
        "webpack:dev": "webpack --debug --progress --colors --config ./webpack.config.dev.js",
        "webpack:test": "webpack --debug --progress --colors --config ./webpack.config.test.js",
        "webpack:release": "webpack --optimize-minimize --debug --progress --colors --config ./webpack.config.release.js",
        "jest": "jest --config ./jest-config.json",
        "test": "grunt test && npm run jest",
        "phantomjs": "./node_modules/.bin/mocha-phantomjs --debug=false --ssl-protocol=sslv2 --web-security=false --ignore-ssl-errors=true ./test/runner.html",
        "couchdebug": "grunt couchdebug",
        "couchdb": "grunt couchdb",
        "couchapp": "grunt couchapp_deploy",
        "dev": "node ./devserver.js",
        "devtests": "webpack-dev-server --config webpack.config.test-dev.js --debug --progress",
        "nightwatch": "grunt nightwatch",
        "start": "node ./bin/fauxton",
        "start-debug": "DIST=./dist/debug node ./bin/fauxton",
        "preversion": "node version-check.js && grunt release",
        "test-before-publish": "npm run preversion && npm install . -g",
        "create:animaldb": "./bin/create-animal-db",
        "docker:couchdb-up": "docker-compose -f ./docker/dc.selenium.yml up -d couchdb",
        "docker:selenium-up": "docker-compose -f ./docker/dc.selenium.yml up -d selenium",
        "docker:selenium-debug-up": "docker-compose -f ./docker/dc.selenium-debug.yml up -d selenium",
        "docker:reset": "npm run docker:down && npm run docker:up",
        "docker:logs": "docker logs couchdb",
        "docker:up": "docker-compose -f ./docker/dc.selenium.yml up -d",
        "docker:debug-up": "docker-compose -f ./docker/dc.selenium-debug.yml up -d",
        "docker:down": "docker-compose -f ./docker/dc.selenium.yml down",
        "remove-test-dbs": "node ./bin/remove-test-dbs.js"
    },
    "repository": {
        "type": "git",
        "url": "https://git-wip-us.apache.org/repos/asf/couchdb.git"
    },
    "keywords": [
        "couchdb",
        "futon",
        "fauxton"
    ],
    "author": "The Apache CouchDB contributors",
    "license": "Apache-2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
