# gulp-static-site
Creating a simple static site using Gulp task runner.
Site has three pages: index, about and contact.  Each page is put together by gulp by using the gulp.concat method, from three different partials: header, footer and page body.
Gulp also compiles a sass style sheet using the gulp-sass module.
Finally, The site makes use of gulp-livereload, to reload the browser automatically every time that Gulp detects changes.
