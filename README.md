# api documentation for  [redux (v3.6.0)](http://redux.js.org)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-redux.svg)](https://travis-ci.org/npmdoc/node-npmdoc-redux)
#### Predictable state container for JavaScript apps

[![NPM](https://nodei.co/npm/redux.png?downloads=true)](https://www.npmjs.com/package/redux)

[![apidoc](https://npmdoc.github.io/node-npmdoc-redux/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-redux_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-redux/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-redux/build/screen-capture.npmPackageListing.svg)



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
        "lodash": "^4.2.1",
        "lodash-es": "^4.2.1",
        "loose-envify": "^1.1.0",
        "symbol-observable": "^1.0.2"
    },
    "description": "Predictable state container for JavaScript apps",
    "devDependencies": {
        "babel-cli": "^6.3.15",
        "babel-core": "^6.3.15",
        "babel-eslint": "^4.1.6",
        "babel-loader": "^6.2.0",
        "babel-plugin-check-es2015-constants": "^6.3.13",
        "babel-plugin-transform-es2015-arrow-functions": "^6.3.13",
        "babel-plugin-transform-es2015-block-scoped-functions": "^6.3.13",
        "babel-plugin-transform-es2015-block-scoping": "^6.3.13",
        "babel-plugin-transform-es2015-classes": "^6.3.13",
        "babel-plugin-transform-es2015-computed-properties": "^6.3.13",
        "babel-plugin-transform-es2015-destructuring": "^6.3.13",
        "babel-plugin-transform-es2015-for-of": "^6.3.13",
        "babel-plugin-transform-es2015-function-name": "^6.3.13",
        "babel-plugin-transform-es2015-literals": "^6.3.13",
        "babel-plugin-transform-es2015-modules-commonjs": "^6.3.13",
        "babel-plugin-transform-es2015-object-super": "^6.3.13",
        "babel-plugin-transform-es2015-parameters": "^6.3.13",
        "babel-plugin-transform-es2015-shorthand-properties": "^6.3.13",
        "babel-plugin-transform-es2015-spread": "^6.3.13",
        "babel-plugin-transform-es2015-sticky-regex": "^6.3.13",
        "babel-plugin-transform-es2015-template-literals": "^6.3.13",
        "babel-plugin-transform-es2015-unicode-regex": "^6.3.13",
        "babel-plugin-transform-es3-member-expression-literals": "^6.5.0",
        "babel-plugin-transform-es3-property-literals": "^6.5.0",
        "babel-plugin-transform-object-rest-spread": "^6.3.13",
        "babel-register": "^6.3.13",
        "check-es3-syntax-cli": "^0.1.1",
        "cross-env": "^1.0.7",
        "eslint": "^1.10.3",
        "eslint-config-rackt": "^1.1.1",
        "eslint-plugin-react": "^3.16.1",
        "expect": "^1.8.0",
        "gitbook-cli": "^2.3.0",
        "glob": "^6.0.4",
        "isparta": "^4.0.0",
        "mocha": "^2.2.5",
        "rimraf": "^2.3.4",
        "rxjs": "^5.0.0-beta.6",
        "typescript": "^1.8.0",
        "typescript-definition-tester": "0.0.4",
        "webpack": "^1.9.6"
    },
    "directories": {},
    "dist": {
        "shasum": "887c2b3d0b9bd86eca2be70571c27654c19e188d",
        "tarball": "https://registry.npmjs.org/redux/-/redux-3.6.0.tgz"
    },
    "files": [
        "dist",
        "lib",
        "es",
        "src",
        "index.d.ts"
    ],
    "gitHead": "3e114f8c0fd4461e2f642c2737d2fa8297484728",
    "homepage": "http://redux.js.org",
    "jsnext:main": "es/index.js",
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
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "acdlite",
            "email": "acdlite@me.com"
        },
        {
            "name": "gaearon",
            "email": "dan.abramov@gmail.com"
        },
        {
            "name": "timdorr",
            "email": "timdorr@timdorr.com"
        }
    ],
    "module": "es/index.js",
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
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/reactjs/redux.git"
    },
    "scripts": {
        "build": "npm run build:commonjs && npm run build:es && npm run build:umd && npm run build:umd:min",
        "build:commonjs": "cross-env BABEL_ENV=commonjs babel src --out-dir lib",
        "build:es": "cross-env BABEL_ENV=es babel src --out-dir es",
        "build:examples": "cross-env BABEL_ENV=commonjs babel-node examples/buildAll.js",
        "build:umd": "cross-env BABEL_ENV=commonjs NODE_ENV=development webpack src/index.js dist/redux.js",
        "build:umd:min": "cross-env BABEL_ENV=commonjs NODE_ENV=production webpack src/index.js dist/redux.min.js",
        "check:examples": "npm run build:examples && npm run lint:examples && npm run test:examples",
        "check:src": "npm run lint:src && npm run test",
        "clean": "rimraf lib dist es coverage",
        "docs:build": "npm run docs:prepare && gitbook build -g reactjs/redux && cp logo/apple-touch-icon.png _book/gitbook/images/apple-touch-icon-precomposed-152.png && cp logo/favicon.ico _book/gitbook/images",
        "docs:clean": "rimraf _book",
        "docs:prepare": "gitbook install",
        "docs:publish": "npm run docs:clean && npm run docs:build && cp CNAME _book && cd _book && git init && git commit --allow-empty -m 'update book' && git checkout -b gh-pages && touch .nojekyll && git add . && git commit -am 'update book' && git push git@github.com:reactjs/redux gh-pages --force",
        "docs:watch": "npm run docs:prepare && gitbook serve",
        "lint": "npm run lint:src && npm run lint:examples",
        "lint:examples": "eslint examples",
        "lint:src": "eslint src test build",
        "prepublish": "npm run clean && npm run check:src && npm run build && check-es3-syntax lib/ dist/ --kill --print",
        "test": "cross-env BABEL_ENV=commonjs mocha --compilers js:babel-register --recursive",
        "test:cov": "cross-env BABEL_ENV=commonjs babel-node $(npm bin)/isparta cover $(npm bin)/_mocha -- --recursive",
        "test:examples": "cross-env BABEL_ENV=commonjs babel-node examples/testAll.js",
        "test:watch": "npm test -- --watch"
    },
    "typings": "./index.d.ts",
    "version": "3.6.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module redux](#apidoc.module.redux)
1.  boolean <span class="apidocSignatureSpan">redux.</span>__esModule
1.  [function <span class="apidocSignatureSpan">redux.</span>applyMiddleware ()](#apidoc.element.redux.applyMiddleware)
1.  [function <span class="apidocSignatureSpan">redux.</span>bindActionCreators (actionCreators, dispatch)](#apidoc.element.redux.bindActionCreators)
1.  [function <span class="apidocSignatureSpan">redux.</span>combineReducers (reducers)](#apidoc.element.redux.combineReducers)
1.  [function <span class="apidocSignatureSpan">redux.</span>compose ()](#apidoc.element.redux.compose)
1.  [function <span class="apidocSignatureSpan">redux.</span>createStore (reducer, preloadedState, enhancer)](#apidoc.element.redux.createStore)

#### [module redux.applyMiddleware](#apidoc.module.redux.applyMiddleware)
1.  boolean <span class="apidocSignatureSpan">redux.applyMiddleware.</span>__esModule
1.  [function <span class="apidocSignatureSpan">redux.applyMiddleware.</span>default ()](#apidoc.element.redux.applyMiddleware.default)

#### [module redux.bindActionCreators](#apidoc.module.redux.bindActionCreators)
1.  boolean <span class="apidocSignatureSpan">redux.bindActionCreators.</span>__esModule
1.  [function <span class="apidocSignatureSpan">redux.bindActionCreators.</span>default (actionCreators, dispatch)](#apidoc.element.redux.bindActionCreators.default)

#### [module redux.combineReducers](#apidoc.module.redux.combineReducers)
1.  boolean <span class="apidocSignatureSpan">redux.combineReducers.</span>__esModule
1.  [function <span class="apidocSignatureSpan">redux.combineReducers.</span>default (reducers)](#apidoc.element.redux.combineReducers.default)

#### [module redux.compose](#apidoc.module.redux.compose)
1.  boolean <span class="apidocSignatureSpan">redux.compose.</span>__esModule
1.  [function <span class="apidocSignatureSpan">redux.compose.</span>default ()](#apidoc.element.redux.compose.default)

#### [module redux.createStore](#apidoc.module.redux.createStore)
1.  boolean <span class="apidocSignatureSpan">redux.createStore.</span>__esModule
1.  [function <span class="apidocSignatureSpan">redux.createStore.</span>default (reducer, preloadedState, enhancer)](#apidoc.element.redux.createStore.default)
1.  object <span class="apidocSignatureSpan">redux.createStore.</span>ActionTypes



# <a name="apidoc.module.redux"></a>[module redux](#apidoc.module.redux)

#### <a name="apidoc.element.redux.applyMiddleware"></a>[function <span class="apidocSignatureSpan">redux.</span>applyMiddleware ()](#apidoc.element.redux.applyMiddleware)
- description and source-code
```javascript
function applyMiddleware() {
  for (var _len = arguments.length, middlewares = Array(_len), _key = 0; _key < _len; _key++) {
    middlewares[_key] = arguments[_key];
  }

  return function (createStore) {
    return function (reducer, preloadedState, enhancer) {
      var store = createStore(reducer, preloadedState, enhancer);
      var _dispatch = store.dispatch;
      var chain = [];

      var middlewareAPI = {
        getState: store.getState,
        dispatch: function dispatch(action) {
          return _dispatch(action);
        }
      };
      chain = middlewares.map(function (middleware) {
        return middleware(middlewareAPI);
      });
      _dispatch = _compose2['default'].apply(undefined, chain)(store.dispatch);

      return _extends({}, store, {
        dispatch: _dispatch
      });
    };
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.redux.bindActionCreators"></a>[function <span class="apidocSignatureSpan">redux.</span>bindActionCreators (actionCreators, dispatch)](#apidoc.element.redux.bindActionCreators)
- description and source-code
```javascript
function bindActionCreators(actionCreators, dispatch) {
  if (typeof actionCreators === 'function') {
    return bindActionCreator(actionCreators, dispatch);
  }

  if (typeof actionCreators !== 'object' || actionCreators === null) {
    throw new Error('bindActionCreators expected an object or a function, instead received ' + (actionCreators === null ? 'null' :
typeof actionCreators) + '. ' + 'Did you write "import ActionCreators from" instead of "import * as ActionCreators from"?');
  }

  var keys = Object.keys(actionCreators);
  var boundActionCreators = {};
  for (var i = 0; i < keys.length; i++) {
    var key = keys[i];
    var actionCreator = actionCreators[key];
    if (typeof actionCreator === 'function') {
      boundActionCreators[key] = bindActionCreator(actionCreator, dispatch);
    }
  }
  return boundActionCreators;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.redux.combineReducers"></a>[function <span class="apidocSignatureSpan">redux.</span>combineReducers (reducers)](#apidoc.element.redux.combineReducers)
- description and source-code
```javascript
function combineReducers(reducers) {
  var reducerKeys = Object.keys(reducers);
  var finalReducers = {};
  for (var i = 0; i < reducerKeys.length; i++) {
    var key = reducerKeys[i];

    if (process.env.NODE_ENV !== 'production') {
      if (typeof reducers[key] === 'undefined') {
        (0, _warning2['default'])('No reducer provided for key "' + key + '"');
      }
    }

    if (typeof reducers[key] === 'function') {
      finalReducers[key] = reducers[key];
    }
  }
  var finalReducerKeys = Object.keys(finalReducers);

  if (process.env.NODE_ENV !== 'production') {
    var unexpectedKeyCache = {};
  }

  var sanityError;
  try {
    assertReducerSanity(finalReducers);
  } catch (e) {
    sanityError = e;
  }

  return function combination() {
    var state = arguments.length <= 0 || arguments[0] === undefined ? {} : arguments[0];
    var action = arguments[1];

    if (sanityError) {
      throw sanityError;
    }

    if (process.env.NODE_ENV !== 'production') {
      var warningMessage = getUnexpectedStateShapeWarningMessage(state, finalReducers, action, unexpectedKeyCache);
      if (warningMessage) {
        (0, _warning2['default'])(warningMessage);
      }
    }

    var hasChanged = false;
    var nextState = {};
    for (var i = 0; i < finalReducerKeys.length; i++) {
      var key = finalReducerKeys[i];
      var reducer = finalReducers[key];
      var previousStateForKey = state[key];
      var nextStateForKey = reducer(previousStateForKey, action);
      if (typeof nextStateForKey === 'undefined') {
        var errorMessage = getUndefinedStateErrorMessage(key, action);
        throw new Error(errorMessage);
      }
      nextState[key] = nextStateForKey;
      hasChanged = hasChanged || nextStateForKey !== previousStateForKey;
    }
    return hasChanged ? nextState : state;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.redux.compose"></a>[function <span class="apidocSignatureSpan">redux.</span>compose ()](#apidoc.element.redux.compose)
- description and source-code
```javascript
function compose() {
  for (var _len = arguments.length, funcs = Array(_len), _key = 0; _key < _len; _key++) {
    funcs[_key] = arguments[_key];
  }

  if (funcs.length === 0) {
    return function (arg) {
      return arg;
    };
  }

  if (funcs.length === 1) {
    return funcs[0];
  }

  var last = funcs[funcs.length - 1];
  var rest = funcs.slice(0, -1);
  return function () {
    return rest.reduceRight(function (composed, f) {
      return f(composed);
    }, last.apply(undefined, arguments));
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.redux.createStore"></a>[function <span class="apidocSignatureSpan">redux.</span>createStore (reducer, preloadedState, enhancer)](#apidoc.element.redux.createStore)
- description and source-code
```javascript
function createStore(reducer, preloadedState, enhancer) {
  var _ref2;

  if (typeof preloadedState === 'function' && typeof enhancer === 'undefined') {
    enhancer = preloadedState;
    preloadedState = undefined;
  }

  if (typeof enhancer !== 'undefined') {
    if (typeof enhancer !== 'function') {
      throw new Error('Expected the enhancer to be a function.');
    }

    return enhancer(createStore)(reducer, preloadedState);
  }

  if (typeof reducer !== 'function') {
    throw new Error('Expected the reducer to be a function.');
  }

  var currentReducer = reducer;
  var currentState = preloadedState;
  var currentListeners = [];
  var nextListeners = currentListeners;
  var isDispatching = false;

  function ensureCanMutateNextListeners() {
    if (nextListeners === currentListeners) {
      nextListeners = currentListeners.slice();
    }
  }

<span class="apidocCodeCommentSpan">  /**
   * Reads the state tree managed by the store.
   *
   * @returns {any} The current state tree of your application.
   */
</span>  function getState() {
    return currentState;
  }

  /**
   * Adds a change listener. It will be called any time an action is dispatched,
   * and some part of the state tree may potentially have changed. You may then
   * call 'getState()' to read the current state tree inside the callback.
   *
   * You may call 'dispatch()' from a change listener, with the following
   * caveats:
   *
   * 1. The subscriptions are snapshotted just before every 'dispatch()' call.
   * If you subscribe or unsubscribe while the listeners are being invoked, this
   * will not have any effect on the 'dispatch()' that is currently in progress.
   * However, the next 'dispatch()' call, whether nested or not, will use a more
   * recent snapshot of the subscription list.
   *
   * 2. The listener should not expect to see all state changes, as the state
   * might have been updated multiple times during a nested 'dispatch()' before
   * the listener is called. It is, however, guaranteed that all subscribers
   * registered before the 'dispatch()' started will be called with the latest
   * state by the time it exits.
   *
   * @param {Function} listener A callback to be invoked on every dispatch.
   * @returns {Function} A function to remove this change listener.
   */
  function subscribe(listener) {
    if (typeof listener !== 'function') {
      throw new Error('Expected listener to be a function.');
    }

    var isSubscribed = true;

    ensureCanMutateNextListeners();
    nextListeners.push(listener);

    return function unsubscribe() {
      if (!isSubscribed) {
        return;
      }

      isSubscribed = false;

      ensureCanMutateNextListeners();
      var index = nextListeners.indexOf(listener);
      nextListeners.splice(index, 1);
    };
  }

  /**
   * Dispatches an action. It is the only way to trigger a state change.
   *
   * The 'reducer' function, used to create the store, will be called with the
   * current state tree and the given 'action'. Its return value will
   * be considered the **next** state of the tree, and the change listeners
   * will be notified.
   *
   * The base implementation only supports plain object actions. If you want to
   * dispatch a Promise, an Observable, a thunk, or something else, you need to
   * wrap your store creating function into the corresponding middleware. For
   * example, see the documentation for the 'redux-thunk' package. Even the
   * middleware will eventually dispatch plain object actions using this method.
   *
   * @param {Object} action A plain object representing “what changed”. It is
   * a good idea to keep actions serializable so you can record and replay user
   * sessions, or use the time travelling 'redux-devtools'. An action must have
   * a 'type' property which may not be 'undefined'. It is a good idea to use
   * string constants for action types.
   *
   * @returns {Object} For convenience, the same action object you dispatched.
   *
   * Note that, if you use a custom middleware, it may wrap 'dispatch()' to
   * return something else (for example, a Promise you can await).
   */ ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.redux.applyMiddleware"></a>[module redux.applyMiddleware](#apidoc.module.redux.applyMiddleware)

#### <a name="apidoc.element.redux.applyMiddleware.default"></a>[function <span class="apidocSignatureSpan">redux.applyMiddleware.</span>default ()](#apidoc.element.redux.applyMiddleware.default)
- description and source-code
```javascript
function applyMiddleware() {
  for (var _len = arguments.length, middlewares = Array(_len), _key = 0; _key < _len; _key++) {
    middlewares[_key] = arguments[_key];
  }

  return function (createStore) {
    return function (reducer, preloadedState, enhancer) {
      var store = createStore(reducer, preloadedState, enhancer);
      var _dispatch = store.dispatch;
      var chain = [];

      var middlewareAPI = {
        getState: store.getState,
        dispatch: function dispatch(action) {
          return _dispatch(action);
        }
      };
      chain = middlewares.map(function (middleware) {
        return middleware(middlewareAPI);
      });
      _dispatch = _compose2['default'].apply(undefined, chain)(store.dispatch);

      return _extends({}, store, {
        dispatch: _dispatch
      });
    };
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.redux.bindActionCreators"></a>[module redux.bindActionCreators](#apidoc.module.redux.bindActionCreators)

#### <a name="apidoc.element.redux.bindActionCreators.default"></a>[function <span class="apidocSignatureSpan">redux.bindActionCreators.</span>default (actionCreators, dispatch)](#apidoc.element.redux.bindActionCreators.default)
- description and source-code
```javascript
function bindActionCreators(actionCreators, dispatch) {
  if (typeof actionCreators === 'function') {
    return bindActionCreator(actionCreators, dispatch);
  }

  if (typeof actionCreators !== 'object' || actionCreators === null) {
    throw new Error('bindActionCreators expected an object or a function, instead received ' + (actionCreators === null ? 'null' :
typeof actionCreators) + '. ' + 'Did you write "import ActionCreators from" instead of "import * as ActionCreators from"?');
  }

  var keys = Object.keys(actionCreators);
  var boundActionCreators = {};
  for (var i = 0; i < keys.length; i++) {
    var key = keys[i];
    var actionCreator = actionCreators[key];
    if (typeof actionCreator === 'function') {
      boundActionCreators[key] = bindActionCreator(actionCreator, dispatch);
    }
  }
  return boundActionCreators;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.redux.combineReducers"></a>[module redux.combineReducers](#apidoc.module.redux.combineReducers)

#### <a name="apidoc.element.redux.combineReducers.default"></a>[function <span class="apidocSignatureSpan">redux.combineReducers.</span>default (reducers)](#apidoc.element.redux.combineReducers.default)
- description and source-code
```javascript
function combineReducers(reducers) {
  var reducerKeys = Object.keys(reducers);
  var finalReducers = {};
  for (var i = 0; i < reducerKeys.length; i++) {
    var key = reducerKeys[i];

    if (process.env.NODE_ENV !== 'production') {
      if (typeof reducers[key] === 'undefined') {
        (0, _warning2['default'])('No reducer provided for key "' + key + '"');
      }
    }

    if (typeof reducers[key] === 'function') {
      finalReducers[key] = reducers[key];
    }
  }
  var finalReducerKeys = Object.keys(finalReducers);

  if (process.env.NODE_ENV !== 'production') {
    var unexpectedKeyCache = {};
  }

  var sanityError;
  try {
    assertReducerSanity(finalReducers);
  } catch (e) {
    sanityError = e;
  }

  return function combination() {
    var state = arguments.length <= 0 || arguments[0] === undefined ? {} : arguments[0];
    var action = arguments[1];

    if (sanityError) {
      throw sanityError;
    }

    if (process.env.NODE_ENV !== 'production') {
      var warningMessage = getUnexpectedStateShapeWarningMessage(state, finalReducers, action, unexpectedKeyCache);
      if (warningMessage) {
        (0, _warning2['default'])(warningMessage);
      }
    }

    var hasChanged = false;
    var nextState = {};
    for (var i = 0; i < finalReducerKeys.length; i++) {
      var key = finalReducerKeys[i];
      var reducer = finalReducers[key];
      var previousStateForKey = state[key];
      var nextStateForKey = reducer(previousStateForKey, action);
      if (typeof nextStateForKey === 'undefined') {
        var errorMessage = getUndefinedStateErrorMessage(key, action);
        throw new Error(errorMessage);
      }
      nextState[key] = nextStateForKey;
      hasChanged = hasChanged || nextStateForKey !== previousStateForKey;
    }
    return hasChanged ? nextState : state;
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.redux.compose"></a>[module redux.compose](#apidoc.module.redux.compose)

#### <a name="apidoc.element.redux.compose.default"></a>[function <span class="apidocSignatureSpan">redux.compose.</span>default ()](#apidoc.element.redux.compose.default)
- description and source-code
```javascript
function compose() {
  for (var _len = arguments.length, funcs = Array(_len), _key = 0; _key < _len; _key++) {
    funcs[_key] = arguments[_key];
  }

  if (funcs.length === 0) {
    return function (arg) {
      return arg;
    };
  }

  if (funcs.length === 1) {
    return funcs[0];
  }

  var last = funcs[funcs.length - 1];
  var rest = funcs.slice(0, -1);
  return function () {
    return rest.reduceRight(function (composed, f) {
      return f(composed);
    }, last.apply(undefined, arguments));
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.redux.createStore"></a>[module redux.createStore](#apidoc.module.redux.createStore)

#### <a name="apidoc.element.redux.createStore.default"></a>[function <span class="apidocSignatureSpan">redux.createStore.</span>default (reducer, preloadedState, enhancer)](#apidoc.element.redux.createStore.default)
- description and source-code
```javascript
function createStore(reducer, preloadedState, enhancer) {
  var _ref2;

  if (typeof preloadedState === 'function' && typeof enhancer === 'undefined') {
    enhancer = preloadedState;
    preloadedState = undefined;
  }

  if (typeof enhancer !== 'undefined') {
    if (typeof enhancer !== 'function') {
      throw new Error('Expected the enhancer to be a function.');
    }

    return enhancer(createStore)(reducer, preloadedState);
  }

  if (typeof reducer !== 'function') {
    throw new Error('Expected the reducer to be a function.');
  }

  var currentReducer = reducer;
  var currentState = preloadedState;
  var currentListeners = [];
  var nextListeners = currentListeners;
  var isDispatching = false;

  function ensureCanMutateNextListeners() {
    if (nextListeners === currentListeners) {
      nextListeners = currentListeners.slice();
    }
  }

<span class="apidocCodeCommentSpan">  /**
   * Reads the state tree managed by the store.
   *
   * @returns {any} The current state tree of your application.
   */
</span>  function getState() {
    return currentState;
  }

  /**
   * Adds a change listener. It will be called any time an action is dispatched,
   * and some part of the state tree may potentially have changed. You may then
   * call 'getState()' to read the current state tree inside the callback.
   *
   * You may call 'dispatch()' from a change listener, with the following
   * caveats:
   *
   * 1. The subscriptions are snapshotted just before every 'dispatch()' call.
   * If you subscribe or unsubscribe while the listeners are being invoked, this
   * will not have any effect on the 'dispatch()' that is currently in progress.
   * However, the next 'dispatch()' call, whether nested or not, will use a more
   * recent snapshot of the subscription list.
   *
   * 2. The listener should not expect to see all state changes, as the state
   * might have been updated multiple times during a nested 'dispatch()' before
   * the listener is called. It is, however, guaranteed that all subscribers
   * registered before the 'dispatch()' started will be called with the latest
   * state by the time it exits.
   *
   * @param {Function} listener A callback to be invoked on every dispatch.
   * @returns {Function} A function to remove this change listener.
   */
  function subscribe(listener) {
    if (typeof listener !== 'function') {
      throw new Error('Expected listener to be a function.');
    }

    var isSubscribed = true;

    ensureCanMutateNextListeners();
    nextListeners.push(listener);

    return function unsubscribe() {
      if (!isSubscribed) {
        return;
      }

      isSubscribed = false;

      ensureCanMutateNextListeners();
      var index = nextListeners.indexOf(listener);
      nextListeners.splice(index, 1);
    };
  }

  /**
   * Dispatches an action. It is the only way to trigger a state change.
   *
   * The 'reducer' function, used to create the store, will be called with the
   * current state tree and the given 'action'. Its return value will
   * be considered the **next** state of the tree, and the change listeners
   * will be notified.
   *
   * The base implementation only supports plain object actions. If you want to
   * dispatch a Promise, an Observable, a thunk, or something else, you need to
   * wrap your store creating function into the corresponding middleware. For
   * example, see the documentation for the 'redux-thunk' package. Even the
   * middleware will eventually dispatch plain object actions using this method.
   *
   * @param {Object} action A plain object representing “what changed”. It is
   * a good idea to keep actions serializable so you can record and replay user
   * sessions, or use the time travelling 'redux-devtools'. An action must have
   * a 'type' property which may not be 'undefined'. It is a good idea to use
   * string constants for action types.
   *
   * @returns {Object} For convenience, the same action object you dispatched.
   *
   * Note that, if you use a custom middleware, it may wrap 'dispatch()' to
   * return something else (for example, a Promise you can await).
   */ ...
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
