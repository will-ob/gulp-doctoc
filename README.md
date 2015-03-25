gulp-doctoc
==============

Inject a table of contents into your markdown files.

Install
-----------

Install with [npm](https://npmjs.org/package/gulp-doctoc)

```javascript
npm install --save-dev gulp-doctoc
```

Usage
---------

```javascript
var toc    = require('gulp-doctoc'),
    marked = require('gulp-marked');

gulp.task('markdown', function(){

  gulp.src('./**/*.md')
    .pipe(toc())
    .pipe(marked())
    .pipe(gulp.dest('./public/'));

});

```

Thanks
-------

Thanks to [@thlorenz](https://github.com/thlorenz) for [doctoc](https://github.com/thlorenz/doctoc). He did all the hard work.

License
--------

MIT (same as [doctoc](https://github.com/thlorenz/doctoc))
