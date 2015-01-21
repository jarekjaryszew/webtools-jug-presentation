##  Node modules for your project

Before we go further you want to know how to save dev tools (node modules) for your project. You need first to set up npm project file (package.json):

```
npm init
```

Again, doesn't matter what you select there unless you plan to create new node module.

What is annoying, is that you have 2 files containing your app name and version (bower.json and package.json). There are no best practices how to handle them. I would keep them both updated and in sync as some tools might use versions from them.
