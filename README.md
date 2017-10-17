# Javascript Track Project Setup
___
### Project Files
`touch index.html .gitignore README.md gulpfile.js js/NAME_OF_PROJECT.js js/NAME_OF_PROJECT-INTERFACE.js`

##### index.html header
```
<head>
  <link rel="stylesheet" href="build/css/vendor.css">
  <link href="build/css/vendor.css" rel="stylesheet" type="text/css">
  <script src="build/js/vendor.min.js"></script>
  <script type="text/javascript" src="build/js/app.js"></script>
</head>
```
___
## npm
Use the package.json (fill in you project name at the top of the gile), gulpfile.js, and karma.conf.js files, then `npm install`.

#### OR...Master npm Setup Command (Must run `npm init` first)
_`npm install gulp bower browserify vinyl-source-stream gulp-concat gulp-uglify gulp-util del jshint gulp-jshint bower-files browser-sync watchify jasmine karma karma-jasmine jasmine-core karma-chrome-launcher karma-cli karma-browserify karma-jquery karma-jasmine-html-reporter --save-dev`_
___
### bower
* `bower init`
* `bower install jquery bootstrap#v4.0.0-beta --save`
___
### Jasmine (Install before Karma)
* ` ./node_modules/.bin/jasmine init`
___
### Karma
Use provided template "karma.conf.js".

<!-- ### gulp stuff
* Make sure the backend js has corresponding exports at the bottom of the file (ex. `exports.module_NameModule = Module_Name;`)
* Make sure the frontend js has corresponding requires at the top of the file (ex. `var ComputerPlayer = require('./../js/pig.js').computerPlayerModule;`)
* Run `gulp build` before you fire up the browser. -->
___
### jshint (ES6)
Use the provided .jshintrc file

_OR_

Configure jshint for ES6 by creating a .jshintrc file in the root directory:
_`{ "esversion":6 }`_
___
# Cloning an Existing Prject

* `npm install`
* `bower install`
* `gulp build`
