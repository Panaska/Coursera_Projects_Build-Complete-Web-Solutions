Installing node (with npm): nodejs.org or: <br>
http://brew.sh/index_ru.html (/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)") and then: brew install node<br>
npm update npm -g<br>
(sudo) npm cache clean<br>
npm uninstall -g npm<br>
npm install -g npm@2.12.1 - installing specific version of npm<br>
Ctrl + с - abort command<br>
cd PATH - change directory<br>
node -v, npm -v, gulp -v, bower -v - checking installed versions<br>
npm install http-server -g - to start server<br>
http-server C:\location\to\app - to put server into the app location<br>
(sudo) npm install json-server -g - installing json server<br>
json-server --watch db.json - starting json server<br>
(sudo) npm install jasmine-core --save-dev<br>
(sudo) npm install karma-cli -g (not working with me - problems with karma-phantomjs-launcher installing)<br>
npm install karma --save-dev (actually worked to install karma)<br>
npm install karma-jasmine --save-dev<br>
npm install phantomjs karma-phantomjs-launcher karma-chrome-launcher --save-dev<br>
npm install protractor -g<br>
webdriver-manager update<br>


(sudo - Mac, Linux) npm install -g node-sass<br>
node-sass mystyles.scss mystyles.css

(sudo) npm install -g less<br>
lessc mystyles.less > mystyles.css

(sudo) npm install -g bower<br>
bower init (creating bower.json)<br>
bower install (all dependencies from bower.json)<br>
bower install bootstrap -S<br>
bower install font-awesome -S<br>
bower install angular -S<br>
bower install angular-route -S<br>
bower install angular-ui-router -S<br>
bower install angular-resource -S<br>
bower install angular-mocks -S<br>

INSTALLING GRUNT<br>
(sudo) npm install -g grunt-cli       (globally)<br>
npm install grunt --save-dev   (inside the project)<br>

INSTALLING GRUNT MODULES<br>
npm install grunt-contrib-jshint --save-dev<br>
npm install jshint-stylish --save-dev<br>
npm install time-grunt --save-dev<br>
npm install jit-grunt --save-dev<br>
npm install grunt-contrib-copy --save-dev<br>
npm install grunt-contrib-clean --save-dev<br>
npm install grunt-contrib-concat --save-dev<br>
npm install grunt-contrib-cssmin --save-dev<br>
npm install grunt-contrib-uglify --save-dev<br>
npm install grunt-filerev --save-dev<br>
npm install grunt-usemin --save-dev<br>
npm install grunt-contrib-concat --save-dev<br>
npm install grunt-contrib-cssmin --save-dev<br>
npm install grunt-contrib-uglify --save-dev<br>
npm install grunt-filerev --save-dev<br>
npm install grunt-usemin --save-dev<br>
npm install grunt-contrib-watch --save-dev<br>
npm install grunt-contrib-connect --save-dev<br><br>

grunt<br>
grunt serve<br>
grunt build<br>
grunt test<br><br>

INSTALLING GULP<br>
(sudo) npm install -g gulp<br>

INSTALLING GULP PLUGINS<br>
npm install jshint gulp-jshint jshint-stylish gulp-imagemin gulp-concat gulp-uglify gulp-minify-css gulp-usemin gulp-cache gulp-changed gulp-rev gulp-rename gulp-notify  browser-sync del --save-dev<br>
npm install gulp-ng-annotate --save-dev<br>

gulp<br>
gulp watch<br><br>

RUNNING TESTS<br>
karma start karma.conf.js (from test folder)<br>
protractor protractor.conf.js (from test older)<br><br>

INSTALLING YO<br>
(sudo) npm install yo -g (after installing bower, grunt, gulp - or instead of it)<br><br>

INSTALLIG GENERATORS<br>
(sudo) npm install generator-angular -g (other generators: yeoman.io)<br><br>

SCAFFOLDING OUT A PROJECT<br>
Create a project folder/directory -> yo *generator_name* (i.e. angular) (from project folder)<br><br>

INTALLING IONIC<br>
(sudo) npm install cordova ionic -g<br><br>

CREATING AN IONIC PROJECT<br>
ionic start *Project_name* sidemenu --v1 (or --v2) (from the project folder)<br>
cd *Project_name*<br>
ionic serve<br>
ionic serve --lab (views in iOS and Android)<br>
ionic platform add android (ios)<br>
ionic platform remove android (ios)<br>
ionic build android<br>
ionic emulate android<br>
ionic run android<br>
ionic resources - creating splash screen<br>
bower install ngCordova --save
