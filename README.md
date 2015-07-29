# [gulp](https://gulpjs.com)-json-concat
[![Build Status](https://travis-ci.org/daviddiasfront/gulp-json-concat.svg?branch=master)](https://travis-ci.org/daviddiasfront/gulp-json-concat)
[![Dependencies](https://david-dm.org/daviddiasfront/gulp-json-concat.png)](https://david-dm.org/daviddiasfront/gulp-json-concat)
[![npm module downloads per month](http://img.shields.io/npm/dm/gulp-json-concat.svg)](https://www.npmjs.org/package/gulp-json-concat)

> Combine several JSON files with Gulp

## Install

[![NPM](https://nodei.co/npm/gulp-json-concat.png?compact=true)](https://www.npmjs.org/package/gulp-json-concat)

```shell
$ npm install --save-dev gulp-json-concat
```

## Usage

```js
var gulp = require('gulp');
var jsonConcat = require('gulp-json-concat');

gulp.task('sass', function () {
  return gulp.src('sass/global.scss')
    .pipe(checkGem({gemfile: 'scss-lint'},
      scsslint()
    ))
    .pipe(sass())
    .pipe(gulp.dest('dist'));
});
```


## API

### gemfile

- Type: `String`

```js
checkgem({
    gemfile: 'scss-lint'
});
```

## Changelog

### 0.0.1 Initial release
* initial code

## License

MIT © 2015 [David Dias](http://www.david-dias.com)
