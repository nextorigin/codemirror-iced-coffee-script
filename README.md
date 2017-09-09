# codemirror-iced-coffee-script

[![Greenkeeper badge](https://badges.greenkeeper.io/nextorigin/codemirror-iced-coffee-script.svg)](https://greenkeeper.io/)
IcedCoffeeScript mode for [CodeMirror](http://codemirror.net)

## Installation
```sh
npm install --save-dev codemirror-iced-coffee-script
```

## Usage
**codemirror-iced-coffee-script** expects **codemirror** to be available on the window object or it will attempt to `require("codemirror")`.

**codemirror-iced-coffee-script** is also designed to be used with `require()` for easy usage with Browserify.
```coffee
CodeMirror = require "codemirror"
IcedMirror = require "codemirror-iced-coffee-script"

...

codemirror = CodeMirror.fromTextArea ($ "placeholder")[0], {
    mode: "icedcoffeescript"
}
```

## License
MIT.  (C) 2016 Double Rebel
