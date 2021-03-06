> [Yeoman](http://yeoman.io) generator that scaffolds out a front-end web app using [gulp](http://gulpjs.com/) for the build process and Mitrhil as the MVC framework

![](screenshot.png)

## Features

Please see our [gulpfile.js](app/templates/gulpfile.js) for up to date information on what we support.

* Mitrhil MVC framework
* Built-in preview server with livereload
* Automagically compile with either Sass or Less
* Module loading using either Require or Browserify

*For more information on what this generator can do for you, take a look at the [gulp plugins](app/templates/_package.json) used in our `package.json`.*


## Getting Started

- Install: `npm install -g generator-gulp-mithril`
- Run: `yo gulp-mithril`
- Run `gulp` for building to the `dist` directory and `gulp serve` for preview

#### Third-Party Dependencies

*(HTML/CSS/JS/Images/etc)*

To install dependencies, run `bower install --save package-name` to get the files, then add a `script` or `style` tag to your `index.html` or another appropriate place.


## Options

- `--skip-install`
  Skips the automatic execution of `bower` and `npm` after scaffolding has finished.

- `--test-framework=<framework>`
  Defaults to `mocha`. Can be switched for another supported testing framework like `jasmine`.


## License

[BSD license](http://opensource.org/licenses/bsd-license.php)

![](app/templates/images/gulp.png)
![](app/templates/images/browserify.png)
![](app/templates/images/require.png)
![](app/templates/images/html.png)
![](app/templates/images/jquery.png)
![](app/templates/images/less.png)
![](app/templates/images/sass.png)
![](app/templates/images/bootstrap.png)
![](app/templates/images/modernizr.png)


## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
