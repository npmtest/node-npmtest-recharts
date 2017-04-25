# npmtest-recharts

#### basic test coverage for  [recharts (v0.22.3)](https://github.com/recharts/recharts)  [![npm package](https://img.shields.io/npm/v/npmtest-recharts.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-recharts) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-recharts.svg)](https://travis-ci.org/npmtest/node-npmtest-recharts)

#### React charts

[![NPM](https://nodei.co/npm/recharts.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/recharts)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-recharts/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-recharts/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-recharts/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-recharts/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-recharts/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-recharts/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-recharts/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-recharts/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-recharts/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-recharts/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-recharts/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-recharts/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-recharts/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-recharts/build/test-report.html](https://npmtest.github.io/node-npmtest-recharts/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-recharts/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-recharts/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-recharts/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-recharts/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-recharts/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-recharts/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-recharts/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-recharts/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "recharts group"
    },
    "bugs": {
        "url": "https://github.com/recharts/recharts/issues"
    },
    "dependencies": {
        "classnames": "2.2.5",
        "core-js": "2.4.1",
        "d3-scale": "1.0.4",
        "d3-shape": "1.0.4",
        "lodash": "~4.17.4",
        "prop-types": "~15.5.7",
        "react-resize-detector": "0.3.3",
        "react-smooth": "0.1.20",
        "recharts-scale": "0.3.0",
        "reduce-css-calc": "1.3.0"
    },
    "description": "React charts",
    "devDependencies": {
        "babel-cli": "^6.18.0",
        "babel-core": "^6.18.2",
        "babel-eslint": "^7.0.0",
        "babel-loader": "^6.2.8",
        "babel-plugin-istanbul": "3.0.0",
        "babel-plugin-lodash": "^3.2.10",
        "babel-plugin-transform-class-properties": "^6.19.0",
        "babel-plugin-transform-decorators-legacy": "^1.3.4",
        "babel-plugin-transform-export-extensions": "^6.8.0",
        "babel-plugin-transform-function-bind": "^6.8.0",
        "babel-plugin-transform-object-rest-spread": "^6.19.0",
        "babel-polyfill": "^6.16.0",
        "babel-preset-es2015": "^6.18.0",
        "babel-preset-react": "^6.16.0",
        "chai": "^3.5.0",
        "chai-enzyme": "^0.5.2",
        "cross-env": "^3.1.4",
        "enzyme": "^2.6.0",
        "escope": "^3.6.0",
        "eslint": "^3.8.1",
        "eslint-config-airbnb": "^12.0.0",
        "eslint-plugin-import": "^1.16.0",
        "eslint-plugin-jsx-a11y": "^2.2.0",
        "eslint-plugin-react": "^6.4.1",
        "estraverse-fb": "^1.3.1",
        "json-loader": "^0.5.4",
        "karma": "^1.3.0",
        "karma-chai": "^0.1.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-coverage": "^1.0.0",
        "karma-coveralls": "^1.1.2",
        "karma-firefox-launcher": "^1.0.0",
        "karma-mocha": "^1.3.0",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-webpack": "^2.0.1",
        "lodash-webpack-plugin": "^0.10.5",
        "mocha": "^3.1.0",
        "pre-commit": "^1.1.3",
        "react": "^15.4.1",
        "react-addons-test-utils": "^15.4.1",
        "react-addons-transition-group": "^15.4.1",
        "react-dom": "^15.4.1",
        "react-hot-loader": "^1.3.0",
        "react-router": "^3.0.1",
        "rimraf": "^2.5.3",
        "sinon": "^1.17.0",
        "webpack": "^2.2.0",
        "webpack-bundle-analyzer": "^2.2.1",
        "webpack-dev-server": "^2.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "99137aa4b10c1aa8aa2266181d2d68cda03e7ae9",
        "tarball": "https://registry.npmjs.org/recharts/-/recharts-0.22.3.tgz"
    },
    "files": [
        "*.md",
        "demo",
        "es6",
        "lib",
        "umd",
        "src"
    ],
    "gitHead": "583e83935d0d51c3e1b90668342e6f9587609ee0",
    "homepage": "https://github.com/recharts/recharts",
    "jsnext:main": "es6/index",
    "keywords": [
        "react",
        "reactjs",
        "chart",
        "react-component"
    ],
    "license": "MIT",
    "main": "lib/index",
    "maintainers": [
        {
            "name": "xile611"
        }
    ],
    "module": "es6/index",
    "name": "recharts",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0",
        "react-addons-transition-group": "^0.14.0 || ^15.0.0"
    },
    "pre-commit": [
        "lint"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/recharts/recharts.git"
    },
    "scripts": {
        "autofix": "eslint src --fix",
        "build": "npm run build-cjs && npm run build-es6 && rimraf umd && npm run build-umd && npm run build-min",
        "build-cjs": "rimraf lib && cross-env NODE_ENV=commonjs babel ./src -d lib",
        "build-es6": "rimraf es6 && babel ./src -d es6",
        "build-min": "cross-env NODE_ENV=production webpack src/index.js umd/Recharts.min.js",
        "build-umd": "cross-env NODE_ENV=development webpack src/index.js umd/Recharts.js",
        "bundle-analyse": "cross-env NODE_ENV=analyse webpack src/index.js umd/Recharts.js",
        "demo": "webpack-dev-server --progress --port 3000 --content-base demo --inline --config demo/webpack.config.js",
        "lint": "eslint src",
        "test": "cross-env NODE_ENV=test karma start test/karma.conf.js"
    },
    "version": "0.22.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
