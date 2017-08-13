# gulp-static-site

We're creating a very simple static site, with the idea of highlighting Gulp's functionality.

Our site has three pages: index.html, about.html and contact.html.  Each page is put together by Gulp using the gulp.concat method, from three different partials: header, footer and page body (see partials folder).

Gulp also compiles a sass style sheet using the gulp-sass module. Our sass style sheet is very simple (again, the idea is just to show how Gulp works). It just contains some variables (for the link and top horizontal bar color, and for the font families of the main pages and the navigation menus).  Gulp detects changes to the sass style sheet and compiles the production-ready style sheet that it then stores in the css folder within the public directory.

The public directory holds all the compliled and concatenated static files which at this stage are ready to deploy.

Finally, for this project I also used the gulp-livereload module, to reload the browser automatically every time that Gulp detects changes.  For this module to work you also have to install the Livereload plugin for Google Chrome, and make sure that the dot in the plugin browser window icon has turned black (this should happen when you enable the plugin, but for some reason that doesn't happen every time).
