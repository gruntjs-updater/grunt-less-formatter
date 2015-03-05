# grunt-less-formatter

> LESS formatter. Based on [this](http://www.calluna-software.com/Formatter/Css).

<a href="http://www.wtfpl.net/"><img src="http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-4.png" width="80" height="15" alt="WTFPL" /></a>

## Getting Started
This plugin requires Grunt `~0.4.5`

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:

```shell
npm install grunt-less-formatter --save-dev
```

Once the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks('grunt-less-formatter');
```

## The "less_formatter" task

### Overview
In your project's Gruntfile, add a section named `less_formatter` to the data object passed into `grunt.initConfig()`.

```js
grunt.initConfig({
  less_formatter: {
    options: {
      files: {
        src: ['<your_less_files>']
      }
    }
  },
});
```
