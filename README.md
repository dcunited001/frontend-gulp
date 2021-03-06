# Frontend Gulp

A template for frontend web development with GulpJS, which includes:

- Tasks for JS/JSHint, Less, Image compression, Web Components
- Concatenation & Minification of JS, CSS, and your **Web Components**
- Includes Polymer's core-elements & paper-elements
- Error handling that doesn't break `gulp watch`
- Nice gulp-notify configuration, with different sounds for success & failure

## Getting Started

1. `npm install -g bower gulp`
1. `npm install`
1. `bower install`
1. `gulp` to build
  - `gulp clean` to clean dist folder
  - `export NODE_ENV=production && gulp` to build using production values set in `config.json`
1. `gulp watch` to set up a filechange watch
1. `gulp webserver` to run the gulp-webserver to serve static files
1. Connect to [http://localhost:8000](http://localhost:8000)

## Deploying

The app is hosted at [development.oscillate.divshot.io](http://development.oscillate.divshot.io).  Divshot is a
service to host completely static sites.

Deploy with the following:

1) NODE_ENV=divshot gulp
2) divshot push

## References

### Official Docs:

- [getting started](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md)
- [recipes](https://github.com/gulpjs/gulp/tree/master/docs/recipes)
- [docs readme](https://github.com/gulpjs/gulp/blob/master/docs/README.md#articles)

### Intro Blogs

- [markgoodyear's gulp guide](http://markgoodyear.com/2014/01/getting-started-with-gulp/)
- [Rome wasn't built with Gulp](http://www.adamlynch.com/rome-wasnt-built-with-gulp/#slide-0)
- http://travismaynard.com/writing/getting-started-with-gulp
- http://ilikekillnerds.com/2014/07/how-to-basic-tasks-in-gulp-js/
- http://blog.overzealous.com/post/74121048393/why-you-shouldnt-create-a-gulp-plugin-or-how-to-stop

### Error Handling Blogs

- [Error Handling in GulpJS](http://www.artandlogic.com/blog/2014/05/error-handling-in-gulp/)
- [Handle Errors While Using Gulp Watch](http://truongtx.me/2014/07/15/handle-errors-while-using-gulp-watch/)

### Vulcanize Web Components

- [gulp-vulcanize](https://www.npmjs.org/package/gulp-vulcanize)
- [vulcanize options](https://github.com/Polymer/grunt-vulcanize#options) (grunt & gulp plugins use same format)

### Gulp & Angular Templates

- https://www.npmjs.org/package/gulp-angular-templates
- https://www.npmjs.org/package/gulp-angular-templatecache

### Polymer/Angular SEO

- https://www.youtube.com/watch?v=inIIyR7hN8M&feature=youtu.be