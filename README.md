## Pug-Sass Starter project.

[![Build Status][travis-image]][travis-url]

This is a Pug and Sass starter project using gulp for task automation.

### Note
If you still need Jade support use [this](https://github.com/azemoh/gulp-jade-sass-starter) project instead.

This project uses...

1. [browser-sync](https://github.com/browsersync/browser-sync) to launch a local server and do live reloads as sass and pug files changes
2. [gulp-pug](https://github.com/jamen/gulp-pug) to compile pug files.
3. [gulp-data](https://github.com/colynb/gulp-data) to pass data to pug. this project uses JSON as the data source, however you can generate data objects from a variety of sources: json, front-matter, database, etc... see gulp-data [README](https://github.com/colynb/gulp-data)
4. [gulp-sass](https://github.com/dlmanning/gulp-sass) to compile sass files.
5. [gulp-autoprefixer](https://github.com/sindresorhus/gulp-autoprefixer) to add vendor prefixes to css files

### To run
- Execute `npm install` from this directory to install dev dependencies.
- Execute `gulp` to run all tasks, launch the browser sync local server and watch for changes.

[travis-url]: https://travis-ci.org/azemoh/gulp-pug-sass-seed
[travis-image]: https://travis-ci.org/azemoh/gulp-pug-sass-seed.svg