# api documentation for  [github (v9.2.0)](https://github.com/mikedeboer/node-github)  [![npm package](https://img.shields.io/npm/v/npmdoc-github.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-github) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-github.svg)](https://travis-ci.org/npmdoc/node-npmdoc-github)
#### NodeJS wrapper for the GitHub API

[![NPM](https://nodei.co/npm/github.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/github)

[![apidoc](https://npmdoc.github.io/node-npmdoc-github/build/screenCapture.buildCi.browser.apidoc.html.png)](https://npmdoc.github.io/node-npmdoc-github/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-github/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-github/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "apidoc": {
        "title": "node-github",
        "name": "node-github",
        "version": "9.2.0",
        "template": {
            "withCompare": true
        }
    },
    "author": {
        "name": "Mike de Boer"
    },
    "bugs": {
        "url": "https://github.com/mikedeboer/node-github/issues"
    },
    "contributors": [
        {
            "name": "Mike de Boer"
        },
        {
            "name": "Fabian Jakobs"
        },
        {
            "name": "Joe Gallo"
        }
    ],
    "dependencies": {
        "follow-redirects": "0.0.7",
        "https-proxy-agent": "^1.0.0",
        "mime": "^1.2.11",
        "netrc": "^0.1.4"
    },
    "description": "NodeJS wrapper for the GitHub API",
    "devDependencies": {
        "mocha": "~1.13.0",
        "mustache": "^2.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "8a886dc40dd63636707dcaf99df3df26c59f16fc",
        "tarball": "https://registry.npmjs.org/github/-/github-9.2.0.tgz"
    },
    "engine": {
        "node": ">=0.4.0"
    },
    "gitHead": "a12475607a308c4febeac5c8545fbef216b1591d",
    "homepage": "https://github.com/mikedeboer/node-github",
    "license": "MIT",
    "licenses": [
        {
            "type": "The MIT License",
            "url": "http://www.opensource.org/licenses/mit-license.php"
        }
    ],
    "main": "lib",
    "maintainers": [
        {
            "name": "kaizensoze"
        },
        {
            "name": "mikedeboer"
        }
    ],
    "name": "github",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mikedeboer/node-github.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "types": "lib/index.d.ts",
    "version": "9.2.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module github](#apidoc.module.github)
1.  [function <span class="apidocSignatureSpan"></span>github (config)](#apidoc.element.github.github)
1.  [function <span class="apidocSignatureSpan">github.</span>toString ()](#apidoc.element.github.toString)



# <a name="apidoc.module.github"></a>[module github](#apidoc.module.github)

#### <a name="apidoc.element.github.github"></a>[function <span class="apidocSignatureSpan"></span>github (config)](#apidoc.element.github.github)
- description and source-code
```javascript
github = function (config) {
    if (!(this instanceof Client)) {
        return new Client(config);
    }

    config = config || {}
    config.headers = config.headers || {};
    this.config = config;
    this.debug = Util.isTrue(config.debug);
    this.Promise = config.Promise || config.promise || Promise;

    this.routes = JSON.parse(fs.readFileSync(__dirname + "/routes.json", "utf8"));

    var pathPrefix = "";
    // Check if a prefix is passed in the config and strip any leading or trailing slashes from it.
    if (typeof config.pathPrefix == "string") {
        pathPrefix = "/" + config.pathPrefix.replace(/(^[\/]+|[\/]+$)/g, "");
        this.config.pathPrefix = pathPrefix;
    }

    // store mapping of accept header to preview api endpoints
    var mediaHash  = this.routes.defines.acceptTree;
    var mediaTypes = {};

    for (var accept in mediaHash) {
        for (var route in mediaHash[accept]) {
            mediaTypes[mediaHash[accept][route]] = accept;
        }
    }

    this.acceptUrls = mediaTypes;

    this.setupRoutes();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.toString"></a>[function <span class="apidocSignatureSpan">github.</span>toString ()](#apidoc.element.github.toString)
- description and source-code
```javascript
toString = function () {
    return toString;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
