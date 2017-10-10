# Javascript Track Project Setup
___
### Project Files
`touch index.html .gitignore README.md gulpfile.js js/NAME_OF_PROJECT.js js/NAME_OF_PROJECT-INTERFACE.js`
___
## npm
1. `npm init`
1. `npm install gulp --save-dev` (global install: `npm install gulp -g`)
1. `npm install bower -g`
1. `npm install browserify --save-dev`
1. `npm install vinyl-source-stream --save-dev`
1. `npm install gulp-concat --save-dev`
1. `npm install gulp-uglify --save-dev`
1. `npm install gulp-util --save-dev`
1. `npm install del --save-dev`
1. `npm install jshint --save-dev`
1. `npm install gulp-jshint --save-dev`
1. `npm install bower-files --save-dev`
1. `npm install browser-sync --save-dev`
1. `npm install watchify --save-dev`
1. `npm install karma --save-dev`
1. `npm install karma-jasmine jasmine-core --save-dev`
1. `npm install karma-chrome-launcher --save-dev`
1. `npm install karma-cli --save-dev`
1. `npm install karma-browserify --save-dev`
1. `npm install karma-jquery --save-dev`
1. `npm install karma-jasmine-html-reporter --save-dev`

#### OR...Master npm Setup Command (Must run `npm init` first)
_`npm install gulp bower browserify vinyl-source-stream gulp-concat gulp-uglify gulp-util del jshint gulp-jshint bower-files browser-sync watchify karma karma-jasmine jasmine-core karma-chrome-launcher karma-cli karma-browserify karma-jquery karma-jasmine-html-reporter --save-dev`_
___
### bower
* `bower init`
* `bower install jquery --save`
* `bower install bootstrap#v4.0.0 --save`
* `bower install moment --save`

#### OR...Master npm Setup Command (Must run `bower init` first)
_`bower install jquery bootstrap#v4.0.0-beta moment --save`_
___
# Javascript Track Project Clone
* `npm init`
* `npm install`
* `npm install bower -g`
* `bower init`
* `bower install`
* `gulp build`
___
### karma --optional
_Use template "karma.conf.js"_

_OR_

_`karma init` in root proj directory_
___
### gulp stuff
* Make sure the backend js has corresponding exports (ex. `exports.module_NameModule = Module_Name;`)
* Make sure the frontend js has corresponding requires (ex. `var ComputerPlayer = require('./../js/pig.js').computerPlayerModule;`)
* Run `gulp build`
