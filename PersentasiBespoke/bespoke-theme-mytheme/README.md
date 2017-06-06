[![Build Status](https://secure.travis-ci.org/Simamora11/bespoke-theme-mytheme.png?branch=master)](https://travis-ci.org/Simamora11/bespoke-theme-mytheme)

# bespoke-theme-mytheme

behavior &mdash; [View demo](http://Simamora11.github.io/bespoke-theme-mytheme)

## Download

Download the [production version][min] or the [development version][max], or use a [package manager](#package-managers).

[min]: https://raw.github.com/Simamora11/bespoke-theme-mytheme/master/dist/bespoke-theme-mytheme.min.js
[max]: https://raw.github.com/Simamora11/bespoke-theme-mytheme/master/dist/bespoke-theme-mytheme.js

## Usage

This theme is shipped in a [UMD format](https://github.com/umdjs/umd), meaning that it is available as a CommonJS/AMD module or browser global.

For example, when using CommonJS modules:

```js
var bespoke = require('bespoke'),
  mytheme = require('bespoke-theme-mytheme');

bespoke.from('#presentation', [
  mytheme()
]);
```

When using browser globals:

```js
bespoke.from('#presentation', [
  bespoke.themes.mytheme()
]);
```

## Package managers

### npm

```bash
$ npm install bespoke-theme-mytheme
```

### Bower

```bash
$ bower install bespoke-theme-mytheme
```

## Credits

This theme was built with [generator-bespoketheme](https://github.com/markdalgleish/generator-bespoketheme).

## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)
