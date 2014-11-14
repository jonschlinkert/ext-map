# ext-map [![NPM version](https://badge.fury.io/js/ext-map.svg)](http://badge.fury.io/js/ext-map)

> just an object that maps `src` file extensions to `dest` file extensions as key/value pairs (e.g. `{'.less': '.css'}`). Useful for dynamically rewriting paths in tasks/plugins. pull requests welcome.

## Install
### Install with [npm](npmjs.org)

```bash
npm i ext-map --save
```

## Run tests

```bash
npm test
```

## Usage

```js
var exts = require('ext-map');
```

### Mapped extensions

Pull requests to add mappings would be appreciated.

**HTML**

- `.md`: => `.html`
- `.hbs`: => `.html`
- `.slim`: => `.html`
- `.swig`: => `.html`
- `.tmpl`: => `.html`
- `.html`: => `.html`
- `.htm`: => `.html`

**css**

- `.less`: => `.css`
- `.styl`: => `.css`
- `.sass`: => `.css`
- `.scss`: => `.css`
- `.css`: => `.css`

**js**

- `.coffee`: => `.js`
- `.ls`: => `.js`
- `.ts`: => `.js`
- `.js`: => `.js`



## Contributing
Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/jonschlinkert/ext-map/issues)

## Author

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 

## License
Copyright (c) 2014 Jon Schlinkert  
Released under the MIT license

***

_This file was generated by [verb](https://github.com/assemble/verb) on November 13, 2014._