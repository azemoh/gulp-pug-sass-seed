## Jade-Sass Starter project.

This is a Jade and Sass starter project using gulp for task automation.

This project uses...

1. [browser-sync](https://github.com/browsersync/browser-sync) to launch a local server and do live reloads as sass and jade files changes
2. [gulp-jade](https://github.com/phated/gulp-jade) to compile jade files.
3. [gulp-data](https://github.com/colynb/gulp-data) to pass data to jade. this project uses JSON as the data source, however you can generate data objects from a variety of sources: json, front-matter, database, etc... see gulp-data [README](https://github.com/colynb/gulp-data)
4. [gulp-sass](https://github.com/dlmanning/gulp-sass) to compile sass files.
5. [gulp-autoprefixer](https://github.com/sindresorhus/gulp-autoprefixer) to add vendor prefixes to css files

### To run
- Execute `npm install` from this directory to install dev dependencies.
- Execute `gulp` to run all tasks, launch the browser sync local server and watch for changes.

