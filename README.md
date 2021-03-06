# npmdoc-redux

#### basic api documentation for  [redux (4.0.0)](http://redux.js.org)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-redux.svg)](https://travis-ci.org/npmdoc/node-npmdoc-redux)

#### Predictable state container for JavaScript apps

[![NPM](https://nodei.co/npm/redux.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/redux)

- [https://npmdoc.github.io/node-npmdoc-redux/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-redux/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-redux/build/screenshot.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-redux/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-redux/build/screenshot.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-redux/build/screenshot.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "Dan Abramov <dan.abramov@me.com> (https://github.com/gaearon)",
        "Andrew Clark <acdlite@me.com> (https://github.com/acdlite)"
    ],
    "browserify": {
        "transform": [
            "loose-envify"
        ]
    },
    "bugs": {
        "url": "https://github.com/reactjs/redux/issues"
    },
    "dependencies": {
        "loose-envify": "^1.1.0",
        "symbol-observable": "^1.2.0"
    },
    "description": "Predictable state container for JavaScript apps",
    "devDependencies": {
        "babel-cli": "^6.26.0",
        "babel-core": "^6.26.0",
        "babel-eslint": "^8.2.3",
        "babel-jest": "^22.4.3",
        "babel-plugin-external-helpers": "^6.22.0",
        "babel-plugin-transform-object-rest-spread": "^6.26.0",
        "babel-preset-env": "^1.6.1",
        "babel-register": "^6.26.0",
        "cross-env": "^5.1.4",
        "eslint": "^4.19.1",
        "eslint-config-react-app": "^2.1.0",
        "eslint-plugin-flowtype": "^2.46.2",
        "eslint-plugin-import": "^2.11.0",
        "eslint-plugin-jsx-a11y": "^6.0.3",
        "eslint-plugin-react": "^7.7.0",
        "glob": "^7.1.1",
        "jest": "^22.4.3",
        "prettier": "^1.12.1",
        "rimraf": "^2.6.2",
        "rollup": "^0.58.0",
        "rollup-plugin-babel": "^3.0.3",
        "rollup-plugin-node-resolve": "^3.3.0",
        "rollup-plugin-replace": "^2.0.0",
        "rollup-plugin-uglify": "^3.0.0",
        "rxjs": "^5.5.10",
        "typescript": "^2.8.1",
        "typings-tester": "^0.3.1"
    },
    "directories": {},
    "dist": {
        "integrity": "sha512-NnnHF0h0WVE/hXyrB6OlX67LYRuaf/rJcbWvnHHEPCF/Xa/AZpwhs/20WyqzQae5x4SD2F9nPObgBh2rxAgLiA==",
        "shasum": "aa698a92b729315d22b34a0553d7e6533555cc03",
        "tarball": "https://registry.npmjs.org/redux/-/redux-4.0.0.tgz",
        "fileCount": 18,
        "unpackedSize": 147490,
        "npm-signature": "-----BEGIN PGP SIGNATURE-----\r\nVersion: OpenPGP.js v3.0.4\r\nComment: https://openpgpjs.org\r\n\r\nwsFcBAEBCAAQBQJa1koWCRA9TVsSAnZWagAABvMP/iDDVvhi/YgHjHodWqC4\n0u1SXRAcSno2Kh1mD0E11K6duSKyVGrT/ZlVD888dDuuwoeFzfJNtCxEJ2ae\nTSvD88ODFNxhhd9+oAojeBh6uRZKpRJCzVrW4Xw1C97ioaZoz4QY493HfRvs\nCQSmsDAraqDI6VamuDqdvCDuADL+hCCIlCsR2aQiCwiJPx6nPjWSCBjdGsDw\nuxS+k7Ys+g3srZI2b1O7QIOWgmrfbO89B03mL1UXGJ70mS0e/7vkSC6+a9io\n0qdsXGNdhk2+5NNXhbzceaQ5K9eIZg1haH/s0NSZtk62ZqZ0kAsdjl1kLpcB\ncmyt20ZyRlnKTVhCL2R3XijB/djhVY6iRQMIC3bxjqu9DxOAm0gMiGd/sVJ5\n0SJuiYkE0rEpIVqBSQB3Rbki7+ril4JqF3e25zUNWR/soS73w4N17r0PbZOj\ny2r+NzzN3uwEV8Hj92KVQWg8sDuBnRAWwWTolEpeS3gbVuwttDUrdAF7lViY\nRmhDBoC4O+XBkVITCWwKxtfMVVeyVUCF+XruVihp6qcKwUNO7qivlMAOCUJr\nlc2+1NP7fUFmiWuLia/0vADQDwsV0R8//8PWQU2NX8UAAgDyLoBT9Thxxtxp\n94PbRaYcMADWw3MYnwmGXEUZpEv4B8DVTX84FUexOOo5isxGiHwXXf2nfoMQ\nV/+9\r\n=D3gG\r\n-----END PGP SIGNATURE-----\r\n"
    },
    "files": [
        "dist",
        "lib",
        "es",
        "src",
        "index.d.ts"
    ],
    "gitHead": "e95eaf2dc2024fe99dc0f7334a8bd049b4949ed0",
    "homepage": "http://redux.js.org",
    "jest": {
        "testRegex": "(/test/.*\\.spec.js)$"
    },
    "keywords": [
        "redux",
        "reducer",
        "state",
        "predictable",
        "functional",
        "immutable",
        "hot",
        "live",
        "replay",
        "flux",
        "elm"
    ],
    "license": "MIT",
    "main": "lib/redux.js",
    "maintainers": [
        {
            "name": "acdlite"
        },
        {
            "name": "gaearon"
        },
        {
            "name": "timdorr"
        }
    ],
    "module": "es/redux.js",
    "name": "redux",
    "npmFileMap": [
        {
            "basePath": "/dist/",
            "files": [
                "*.js"
            ]
        }
    ],
    "npmName": "redux",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/reactjs/redux.git"
    },
    "scripts": {
        "build": "npm run build:commonjs && npm run build:es && npm run build:umd && npm run build:umd:min",
        "build:commonjs": "cross-env NODE_ENV=cjs rollup -c -o lib/redux.js",
        "build:es": "cross-env BABEL_ENV=es NODE_ENV=es rollup -c -o es/redux.js",
        "build:umd": "cross-env BABEL_ENV=es NODE_ENV=development rollup -c -o dist/redux.js",
        "build:umd:min": "cross-env BABEL_ENV=es NODE_ENV=production rollup -c -o dist/redux.min.js",
        "clean": "rimraf lib dist es coverage",
        "examples:lint": "eslint examples",
        "examples:test": "cross-env CI=true babel-node examples/testAll.js",
        "format": "prettier --write \"{src,test}/**/*.js\"",
        "format:check": "prettier --list-different \"{src,test}/**/*.js\"",
        "lint": "eslint src test build",
        "prepare": "npm run clean && npm run format:check && npm run lint && npm test && npm run build",
        "pretest": "npm run build:commonjs",
        "test": "cross-env BABEL_ENV=commonjs jest",
        "test:cov": "npm test -- --coverage",
        "test:watch": "npm test -- --watch"
    },
    "sideEffects": false,
    "typings": "./index.d.ts",
    "version": "4.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
