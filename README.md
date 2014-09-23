# userhome [![Build Status](http://img.shields.io/travis/shama/userhome.svg)](https://travis-ci.org/shama/userhome)

> A cross-platform (OSX, Windows, Linux) path to the user's home.

```js
var userhome = require('userhome');

console.log(userhome('.bashrc'));
// /Users/shama/.bashrc

console.log(userhome('test', 'sub', 'file'));
// /Users/shama/test/sub/file

console.log(userhome());
// C:\Users\shama
```

## Release History
* 0.1.0 - initial release

## License
Copyright (c) 2014 Kyle Robinson Young  
Licensed under the MIT license.
