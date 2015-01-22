##  Gruntfile anatomy 2

Load plugins:

```
grunt.loadNpmTasks('grunt-contrib-jshint');
grunt.loadNpmTasks('grunt-contrib-watch');
```

And of course register tasks:

```
grunt.registerTask('default', ['jshint']);
```
