## Pattern Lab Node with SASS to CSS Preprocessing as a Gulp Task

By default, the Node version of Pattern Lab doesn’t include CSS preprocessing. It is intentionally excluded due to the number of different workflows and tools for working with SASS. This version includes a Gulp task that processes SASS to CSS in source and public folders in parallel with BrowserSync.

## Prerequisites

[Node](https://nodejs.org) for core processing, [npm](https://www.npmjs.com/) to manage project dependencies, and [gulp.js](http://gulpjs.com/) to run tasks and interface with the core library. Installation of Node will include npm. It's also highly recommended to install gulp globally.

## Up and Running with Mac Terminal

```
git clone [this repository]
cd [root directory]
npm install
npm install gulp-sass
gulp patternlab:build
gulp patternlab:serve
```

## Manually Reproduce

To recreate this packaged repository, clone the Node Edition straight from Pattern Lab, add all standard modules, install gulp-sass and replace gulp.js.

* [Clone Node Edition and install NPM](https://github.com/pattern-lab/edition-node-gulp)
* [Install Gulp SASS](http://www.brianmuenzenmeyer.com/adding-common-gulp-tasks-to-pattern-lab-node)
* [Replace gulp.js](https://gist.github.com/bmuenzenmeyer/7a6ec54dc1ea720a61497a75ea88e3b4)
