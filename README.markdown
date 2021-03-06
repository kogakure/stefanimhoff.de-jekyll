![Maintenance](https://img.shields.io/maintenance/no/2016.svg)

# stefanimhoff.de

This is the source of my [personal website and blog](http://stefanimhoff.de/) build with [Jekyll](http://jekyllrb.com/) and [Gulp.js](http://gulpjs.com/).

## Installation

You will need [Bundler](http://bundler.io/), [Node.js](http://nodejs.org/), [Gulp.js](http://gulpjs.com/) and [Bower](http://bower.io/) to run this website:

```sh
$ gem install bundler
$ npm install -g gulp
$ npm install -g bower
```

After cloning the repository run:

```sh
$ bundle install
$ bower install
$ npm install
```

## Running the website

The development enviroment is driven by Gulp.js. I have written three main gulp tasks:

```sh
$ gulp [default]
$ gulp publish
$ gulp deploy
```

To start the development enviroment run `gulp`. To build a production build run `gulp publish`. To sync the files to a server run `gulp deploy`.

The developement server will run on [http://0.0.0.0:9999/](http://0.0.0.0:9999/).

## Stuff I use on my website

These are just some of the tools, packages, languages and stuff I used to build my website:

- [Jekyll](http://jekyllrb.com/)
- [Octopress](https://github.com/octopress/octopress) to create posts and pages.
- [Gulp.js](http://gulpjs.com/) to run the development enviroment and create builds.
- [Node.js](http://nodejs.org/) to run Gulp.js, Bower and other tools
- [Bundler](http://bundler.io/) to have all Gems in an consistent enviroment.
- [Ruby](https://www.ruby-lang.org/) to write plugins for Jekyll.
- [JavaScript](https://developer.mozilla.org/docs/Web/JavaScript)
- [Browserify](http://browserify.org/) to use CommonJS modules.
- [BrowserSync](http://www.browsersync.io/) to have live reload and syning of actions.
- [PostCSS](https://github.com/postcss/postcss)
- [LostGrid](https://github.com/corysimmons/lost) to build the awesome Grid of my website.

## Licence
All content is copyrighted by [Stefan Imhoff](http://stefanimhoff.de) unless otherwise stated. Feel free to learn from the source code and reuse code for your projects. The only thing which is not allowed is the usage of my design (the unique combination of layout, fonts, images), private photos and logo.

In easier words: **This is not a free theme**. Learn from it. Remix. Reuse. Build your own stuff.
