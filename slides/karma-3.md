##  Karma config

```
module.exports = function(config) {
  config.set({
    // base path, that will be used to resolve files and exclude
    basePath: '../',
    // testing framework to use (jasmine/mocha/qunit/...)
    frameworks: ['jasmine'],
    // list of files / patterns to load in the browser
    files: [
      test/*.js
    ],
    // list of files / patterns to exclude
    exclude: [],
    // web server port
    port: 8080,

    colors: true,

```
