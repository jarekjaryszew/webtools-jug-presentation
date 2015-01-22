##  Gruntfile anatomy 1

Plugins configuration:

```
grunt.initConfig({
  jshint: {
    files: ['Gruntfile.js', 'src/**/*.js', 'test/**/*.js'],
    options: {
      globals: {
        jQuery: true
      }
    }
    },
    watch: {
      files: ['<%= jshint.files %>'],
      tasks: ['jshint']
    }
    });
```
