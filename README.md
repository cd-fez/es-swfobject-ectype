# es-swfobject-ectype

This repository is a fork of https://github.com/swfobject/swfobject/ and publish the Version of 3.0 fix bug that remove 'argument.callee' calling in v2.2 with is forbidden is ES6. We add function name with Anonymous function

This a browserify compatible version of the `swfobject` library which is used toembed flash objects in your browsers.

The full documentation is available at: 
http://code.ciaoca.com/javascript/swfobject/

## Installation

This module is intended to be used in browserify and can therefor be installed
using npm:

```
npm install --save es-swfobject-ectype
```

## Versioning


SWFObject 3.0 introduces many small changes under the hood (almost exclusively aimed at fixing bugs), but the public API is mostly unchanged and completely backwards compatible with SWFObject 2.2.  The only two significant changes to the API: 

1. You may now pass an element as an argument in embedSWF (in place of an ID)
2. You may now use integers in place of number strings in embedSWF (e.g. 9 instead of "9").

## License

Same as the swfobject's license, MIT