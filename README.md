# test coverage for  [graphql (v0.9.2)](https://github.com/graphql/graphql-js)  [![npm package](https://img.shields.io/npm/v/npmtest-graphql.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-graphql) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-graphql.svg)](https://travis-ci.org/npmtest/node-npmtest-graphql)
#### A Query Language and Runtime which can target any service.

[![NPM](https://nodei.co/npm/graphql.png?downloads=true)](https://www.npmjs.com/package/graphql)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-graphql/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-graphql/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-graphql/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-graphql/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-graphql/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-graphql/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-graphql/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-graphql/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-graphql/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-graphql/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-graphql%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-graphql/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-graphql/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-graphql%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-graphql/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-graphql/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-graphql/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/graphql/graphql-js/issues"
    },
    "contributors": [
        {
            "name": "Lee Byron",
            "email": "lee@leebyron.com",
            "url": "http://leebyron.com/"
        },
        {
            "name": "Nicholas Schrock",
            "email": "schrockn@fb.com"
        },
        {
            "name": "Daniel Schafer",
            "email": "dschafer@fb.com"
        }
    ],
    "dependencies": {
        "iterall": "1.0.3"
    },
    "description": "A Query Language and Runtime which can target any service.",
    "devDependencies": {
        "babel-cli": "6.22.2",
        "babel-eslint": "7.2.1",
        "babel-plugin-check-es2015-constants": "6.22.0",
        "babel-plugin-syntax-async-functions": "6.13.0",
        "babel-plugin-transform-class-properties": "6.22.0",
        "babel-plugin-transform-es2015-arrow-functions": "6.22.0",
        "babel-plugin-transform-es2015-block-scoped-functions": "6.22.0",
        "babel-plugin-transform-es2015-block-scoping": "6.22.0",
        "babel-plugin-transform-es2015-classes": "6.22.0",
        "babel-plugin-transform-es2015-computed-properties": "6.22.0",
        "babel-plugin-transform-es2015-destructuring": "6.23.0",
        "babel-plugin-transform-es2015-duplicate-keys": "6.22.0",
        "babel-plugin-transform-es2015-function-name": "6.22.0",
        "babel-plugin-transform-es2015-literals": "6.22.0",
        "babel-plugin-transform-es2015-modules-commonjs": "6.24.0",
        "babel-plugin-transform-es2015-object-super": "6.22.0",
        "babel-plugin-transform-es2015-parameters": "6.22.0",
        "babel-plugin-transform-es2015-shorthand-properties": "6.22.0",
        "babel-plugin-transform-es2015-spread": "6.22.0",
        "babel-plugin-transform-es2015-template-literals": "6.22.0",
        "babel-plugin-transform-es3-property-literals": "^6.22.0",
        "babel-plugin-transform-flow-strip-types": "6.22.0",
        "babel-plugin-transform-object-rest-spread": "6.23.0",
        "babel-plugin-transform-regenerator": "6.22.0",
        "chai": "3.5.0",
        "chai-json-equal": "0.0.1",
        "chai-subset": "1.5.0",
        "coveralls": "2.13.0",
        "eslint": "3.18.0",
        "eslint-plugin-babel": "4.1.1",
        "eslint-plugin-flowtype": "2.30.4",
        "flow-bin": "0.42.0",
        "isparta": "4.0.0",
        "mocha": "3.2.0",
        "sane": "1.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "2cb5c635de13f790a77c5879649cb401b1589386",
        "tarball": "https://registry.npmjs.org/graphql/-/graphql-0.9.2.tgz"
    },
    "gitHead": "5ba817e13f7547ce99c4963ee74a805ed3f74dd8",
    "homepage": "https://github.com/graphql/graphql-js",
    "license": "BSD-3-Clause",
    "main": "index.js",
    "maintainers": [
        {
            "name": "dschafer",
            "email": "dschafer@fb.com"
        },
        {
            "name": "fb",
            "email": "opensource+npm@fb.com"
        },
        {
            "name": "leebyron",
            "email": "lee@leebyron.com"
        },
        {
            "name": "wincent",
            "email": "greg@hurrell.net"
        }
    ],
    "name": "graphql",
    "optionalDependencies": {},
    "options": {
        "mocha": "--require ./resources/mocha-bootload --check-leaks --full-trace src/**/__tests__/**/*-test.js"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/graphql/graphql-js.git"
    },
    "scripts": {
        "build": "babel src --optional runtime --ignore __tests__ --out-dir dist/ && cp package.json dist/ && npm run build-dot-flow",
        "build-dot-flow": "find ./src -name '*.js' -not -path '*/__tests__*' | while read filepath; do cp $filepath 'echo $filepath | sed 's/\\/src\\//\\/dist\\//g''.flow; done",
        "check": "flow check",
        "check-cover": "for file in {src/*.js,src/**/*.js}; do echo $file; flow coverage $file; done",
        "cover": "babel-node ./node_modules/.bin/isparta cover --root src --report html _mocha -- $npm_package_options_mocha",
        "cover:lcov": "babel-node ./node_modules/.bin/isparta cover --root src --report lcovonly _mocha -- $npm_package_options_mocha",
        "lint": "eslint src || (printf '\\033[33mTry: \\033[7m npm run lint -- --fix \\033[0m\\n' && exit 1)",
        "prepublish": ". ./resources/prepublish.sh",
        "preversion": ". ./resources/checkgit.sh && npm test",
        "t": "babel-node ./node_modules/.bin/_mocha --require ./resources/mocha-bootload",
        "test": "npm run lint && npm run check && npm run testonly",
        "testonly": "babel-node ./node_modules/.bin/_mocha $npm_package_options_mocha",
        "watch": "babel-node ./resources/watch.js"
    },
    "version": "0.9.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
