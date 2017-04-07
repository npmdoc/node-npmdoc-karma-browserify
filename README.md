# api documentation for  [karma-browserify (v5.1.1)](https://github.com/nikku/karma-browserify#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-karma-browserify.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-karma-browserify) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-karma-browserify.svg)](https://travis-ci.org/npmdoc/node-npmdoc-karma-browserify)
#### A fast browserify integration for Karma that handles large projects with ease

[![NPM](https://nodei.co/npm/karma-browserify.png?downloads=true)](https://www.npmjs.com/package/karma-browserify)

[![apidoc](https://npmdoc.github.io/node-npmdoc-karma-browserify/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-karma-browserify_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-karma-browserify/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-karma-browserify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-karma-browserify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "Nico Rehwaldt <git_nikku@nixis.de>",
        "Ben Drucker <bvdrucker@gmail.com>"
    ],
    "bugs": {
        "url": "https://github.com/nikku/karma-browserify/issues"
    },
    "dependencies": {
        "convert-source-map": "^1.1.3",
        "hat": "^0.0.3",
        "js-string-escape": "^1.0.0",
        "lodash": "^3.10.1",
        "minimatch": "^3.0.0",
        "os-shim": "^0.1.3"
    },
    "description": "A fast browserify integration for Karma that handles large projects with ease",
    "devDependencies": {
        "brfs": "^1.4.2",
        "browser-unpack": "^1.1.1",
        "browserify": "^14.0.0",
        "chai": "^3.4.1",
        "chai-spies": "^0.7.1",
        "grunt": "~1.0.1",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-jshint": "^0.11.3",
        "grunt-mocha-test": "^0.12.7",
        "grunt-release": "^0.13.0",
        "jasmine-core": "^2.4.1",
        "karma": "^0.13.19",
        "karma-jasmine": "^0.3.6",
        "karma-phantomjs-launcher": "^0.2.3",
        "load-grunt-tasks": "^3.4.0",
        "mocha": "^2.3.4",
        "phantomjs": "^1.9.19",
        "resolve": "^1.1.6",
        "touch": "^1.0.0",
        "tsify": "^0.13.1",
        "watchify": "^3.6.1"
    },
    "directories": {},
    "dist": {
        "shasum": "f642d70d776d9ab3b73526c5732abcfea2400319",
        "tarball": "https://registry.npmjs.org/karma-browserify/-/karma-browserify-5.1.1.tgz"
    },
    "engines": {
        "node": ">=0.12",
        "npm": ">=2"
    },
    "gitHead": "e42a5bed7700dff68bba4b7e66dedba8f321fea1",
    "homepage": "https://github.com/nikku/karma-browserify#readme",
    "keywords": [
        "karma-plugin",
        "karma-preprocessor",
        "browserify-tool",
        "browserify"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "xdissent",
            "email": "xdissent@me.com"
        },
        {
            "name": "alexgorbatchev",
            "email": "alex.gorbatchev@gmail.com"
        },
        {
            "name": "nikku",
            "email": "git_nikku@nixis.de"
        },
        {
            "name": "bendrucker",
            "email": "bvdrucker@gmail.com"
        }
    ],
    "name": "karma-browserify",
    "optionalDependencies": {},
    "peerDependencies": {
        "karma": ">=0.10.0",
        "browserify": ">=10 <15",
        "watchify": ">=3 <4"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/nikku/karma-browserify.git"
    },
    "scripts": {
        "all": "grunt",
        "test": "grunt test"
    },
    "version": "5.1.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module karma-browserify](#apidoc.module.karma-browserify)
1.  [function <span class="apidocSignatureSpan">karma-browserify.</span>bundle_file ()](#apidoc.element.karma-browserify.bundle_file)
1.  object <span class="apidocSignatureSpan">karma-browserify.</span>bro
1.  object <span class="apidocSignatureSpan">karma-browserify.</span>preprocess
1.  object <span class="apidocSignatureSpan">karma-browserify.</span>preprocessor

#### [module karma-browserify.bro](#apidoc.module.karma-browserify.bro)
1.  [function <span class="apidocSignatureSpan">karma-browserify.bro.</span>1 (bundleFile)](#apidoc.element.karma-browserify.bro.1)
1.  string <span class="apidocSignatureSpan">karma-browserify.bro.</span>0

#### [module karma-browserify.bundle_file](#apidoc.module.karma-browserify.bundle_file)
1.  [function <span class="apidocSignatureSpan">karma-browserify.</span>bundle_file ()](#apidoc.element.karma-browserify.bundle_file.bundle_file)
1.  [function <span class="apidocSignatureSpan">karma-browserify.bundle_file.</span>getTempFileName (suffix)](#apidoc.element.karma-browserify.bundle_file.getTempFileName)

#### [module karma-browserify.preprocess](#apidoc.module.karma-browserify.preprocess)
1.  [function <span class="apidocSignatureSpan">karma-browserify.preprocess.</span>1 (config, basePath, injector)](#apidoc.element.karma-browserify.preprocess.1)
1.  string <span class="apidocSignatureSpan">karma-browserify.preprocess.</span>0

#### [module karma-browserify.preprocessor](#apidoc.module.karma-browserify.preprocessor)
1.  [function <span class="apidocSignatureSpan">karma-browserify.preprocessor.</span>createPreprocessor (config, basePath, injector)](#apidoc.element.karma-browserify.preprocessor.createPreprocessor)



# <a name="apidoc.module.karma-browserify"></a>[module karma-browserify](#apidoc.module.karma-browserify)

#### <a name="apidoc.element.karma-browserify.bundle_file"></a>[function <span class="apidocSignatureSpan">karma-browserify.</span>bundle_file ()](#apidoc.element.karma-browserify.bundle_file)
- description and source-code
```javascript
function BundleFile() {

  var location = getTempFileName('.browserify');

  function write(content) {
    fs.writeFileSync(location, content);
  }

  function exists() {
    return fs.existsSync(location);
  }

  function remove() {
    if (exists()) {
      fs.unlinkSync(location);
    }
  }

  function touch() {
    if (!exists()) {
      write('');
    }
  }


  // API

  this.touch = touch;

  this.update = write;
  this.remove = remove;

  this.location = location;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma-browserify.bro"></a>[module karma-browserify.bro](#apidoc.module.karma-browserify.bro)

#### <a name="apidoc.element.karma-browserify.bro.1"></a>[function <span class="apidocSignatureSpan">karma-browserify.bro.</span>1 (bundleFile)](#apidoc.element.karma-browserify.bro.1)
- description and source-code
```javascript
function Bro(bundleFile) {

  var log;

<span class="apidocCodeCommentSpan">  /**
   * Add bundle file to the list of files in the
   * configuration, right before the first browserified
   * test file and after everything else.
   *
   * That makes sure users can include non-commonJS files
   * prior to the browserified bundle.
   *
   * @param {BundleFile} bundleFile the file containing the browserify bundle
   * @param {Object} config the karma configuration to be updated
   */
</span>  function addBundleFile(bundleFile, config) {

    var files = config.files,
        preprocessors = config.preprocessors;

    // list of patterns using our preprocessor
    var patterns = reduce(preprocessors, function(matched, val, key) {
      if (val.indexOf('browserify') !== -1) {
        matched.push(key);
      }
      return matched;
    }, []);

    // first file being preprocessed
    var file = find(files, function(f) {
      return any(patterns, function(p) {
        return minimatch(f.pattern, p);
      });
    });

    var idx = 0;

    if (file) {
      idx = files.indexOf(file);
    } else {
      log.debug('no matching preprocessed file was found, defaulting to prepend');
    }

    log.debug('add bundle to config.files at position', idx);

    // insert bundle on the correct spot
    files.splice(idx, 0, {
      pattern: bundleFile.location,
      served: true,
      included: true,
      watched: true
    });
  }


  /**
   * The browserify instance that creates the
   * minified bundle and gets added all test files to it.
   */
  var b;


  /**
   * The browserify framework that creates the initial logger and bundle file
   * as well as prepends the bundle file to the karma file configuration.
   */
  function framework(emitter, config, logger) {

    log = logger.create('framework.browserify');

    if (!bundleFile) {
      bundleFile = new BundleFile();
    }

    bundleFile.touch();
    log.debug('created browserify bundle: %s', bundleFile.location);

    b = createBundle(config);

    // TODO(Nikku): hook into karma karmas file update facilities
    // to remove files from the bundle once karma detects the deletion

    // hook into exit for cleanup
    emitter.on('exit', function(done) {
      log.debug('cleaning up');

      if (b.close) {
        b.close();
      }

      bundleFile.remove();
      done();
    });


    // add bundle file to the list of files defined in the
    // configuration. be smart by doing so.
    addBundleFile(bundleFile, config);

    return b;
  }

  framework.$inject = [ 'emitter', 'config', 'logger' ];


  /**
   * Create the browserify bundle
   */
  function createBundle(config) {

    var bopts = config.browserify || {},
        bundleDelay = bopts.bundleDelay || DEFAULT_BUNDLE_DELAY,
        requireName = bopts.externalRequireName || 'require';

    function warn(key) {
      log.warn('Invalid config option: "' + key + 's" should be "' + key + '"');
    }

    forEach([ 'transform', 'plugin' ], function(key) {
      if (bopts[key + 's']) {
        warn(key);
      }
    });

    var browserifyOptions = assign({
      basedir: path.resolve(config.basePath),
      // watchify.args
      cache: {},
      packageCache: {}
    }, omit(bopts, [
      'transform', 'plugin', 'configure', 'bundleDelay'
    ]));

    if ('prebundle' in browserifyOptions) {
      log.warn('The prebundle hook got removed in favor of configure');
    }

    if ('watchify' in browserifyOptions) {
      log.warn('Configure watchify via config.watchify');
    }

    var w = browserify(browserifyOptions);
    w.setMaxListeners(Infinity);

    forEach(bopts.plugin, function(p) {
      // ensure we can pass plugin options as
      // the first parameter
      if (!Array.isArray(p)) {
        p = [ p ];
      }
      w.plugin.apply(w, p);
    });

    forEach(bopts.transform, function(t) {
      // ensure we can pass transform options as
      // the first parameter
      if (!Array.isArray(t)) {
        t = [ t ];
      }
      w.transform.apply(w, t);
    });

    // test if we have a configure function
    if (bopts.configure && typeof bopts.configure ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma-browserify.bundle_file"></a>[module karma-browserify.bundle_file](#apidoc.module.karma-browserify.bundle_file)

#### <a name="apidoc.element.karma-browserify.bundle_file.bundle_file"></a>[function <span class="apidocSignatureSpan">karma-browserify.</span>bundle_file ()](#apidoc.element.karma-browserify.bundle_file.bundle_file)
- description and source-code
```javascript
function BundleFile() {

  var location = getTempFileName('.browserify');

  function write(content) {
    fs.writeFileSync(location, content);
  }

  function exists() {
    return fs.existsSync(location);
  }

  function remove() {
    if (exists()) {
      fs.unlinkSync(location);
    }
  }

  function touch() {
    if (!exists()) {
      write('');
    }
  }


  // API

  this.touch = touch;

  this.update = write;
  this.remove = remove;

  this.location = location;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.karma-browserify.bundle_file.getTempFileName"></a>[function <span class="apidocSignatureSpan">karma-browserify.bundle_file.</span>getTempFileName (suffix)](#apidoc.element.karma-browserify.bundle_file.getTempFileName)
- description and source-code
```javascript
function getTempFileName(suffix) {
  return path.join(os.tmpdir(), hat() + suffix);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma-browserify.preprocess"></a>[module karma-browserify.preprocess](#apidoc.module.karma-browserify.preprocess)

#### <a name="apidoc.element.karma-browserify.preprocess.1"></a>[function <span class="apidocSignatureSpan">karma-browserify.preprocess.</span>1 (config, basePath, injector)](#apidoc.element.karma-browserify.preprocess.1)
- description and source-code
```javascript
1 = function (config, basePath, injector) {

  // add our preprocessor for .browserify files
  config[path.resolve(os.tmpdir(), '*.browserify')] = ['browserify-bundle'];

  return originalFactory(config, basePath, injector);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.karma-browserify.preprocessor"></a>[module karma-browserify.preprocessor](#apidoc.module.karma-browserify.preprocessor)

#### <a name="apidoc.element.karma-browserify.preprocessor.createPreprocessor"></a>[function <span class="apidocSignatureSpan">karma-browserify.preprocessor.</span>createPreprocessor (config, basePath, injector)](#apidoc.element.karma-browserify.preprocessor.createPreprocessor)
- description and source-code
```javascript
createPreprocessor = function (config, basePath, injector) {

  // add our preprocessor for .browserify files
  config[path.resolve(os.tmpdir(), '*.browserify')] = ['browserify-bundle'];

  return originalFactory(config, basePath, injector);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
