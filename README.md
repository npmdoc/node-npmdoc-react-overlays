# npmdoc-react-overlays

#### api documentation for  react-overlays (v0.6.12)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-overlays.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-overlays) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-overlays.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-overlays)

#### Utilities for creating robust overlay components

[![NPM](https://nodei.co/npm/react-overlays.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-overlays)

- [https://npmdoc.github.io/node-npmdoc-react-overlays/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-overlays/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-overlays/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-overlays/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-overlays/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-overlays/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-overlays",
    "version": "0.6.12",
    "description": "Utilities for creating robust overlay components",
    "author": "Jason Quense <monastic.panic@gmail.com>",
    "repository": "react-bootstrap/react-overlays",
    "license": "MIT",
    "main": "lib/index.js",
    "files": [
        "lib"
    ],
    "keywords": [
        "react-overlays",
        "react-component",
        "react",
        "overlay",
        "react-component",
        "tooltip",
        "bootstrap",
        "popover",
        "modal"
    ],
    "scripts": {
        "clean": "rimraf lib",
        "clean:examples": "rimraf examples/static",
        "build": "npm run clean && babel src --out-dir lib",
        "build:examples": "npm run clean:examples && webpack --config webpack/docs.config.js",
        "examples": "npm run clean:examples && babel-node examples/server.js",
        "lint": "eslint examples/*.js src test *.js",
        "test": "npm run lint && npm run testonly",
        "testonly": "karma start --single-run",
        "tdd": "karma start",
        "release": "release"
    },
    "peerDependencies": {
        "react": ">=0.14.0",
        "react-dom": ">=0.14.0"
    },
    "devDependencies": {
        "@monastic.panic/component-playground": "^2.0.0",
        "babel-cli": "^6.10.1",
        "babel-core": "^6.10.4",
        "babel-eslint": "^6.1.2",
        "babel-loader": "^6.2.4",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-object-assign": "^1.2.1",
        "babel-preset-es2015": "^6.9.0",
        "babel-preset-react": "^6.11.1",
        "babel-preset-stage-1": "^6.5.0",
        "chai": "^3.5.0",
        "component-metadata-loader": "^2.0.3",
        "css-loader": "^0.23.1",
        "es5-shim": "^4.5.9",
        "eslint": "^3.0.1",
        "eslint-plugin-mocha": "^4.0.0",
        "eslint-plugin-react": "^5.2.2",
        "isparta-loader": "^2.0.0",
        "jquery": "^3.1.0",
        "karma": "^1.3.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-cli": "^1.0.1",
        "karma-coverage": "^1.1.0",
        "karma-coveralls": "^1.1.2",
        "karma-mocha": "^1.1.1",
        "karma-mocha-reporter": "^2.0.4",
        "karma-sinon-chai": "^1.2.2",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-webpack": "^1.7.0",
        "less": "^2.7.1",
        "less-loader": "^2.2.3",
        "lodash": "^4.13.1",
        "lolex": "^1.5.0",
        "marked": "^0.3.5",
        "mocha": "^2.5.3",
        "node-libs-browser": "^1.0.0",
        "raw-loader": "^0.5.1",
        "react": "^15.3.0",
        "react-addons-test-utils": "^15.3.0",
        "react-bootstrap": "^0.29.5",
        "react-component-metadata": "^3.0.0",
        "react-dom": "^15.3.0",
        "react-hot-loader": "^1.3.0",
        "release-script": "^1.0.2",
        "rimraf": "^2.5.3",
        "simulant": "^0.2.2",
        "sinon": "^1.17.4",
        "sinon-chai": "^2.8.0",
        "style-loader": "^0.13.1",
        "teaspoon": "^6.4.1",
        "webpack": "^1.13.1",
        "webpack-dev-server": "^1.14.1",
        "yargs": "^4.7.1"
    },
    "dependencies": {
        "classnames": "^2.2.5",
        "dom-helpers": "^3.2.0",
        "react-prop-types": "^0.4.0",
        "warning": "^3.0.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
