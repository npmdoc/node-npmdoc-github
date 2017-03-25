# api documentation for  [github (v9.2.0)](https://github.com/mikedeboer/node-github)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-github.svg)](https://travis-ci.org/npmdoc/node-npmdoc-github)
#### NodeJS wrapper for the GitHub API

[![NPM](https://nodei.co/npm/github.png?downloads=true)](https://www.npmjs.com/package/github)

[![apidoc](https://npmdoc.github.io/node-npmdoc-github/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-github_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-github/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-github/build/screen-capture.npmPackageListing.svg)



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
        "name": "Mike de Boer",
        "email": "info@mikedeboer.nl"
    },
    "bugs": {
        "url": "https://github.com/mikedeboer/node-github/issues"
    },
    "contributors": [
        {
            "name": "Mike de Boer",
            "email": "info@mikedeboer.nl"
        },
        {
            "name": "Fabian Jakobs",
            "email": "fabian@c9.io"
        },
        {
            "name": "Joe Gallo",
            "email": "joe@brassafrax.com"
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
            "name": "kaizensoze",
            "email": "joe@brassafrax.com"
        },
        {
            "name": "mikedeboer",
            "email": "info@mikedeboer.nl"
        }
    ],
    "name": "github",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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
1.  object <span class="apidocSignatureSpan">github.</span>error
1.  object <span class="apidocSignatureSpan">github.</span>util

#### [module github.error](#apidoc.module.github.error)
1.  [function <span class="apidocSignatureSpan">github.error.</span>400 (msg)](#apidoc.element.github.error.400)
1.  [function <span class="apidocSignatureSpan">github.error.</span>401 (msg)](#apidoc.element.github.error.401)
1.  [function <span class="apidocSignatureSpan">github.error.</span>402 (msg)](#apidoc.element.github.error.402)
1.  [function <span class="apidocSignatureSpan">github.error.</span>403 (msg)](#apidoc.element.github.error.403)
1.  [function <span class="apidocSignatureSpan">github.error.</span>404 (msg)](#apidoc.element.github.error.404)
1.  [function <span class="apidocSignatureSpan">github.error.</span>405 (msg)](#apidoc.element.github.error.405)
1.  [function <span class="apidocSignatureSpan">github.error.</span>406 (msg)](#apidoc.element.github.error.406)
1.  [function <span class="apidocSignatureSpan">github.error.</span>407 (msg)](#apidoc.element.github.error.407)
1.  [function <span class="apidocSignatureSpan">github.error.</span>408 (msg)](#apidoc.element.github.error.408)
1.  [function <span class="apidocSignatureSpan">github.error.</span>409 (msg)](#apidoc.element.github.error.409)
1.  [function <span class="apidocSignatureSpan">github.error.</span>410 (msg)](#apidoc.element.github.error.410)
1.  [function <span class="apidocSignatureSpan">github.error.</span>411 (msg)](#apidoc.element.github.error.411)
1.  [function <span class="apidocSignatureSpan">github.error.</span>412 (msg)](#apidoc.element.github.error.412)
1.  [function <span class="apidocSignatureSpan">github.error.</span>413 (msg)](#apidoc.element.github.error.413)
1.  [function <span class="apidocSignatureSpan">github.error.</span>414 (msg)](#apidoc.element.github.error.414)
1.  [function <span class="apidocSignatureSpan">github.error.</span>415 (msg)](#apidoc.element.github.error.415)
1.  [function <span class="apidocSignatureSpan">github.error.</span>416 (msg)](#apidoc.element.github.error.416)
1.  [function <span class="apidocSignatureSpan">github.error.</span>417 (msg)](#apidoc.element.github.error.417)
1.  [function <span class="apidocSignatureSpan">github.error.</span>420 (msg)](#apidoc.element.github.error.420)
1.  [function <span class="apidocSignatureSpan">github.error.</span>422 (msg)](#apidoc.element.github.error.422)
1.  [function <span class="apidocSignatureSpan">github.error.</span>423 (msg)](#apidoc.element.github.error.423)
1.  [function <span class="apidocSignatureSpan">github.error.</span>424 (msg)](#apidoc.element.github.error.424)
1.  [function <span class="apidocSignatureSpan">github.error.</span>425 (msg)](#apidoc.element.github.error.425)
1.  [function <span class="apidocSignatureSpan">github.error.</span>426 (msg)](#apidoc.element.github.error.426)
1.  [function <span class="apidocSignatureSpan">github.error.</span>428 (msg)](#apidoc.element.github.error.428)
1.  [function <span class="apidocSignatureSpan">github.error.</span>429 (msg)](#apidoc.element.github.error.429)
1.  [function <span class="apidocSignatureSpan">github.error.</span>431 (msg)](#apidoc.element.github.error.431)
1.  [function <span class="apidocSignatureSpan">github.error.</span>444 (msg)](#apidoc.element.github.error.444)
1.  [function <span class="apidocSignatureSpan">github.error.</span>449 (msg)](#apidoc.element.github.error.449)
1.  [function <span class="apidocSignatureSpan">github.error.</span>499 (msg)](#apidoc.element.github.error.499)
1.  [function <span class="apidocSignatureSpan">github.error.</span>500 (msg)](#apidoc.element.github.error.500)
1.  [function <span class="apidocSignatureSpan">github.error.</span>501 (msg)](#apidoc.element.github.error.501)
1.  [function <span class="apidocSignatureSpan">github.error.</span>502 (msg)](#apidoc.element.github.error.502)
1.  [function <span class="apidocSignatureSpan">github.error.</span>503 (msg)](#apidoc.element.github.error.503)
1.  [function <span class="apidocSignatureSpan">github.error.</span>504 (msg)](#apidoc.element.github.error.504)
1.  [function <span class="apidocSignatureSpan">github.error.</span>505 (msg)](#apidoc.element.github.error.505)
1.  [function <span class="apidocSignatureSpan">github.error.</span>506 (msg)](#apidoc.element.github.error.506)
1.  [function <span class="apidocSignatureSpan">github.error.</span>507 (msg)](#apidoc.element.github.error.507)
1.  [function <span class="apidocSignatureSpan">github.error.</span>508 (msg)](#apidoc.element.github.error.508)
1.  [function <span class="apidocSignatureSpan">github.error.</span>509 (msg)](#apidoc.element.github.error.509)
1.  [function <span class="apidocSignatureSpan">github.error.</span>510 (msg)](#apidoc.element.github.error.510)
1.  [function <span class="apidocSignatureSpan">github.error.</span>511 (msg)](#apidoc.element.github.error.511)
1.  [function <span class="apidocSignatureSpan">github.error.</span>BadGateway (msg)](#apidoc.element.github.error.BadGateway)
1.  [function <span class="apidocSignatureSpan">github.error.</span>BadRequest (msg)](#apidoc.element.github.error.BadRequest)
1.  [function <span class="apidocSignatureSpan">github.error.</span>BandwidthLimitExceeded (msg)](#apidoc.element.github.error.BandwidthLimitExceeded)
1.  [function <span class="apidocSignatureSpan">github.error.</span>ClientClosedRequest (msg)](#apidoc.element.github.error.ClientClosedRequest)
1.  [function <span class="apidocSignatureSpan">github.error.</span>Conflict (msg)](#apidoc.element.github.error.Conflict)
1.  [function <span class="apidocSignatureSpan">github.error.</span>EnhanceYourCalm (msg)](#apidoc.element.github.error.EnhanceYourCalm)
1.  [function <span class="apidocSignatureSpan">github.error.</span>ExpectationFailed (msg)](#apidoc.element.github.error.ExpectationFailed)
1.  [function <span class="apidocSignatureSpan">github.error.</span>FailedDependency (msg)](#apidoc.element.github.error.FailedDependency)
1.  [function <span class="apidocSignatureSpan">github.error.</span>Forbidden (msg)](#apidoc.element.github.error.Forbidden)
1.  [function <span class="apidocSignatureSpan">github.error.</span>GatewayTimeout (msg)](#apidoc.element.github.error.GatewayTimeout)
1.  [function <span class="apidocSignatureSpan">github.error.</span>Gone (msg)](#apidoc.element.github.error.Gone)
1.  [function <span class="apidocSignatureSpan">github.error.</span>HttpError (message, code, headers)](#apidoc.element.github.error.HttpError)
1.  [function <span class="apidocSignatureSpan">github.error.</span>HttpVersionNotSupported (msg)](#apidoc.element.github.error.HttpVersionNotSupported)
1.  [function <span class="apidocSignatureSpan">github.error.</span>InsufficientStorage (msg)](#apidoc.element.github.error.InsufficientStorage)
1.  [function <span class="apidocSignatureSpan">github.error.</span>InternalServerError (msg)](#apidoc.element.github.error.InternalServerError)
1.  [function <span class="apidocSignatureSpan">github.error.</span>LengthRequired (msg)](#apidoc.element.github.error.LengthRequired)
1.  [function <span class="apidocSignatureSpan">github.error.</span>Locked (msg)](#apidoc.element.github.error.Locked)
1.  [function <span class="apidocSignatureSpan">github.error.</span>LoopDetected (msg)](#apidoc.element.github.error.LoopDetected)
1.  [function <span class="apidocSignatureSpan">github.error.</span>MethodNotAllowed (msg)](#apidoc.element.github.error.MethodNotAllowed)
1.  [function <span class="apidocSignatureSpan">github.error.</span>NetworkAuthenticationRequired (msg)](#apidoc.element.github.error.NetworkAuthenticationRequired)
1.  [function <span class="apidocSignatureSpan">github.error.</span>NoResponse (msg)](#apidoc.element.github.error.NoResponse)
1.  [function <span class="apidocSignatureSpan">github.error.</span>NotAcceptable (msg)](#apidoc.element.github.error.NotAcceptable)
1.  [function <span class="apidocSignatureSpan">github.error.</span>NotExtended (msg)](#apidoc.element.github.error.NotExtended)
1.  [function <span class="apidocSignatureSpan">github.error.</span>NotFound (msg)](#apidoc.element.github.error.NotFound)
1.  [function <span class="apidocSignatureSpan">github.error.</span>NotImplemented (msg)](#apidoc.element.github.error.NotImplemented)
1.  [function <span class="apidocSignatureSpan">github.error.</span>PaymentRequired (msg)](#apidoc.element.github.error.PaymentRequired)
1.  [function <span class="apidocSignatureSpan">github.error.</span>PreconditionFailed (msg)](#apidoc.element.github.error.PreconditionFailed)
1.  [function <span class="apidocSignatureSpan">github.error.</span>PreconditionRequired (msg)](#apidoc.element.github.error.PreconditionRequired)
1.  [function <span class="apidocSignatureSpan">github.error.</span>ProxyAuthenticationRequired (msg)](#apidoc.element.github.error.ProxyAuthenticationRequired)
1.  [function <span class="apidocSignatureSpan">github.error.</span>Request-uriTooLong (msg)](#apidoc.element.github.error.Request-uriTooLong)
1.  [function <span class="apidocSignatureSpan">github.error.</span>RequestEntityTooLarge (msg)](#apidoc.element.github.error.RequestEntityTooLarge)
1.  [function <span class="apidocSignatureSpan">github.error.</span>RequestHeaderFieldsTooLarge (msg)](#apidoc.element.github.error.RequestHeaderFieldsTooLarge)
1.  [function <span class="apidocSignatureSpan">github.error.</span>RequestTimeout (msg)](#apidoc.element.github.error.RequestTimeout)
1.  [function <span class="apidocSignatureSpan">github.error.</span>RequestedRangeNotSatisfiable (msg)](#apidoc.element.github.error.RequestedRangeNotSatisfiable)
1.  [function <span class="apidocSignatureSpan">github.error.</span>RetryWith (msg)](#apidoc.element.github.error.RetryWith)
1.  [function <span class="apidocSignatureSpan">github.error.</span>ServiceUnavailable (msg)](#apidoc.element.github.error.ServiceUnavailable)
1.  [function <span class="apidocSignatureSpan">github.error.</span>TooManyRequests (msg)](#apidoc.element.github.error.TooManyRequests)
1.  [function <span class="apidocSignatureSpan">github.error.</span>Unauthorized (msg)](#apidoc.element.github.error.Unauthorized)
1.  [function <span class="apidocSignatureSpan">github.error.</span>UnorderedCollection (msg)](#apidoc.element.github.error.UnorderedCollection)
1.  [function <span class="apidocSignatureSpan">github.error.</span>UnprocessableEntity (msg)](#apidoc.element.github.error.UnprocessableEntity)
1.  [function <span class="apidocSignatureSpan">github.error.</span>UnsupportedMediaType (msg)](#apidoc.element.github.error.UnsupportedMediaType)
1.  [function <span class="apidocSignatureSpan">github.error.</span>UpgradeRequired (msg)](#apidoc.element.github.error.UpgradeRequired)
1.  [function <span class="apidocSignatureSpan">github.error.</span>VariantAlsoNegotiates (msg)](#apidoc.element.github.error.VariantAlsoNegotiates)

#### [module github.util](#apidoc.module.github.util)
1.  [function <span class="apidocSignatureSpan">github.util.</span>escapeRegExp (str)](#apidoc.element.github.util.escapeRegExp)
1.  [function <span class="apidocSignatureSpan">github.util.</span>extend (dest, src, noOverwrite)](#apidoc.element.github.util.extend)
1.  [function <span class="apidocSignatureSpan">github.util.</span>isFalse (c)](#apidoc.element.github.util.isFalse)
1.  [function <span class="apidocSignatureSpan">github.util.</span>isTrue (c)](#apidoc.element.github.util.isTrue)
1.  [function <span class="apidocSignatureSpan">github.util.</span>log ()](#apidoc.element.github.util.log)
1.  [function <span class="apidocSignatureSpan">github.util.</span>toCamelCase (str, upper)](#apidoc.element.github.util.toCamelCase)



# <a name="apidoc.module.github"></a>[module github](#apidoc.module.github)



# <a name="apidoc.module.github.error"></a>[module github.error](#apidoc.module.github.error)

#### <a name="apidoc.element.github.error.400"></a>[function <span class="apidocSignatureSpan">github.error.</span>400 (msg)](#apidoc.element.github.error.400)
- description and source-code
```javascript
400 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.401"></a>[function <span class="apidocSignatureSpan">github.error.</span>401 (msg)](#apidoc.element.github.error.401)
- description and source-code
```javascript
401 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.402"></a>[function <span class="apidocSignatureSpan">github.error.</span>402 (msg)](#apidoc.element.github.error.402)
- description and source-code
```javascript
402 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.403"></a>[function <span class="apidocSignatureSpan">github.error.</span>403 (msg)](#apidoc.element.github.error.403)
- description and source-code
```javascript
403 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.404"></a>[function <span class="apidocSignatureSpan">github.error.</span>404 (msg)](#apidoc.element.github.error.404)
- description and source-code
```javascript
404 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.405"></a>[function <span class="apidocSignatureSpan">github.error.</span>405 (msg)](#apidoc.element.github.error.405)
- description and source-code
```javascript
405 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.406"></a>[function <span class="apidocSignatureSpan">github.error.</span>406 (msg)](#apidoc.element.github.error.406)
- description and source-code
```javascript
406 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.407"></a>[function <span class="apidocSignatureSpan">github.error.</span>407 (msg)](#apidoc.element.github.error.407)
- description and source-code
```javascript
407 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.408"></a>[function <span class="apidocSignatureSpan">github.error.</span>408 (msg)](#apidoc.element.github.error.408)
- description and source-code
```javascript
408 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.409"></a>[function <span class="apidocSignatureSpan">github.error.</span>409 (msg)](#apidoc.element.github.error.409)
- description and source-code
```javascript
409 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.410"></a>[function <span class="apidocSignatureSpan">github.error.</span>410 (msg)](#apidoc.element.github.error.410)
- description and source-code
```javascript
410 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.411"></a>[function <span class="apidocSignatureSpan">github.error.</span>411 (msg)](#apidoc.element.github.error.411)
- description and source-code
```javascript
411 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.412"></a>[function <span class="apidocSignatureSpan">github.error.</span>412 (msg)](#apidoc.element.github.error.412)
- description and source-code
```javascript
412 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.413"></a>[function <span class="apidocSignatureSpan">github.error.</span>413 (msg)](#apidoc.element.github.error.413)
- description and source-code
```javascript
413 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.414"></a>[function <span class="apidocSignatureSpan">github.error.</span>414 (msg)](#apidoc.element.github.error.414)
- description and source-code
```javascript
414 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.415"></a>[function <span class="apidocSignatureSpan">github.error.</span>415 (msg)](#apidoc.element.github.error.415)
- description and source-code
```javascript
415 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.416"></a>[function <span class="apidocSignatureSpan">github.error.</span>416 (msg)](#apidoc.element.github.error.416)
- description and source-code
```javascript
416 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.417"></a>[function <span class="apidocSignatureSpan">github.error.</span>417 (msg)](#apidoc.element.github.error.417)
- description and source-code
```javascript
417 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.420"></a>[function <span class="apidocSignatureSpan">github.error.</span>420 (msg)](#apidoc.element.github.error.420)
- description and source-code
```javascript
420 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.422"></a>[function <span class="apidocSignatureSpan">github.error.</span>422 (msg)](#apidoc.element.github.error.422)
- description and source-code
```javascript
422 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.423"></a>[function <span class="apidocSignatureSpan">github.error.</span>423 (msg)](#apidoc.element.github.error.423)
- description and source-code
```javascript
423 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.424"></a>[function <span class="apidocSignatureSpan">github.error.</span>424 (msg)](#apidoc.element.github.error.424)
- description and source-code
```javascript
424 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.425"></a>[function <span class="apidocSignatureSpan">github.error.</span>425 (msg)](#apidoc.element.github.error.425)
- description and source-code
```javascript
425 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.426"></a>[function <span class="apidocSignatureSpan">github.error.</span>426 (msg)](#apidoc.element.github.error.426)
- description and source-code
```javascript
426 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.428"></a>[function <span class="apidocSignatureSpan">github.error.</span>428 (msg)](#apidoc.element.github.error.428)
- description and source-code
```javascript
428 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.429"></a>[function <span class="apidocSignatureSpan">github.error.</span>429 (msg)](#apidoc.element.github.error.429)
- description and source-code
```javascript
429 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.431"></a>[function <span class="apidocSignatureSpan">github.error.</span>431 (msg)](#apidoc.element.github.error.431)
- description and source-code
```javascript
431 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.444"></a>[function <span class="apidocSignatureSpan">github.error.</span>444 (msg)](#apidoc.element.github.error.444)
- description and source-code
```javascript
444 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.449"></a>[function <span class="apidocSignatureSpan">github.error.</span>449 (msg)](#apidoc.element.github.error.449)
- description and source-code
```javascript
449 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.499"></a>[function <span class="apidocSignatureSpan">github.error.</span>499 (msg)](#apidoc.element.github.error.499)
- description and source-code
```javascript
499 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.500"></a>[function <span class="apidocSignatureSpan">github.error.</span>500 (msg)](#apidoc.element.github.error.500)
- description and source-code
```javascript
500 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.501"></a>[function <span class="apidocSignatureSpan">github.error.</span>501 (msg)](#apidoc.element.github.error.501)
- description and source-code
```javascript
501 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.502"></a>[function <span class="apidocSignatureSpan">github.error.</span>502 (msg)](#apidoc.element.github.error.502)
- description and source-code
```javascript
502 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.503"></a>[function <span class="apidocSignatureSpan">github.error.</span>503 (msg)](#apidoc.element.github.error.503)
- description and source-code
```javascript
503 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.504"></a>[function <span class="apidocSignatureSpan">github.error.</span>504 (msg)](#apidoc.element.github.error.504)
- description and source-code
```javascript
504 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.505"></a>[function <span class="apidocSignatureSpan">github.error.</span>505 (msg)](#apidoc.element.github.error.505)
- description and source-code
```javascript
505 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.506"></a>[function <span class="apidocSignatureSpan">github.error.</span>506 (msg)](#apidoc.element.github.error.506)
- description and source-code
```javascript
506 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.507"></a>[function <span class="apidocSignatureSpan">github.error.</span>507 (msg)](#apidoc.element.github.error.507)
- description and source-code
```javascript
507 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.508"></a>[function <span class="apidocSignatureSpan">github.error.</span>508 (msg)](#apidoc.element.github.error.508)
- description and source-code
```javascript
508 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.509"></a>[function <span class="apidocSignatureSpan">github.error.</span>509 (msg)](#apidoc.element.github.error.509)
- description and source-code
```javascript
509 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.510"></a>[function <span class="apidocSignatureSpan">github.error.</span>510 (msg)](#apidoc.element.github.error.510)
- description and source-code
```javascript
510 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.511"></a>[function <span class="apidocSignatureSpan">github.error.</span>511 (msg)](#apidoc.element.github.error.511)
- description and source-code
```javascript
511 = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.BadGateway"></a>[function <span class="apidocSignatureSpan">github.error.</span>BadGateway (msg)](#apidoc.element.github.error.BadGateway)
- description and source-code
```javascript
BadGateway = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.BadRequest"></a>[function <span class="apidocSignatureSpan">github.error.</span>BadRequest (msg)](#apidoc.element.github.error.BadRequest)
- description and source-code
```javascript
BadRequest = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.BandwidthLimitExceeded"></a>[function <span class="apidocSignatureSpan">github.error.</span>BandwidthLimitExceeded (msg)](#apidoc.element.github.error.BandwidthLimitExceeded)
- description and source-code
```javascript
BandwidthLimitExceeded = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.ClientClosedRequest"></a>[function <span class="apidocSignatureSpan">github.error.</span>ClientClosedRequest (msg)](#apidoc.element.github.error.ClientClosedRequest)
- description and source-code
```javascript
ClientClosedRequest = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.Conflict"></a>[function <span class="apidocSignatureSpan">github.error.</span>Conflict (msg)](#apidoc.element.github.error.Conflict)
- description and source-code
```javascript
Conflict = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.EnhanceYourCalm"></a>[function <span class="apidocSignatureSpan">github.error.</span>EnhanceYourCalm (msg)](#apidoc.element.github.error.EnhanceYourCalm)
- description and source-code
```javascript
EnhanceYourCalm = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.ExpectationFailed"></a>[function <span class="apidocSignatureSpan">github.error.</span>ExpectationFailed (msg)](#apidoc.element.github.error.ExpectationFailed)
- description and source-code
```javascript
ExpectationFailed = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.FailedDependency"></a>[function <span class="apidocSignatureSpan">github.error.</span>FailedDependency (msg)](#apidoc.element.github.error.FailedDependency)
- description and source-code
```javascript
FailedDependency = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.Forbidden"></a>[function <span class="apidocSignatureSpan">github.error.</span>Forbidden (msg)](#apidoc.element.github.error.Forbidden)
- description and source-code
```javascript
Forbidden = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.GatewayTimeout"></a>[function <span class="apidocSignatureSpan">github.error.</span>GatewayTimeout (msg)](#apidoc.element.github.error.GatewayTimeout)
- description and source-code
```javascript
GatewayTimeout = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.Gone"></a>[function <span class="apidocSignatureSpan">github.error.</span>Gone (msg)](#apidoc.element.github.error.Gone)
- description and source-code
```javascript
Gone = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.HttpError"></a>[function <span class="apidocSignatureSpan">github.error.</span>HttpError (message, code, headers)](#apidoc.element.github.error.HttpError)
- description and source-code
```javascript
HttpError = function (message, code, headers) {
    Error.call(this, message);
    //Error.captureStackTrace(this, arguments.callee);
    this.message = message;
    this.code = code;
    this.status = statusCodes[code];
    this.headers = headers;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.HttpVersionNotSupported"></a>[function <span class="apidocSignatureSpan">github.error.</span>HttpVersionNotSupported (msg)](#apidoc.element.github.error.HttpVersionNotSupported)
- description and source-code
```javascript
HttpVersionNotSupported = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.InsufficientStorage"></a>[function <span class="apidocSignatureSpan">github.error.</span>InsufficientStorage (msg)](#apidoc.element.github.error.InsufficientStorage)
- description and source-code
```javascript
InsufficientStorage = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.InternalServerError"></a>[function <span class="apidocSignatureSpan">github.error.</span>InternalServerError (msg)](#apidoc.element.github.error.InternalServerError)
- description and source-code
```javascript
InternalServerError = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.LengthRequired"></a>[function <span class="apidocSignatureSpan">github.error.</span>LengthRequired (msg)](#apidoc.element.github.error.LengthRequired)
- description and source-code
```javascript
LengthRequired = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.Locked"></a>[function <span class="apidocSignatureSpan">github.error.</span>Locked (msg)](#apidoc.element.github.error.Locked)
- description and source-code
```javascript
Locked = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.LoopDetected"></a>[function <span class="apidocSignatureSpan">github.error.</span>LoopDetected (msg)](#apidoc.element.github.error.LoopDetected)
- description and source-code
```javascript
LoopDetected = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.MethodNotAllowed"></a>[function <span class="apidocSignatureSpan">github.error.</span>MethodNotAllowed (msg)](#apidoc.element.github.error.MethodNotAllowed)
- description and source-code
```javascript
MethodNotAllowed = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.NetworkAuthenticationRequired"></a>[function <span class="apidocSignatureSpan">github.error.</span>NetworkAuthenticationRequired (msg)](#apidoc.element.github.error.NetworkAuthenticationRequired)
- description and source-code
```javascript
NetworkAuthenticationRequired = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.NoResponse"></a>[function <span class="apidocSignatureSpan">github.error.</span>NoResponse (msg)](#apidoc.element.github.error.NoResponse)
- description and source-code
```javascript
NoResponse = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.NotAcceptable"></a>[function <span class="apidocSignatureSpan">github.error.</span>NotAcceptable (msg)](#apidoc.element.github.error.NotAcceptable)
- description and source-code
```javascript
NotAcceptable = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.NotExtended"></a>[function <span class="apidocSignatureSpan">github.error.</span>NotExtended (msg)](#apidoc.element.github.error.NotExtended)
- description and source-code
```javascript
NotExtended = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.NotFound"></a>[function <span class="apidocSignatureSpan">github.error.</span>NotFound (msg)](#apidoc.element.github.error.NotFound)
- description and source-code
```javascript
NotFound = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.NotImplemented"></a>[function <span class="apidocSignatureSpan">github.error.</span>NotImplemented (msg)](#apidoc.element.github.error.NotImplemented)
- description and source-code
```javascript
NotImplemented = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.PaymentRequired"></a>[function <span class="apidocSignatureSpan">github.error.</span>PaymentRequired (msg)](#apidoc.element.github.error.PaymentRequired)
- description and source-code
```javascript
PaymentRequired = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.PreconditionFailed"></a>[function <span class="apidocSignatureSpan">github.error.</span>PreconditionFailed (msg)](#apidoc.element.github.error.PreconditionFailed)
- description and source-code
```javascript
PreconditionFailed = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.PreconditionRequired"></a>[function <span class="apidocSignatureSpan">github.error.</span>PreconditionRequired (msg)](#apidoc.element.github.error.PreconditionRequired)
- description and source-code
```javascript
PreconditionRequired = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.ProxyAuthenticationRequired"></a>[function <span class="apidocSignatureSpan">github.error.</span>ProxyAuthenticationRequired (msg)](#apidoc.element.github.error.ProxyAuthenticationRequired)
- description and source-code
```javascript
ProxyAuthenticationRequired = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.Request-uriTooLong"></a>[function <span class="apidocSignatureSpan">github.error.</span>Request-uriTooLong (msg)](#apidoc.element.github.error.Request-uriTooLong)
- description and source-code
```javascript
Request-uriTooLong = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.RequestEntityTooLarge"></a>[function <span class="apidocSignatureSpan">github.error.</span>RequestEntityTooLarge (msg)](#apidoc.element.github.error.RequestEntityTooLarge)
- description and source-code
```javascript
RequestEntityTooLarge = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.RequestHeaderFieldsTooLarge"></a>[function <span class="apidocSignatureSpan">github.error.</span>RequestHeaderFieldsTooLarge (msg)](#apidoc.element.github.error.RequestHeaderFieldsTooLarge)
- description and source-code
```javascript
RequestHeaderFieldsTooLarge = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.RequestTimeout"></a>[function <span class="apidocSignatureSpan">github.error.</span>RequestTimeout (msg)](#apidoc.element.github.error.RequestTimeout)
- description and source-code
```javascript
RequestTimeout = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.RequestedRangeNotSatisfiable"></a>[function <span class="apidocSignatureSpan">github.error.</span>RequestedRangeNotSatisfiable (msg)](#apidoc.element.github.error.RequestedRangeNotSatisfiable)
- description and source-code
```javascript
RequestedRangeNotSatisfiable = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.RetryWith"></a>[function <span class="apidocSignatureSpan">github.error.</span>RetryWith (msg)](#apidoc.element.github.error.RetryWith)
- description and source-code
```javascript
RetryWith = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.ServiceUnavailable"></a>[function <span class="apidocSignatureSpan">github.error.</span>ServiceUnavailable (msg)](#apidoc.element.github.error.ServiceUnavailable)
- description and source-code
```javascript
ServiceUnavailable = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.TooManyRequests"></a>[function <span class="apidocSignatureSpan">github.error.</span>TooManyRequests (msg)](#apidoc.element.github.error.TooManyRequests)
- description and source-code
```javascript
TooManyRequests = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.Unauthorized"></a>[function <span class="apidocSignatureSpan">github.error.</span>Unauthorized (msg)](#apidoc.element.github.error.Unauthorized)
- description and source-code
```javascript
Unauthorized = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.UnorderedCollection"></a>[function <span class="apidocSignatureSpan">github.error.</span>UnorderedCollection (msg)](#apidoc.element.github.error.UnorderedCollection)
- description and source-code
```javascript
UnorderedCollection = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.UnprocessableEntity"></a>[function <span class="apidocSignatureSpan">github.error.</span>UnprocessableEntity (msg)](#apidoc.element.github.error.UnprocessableEntity)
- description and source-code
```javascript
UnprocessableEntity = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.UnsupportedMediaType"></a>[function <span class="apidocSignatureSpan">github.error.</span>UnsupportedMediaType (msg)](#apidoc.element.github.error.UnsupportedMediaType)
- description and source-code
```javascript
UnsupportedMediaType = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.UpgradeRequired"></a>[function <span class="apidocSignatureSpan">github.error.</span>UpgradeRequired (msg)](#apidoc.element.github.error.UpgradeRequired)
- description and source-code
```javascript
UpgradeRequired = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.error.VariantAlsoNegotiates"></a>[function <span class="apidocSignatureSpan">github.error.</span>VariantAlsoNegotiates (msg)](#apidoc.element.github.error.VariantAlsoNegotiates)
- description and source-code
```javascript
VariantAlsoNegotiates = function (msg) {
    this.defaultMessage = defaultMsg;
    exports.HttpError.call(this, msg || status + ": " + defaultMsg, status);

    if (status >= 500)
        Error.captureStackTrace(this, arguments.callee);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.github.util"></a>[module github.util](#apidoc.module.github.util)

#### <a name="apidoc.element.github.util.escapeRegExp"></a>[function <span class="apidocSignatureSpan">github.util.</span>escapeRegExp (str)](#apidoc.element.github.util.escapeRegExp)
- description and source-code
```javascript
escapeRegExp = function (str) {
    return str.replace(/([.*+?^${}()|[\]\/\\])/g, '\\$1');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.util.extend"></a>[function <span class="apidocSignatureSpan">github.util.</span>extend (dest, src, noOverwrite)](#apidoc.element.github.util.extend)
- description and source-code
```javascript
extend = function (dest, src, noOverwrite) {
    for (var prop in src) {
        if (!noOverwrite || typeof dest[prop] == "undefined") {
            dest[prop] = src[prop];
        }
    }
    return dest;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.util.isFalse"></a>[function <span class="apidocSignatureSpan">github.util.</span>isFalse (c)](#apidoc.element.github.util.isFalse)
- description and source-code
```javascript
isFalse = function (c){
    return (c === false || c === "false" || c === "off" || c === 0 || c === "0");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.util.isTrue"></a>[function <span class="apidocSignatureSpan">github.util.</span>isTrue (c)](#apidoc.element.github.util.isTrue)
- description and source-code
```javascript
isTrue = function (c){
    return (c === true || c === "true" || c === "on" || typeof c == "number" && c > 0 || c === "1");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.github.util.log"></a>[function <span class="apidocSignatureSpan">github.util.</span>log ()](#apidoc.element.github.util.log)
- description and source-code
```javascript
log = function () {
    var args = _slice.call(arguments);
    var lastArg = args[args.length - 1];

    var level = levels[lastArg] ? args.pop() : "info";
    if (!args.length) {
        return;
    }

    var msg = args.map(function(arg) {
        return typeof arg != "string" ? Util.inspect(arg) : arg;
    }).join(" ");
    var pfx = levels[level][0] + "[" + level + "]" + levels[level][1];

    msg.split("\n").forEach(function(line) {
        console.log(pfx + " " + line);
    });
}
```
- example usage
```shell
...
github.users.getFollowingForUser({
    // optional
    // headers: {
    //     "cookie": "blahblah"
    // },
    username: "defunkt"
}, function(err, res) {
    console.log(JSON.stringify(res));
});
'''

## Pagination

There are a few pagination-related methods:
...
```

#### <a name="apidoc.element.github.util.toCamelCase"></a>[function <span class="apidocSignatureSpan">github.util.</span>toCamelCase (str, upper)](#apidoc.element.github.util.toCamelCase)
- description and source-code
```javascript
toCamelCase = function (str, upper) {
    str = str.toLowerCase().replace(/(?:(^.)|(\s+.)|(-.))/g, function(match) {
        return match.charAt(match.length - 1).toUpperCase();
    });
    if (upper) {
        return str;
    }
    return str.charAt(0).toLowerCase() + str.substr(1);
}
```
- example usage
```shell
...
 *      - upper (Boolean): set to 'true' to transform to CamelCase
 *
 *  Transform a string that contains spaces or dashes to camelCase. If 'upper' is
 *  set to 'true', the string will be transformed to CamelCase.
 *
 *  Example:
 *
 *      Util.toCamelCase("why U no-work"); // returns 'whyUNoWork'
 *      Util.toCamelCase("I U no-work", true); // returns 'WhyUNoWork'
 **/
exports.toCamelCase = function(str, upper) {
str = str.toLowerCase().replace(/(?:(^.)|(\s+.)|(-.))/g, function(match) {
    return match.charAt(match.length - 1).toUpperCase();
});
if (upper) {
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
