# npmtest-react-native-elements

#### basic test coverage for  [react-native-elements (v0.11.1)](https://github.com/react-native-training/react-native-elements#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-react-native-elements.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-native-elements) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-native-elements.svg)](https://travis-ci.org/npmtest/node-npmtest-react-native-elements)

#### React Native Elements & UI Toolkit

[![NPM](https://nodei.co/npm/react-native-elements.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-native-elements)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-native-elements/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-native-elements/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-native-elements/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-native-elements/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-native-elements/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-native-elements/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-native-elements/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-native-elements/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-native-elements/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-native-elements/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-native-elements/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-native-elements/build/test-report.html](https://npmtest.github.io/node-npmtest-react-native-elements/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-native-elements/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-native-elements/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-native-elements/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-native-elements/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-native-elements/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-native-elements/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-native-elements/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-native-elements/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-native-elements",
    "version": "0.11.1",
    "description": "React Native Elements & UI Toolkit",
    "main": "src/index.js",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/dabit3/React-Native-Elements.git"
    },
    "keywords": [
        "react-native",
        "reactjs",
        "reactnative",
        "bootstrap"
    ],
    "scripts": {
        "build": "rm -rf build; webpack",
        "test": "jest",
        "test:watch": "jest --watch",
        "test:coverage": "jest --coverage",
        "postinstall": "./node_modules/.bin/opencollective-postinstall || exit 0",
        "lint": "eslint src/"
    },
    "peerDependencies": {
        "react-native-vector-icons": "~4.0.0"
    },
    "author": "Nader Dabit",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/react-native-training/react-native-elements/issues"
    },
    "homepage": "https://github.com/react-native-training/react-native-elements#readme",
    "collective": {
        "type": "opencollective",
        "url": "https://opencollective.com/react-native-elements",
        "logo": "https://opencollective.com/react-native-elements/logo.txt"
    },
    "dependencies": {
        "react-native-side-menu": "^0.20.1",
        "react-native-tab-navigator": "^0.3.3"
    },
    "devDependencies": {
        "babel": "^6.23.0",
        "babel-core": "^6.23.1",
        "babel-eslint": "^7.1.1",
        "babel-jest": "^19.0.0",
        "babel-loader": "^6.3.2",
        "babel-preset-react-native": "^1.9.1",
        "codecov": "^2.1.0",
        "enzyme": "^2.8.0",
        "enzyme-to-json": "^1.5.0",
        "eslint": "^3.17.1",
        "eslint-plugin-react": "^6.10.0",
        "eslint-plugin-react-native": "^2.3.1",
        "jest": "^19.0.2",
        "react": "^15.4.2",
        "react-addons-test-utils": "^15.4.2",
        "react-dom": "^15.4.2",
        "react-native": "^0.41.2",
        "react-native-vector-icons": "^4.0.0",
        "webpack": "^2.2.1",
        "opencollective-postinstall": "^1.0.15"
    },
    "jest": {
        "preset": "react-native",
        "coverageDirectory": "./coverage/",
        "collectCoverageFrom": [
            "src/**/*.js",
            "!src/index.js",
            "!src/tabs/*.js",
            "!src/sidemenu/*.js",
            "!src/helpers/*.js"
        ],
        "collectCoverage": true,
        "globals": {
            "__DEV__": true
        }
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
