# Amicus: your expert toolkit for rapid web prototyping

## What is it?

Amicus is a clean project starting point for the [Middleman](http://middlemanapp.com/) static site generator. It features [HTML5 Boilerplate](http://html5boilerplate.com/), [Haml](http://haml-lang.com/), [Sass](http://sass-lang.com/), [Compass](http://compass-style.org/), [Susy](http://susy.oddbird.net/) grid system, and lots of best practices.

## It's Responsive!

Amicus now comes with a mobile-first responsive grid system by default (see ```source/stylesheets/grid/_magic.sass```). Based on the [Susy "Magic" grid system](http://susy.oddbird.net/demos/magic/), it's ready to customize for your projects.

## How do I use it?

Start by installing [Bundler](http://gembundler.com/), if you don't already have it:

```
gem install bundler
```

Then just download the [latest source](https://github.com/nathos/amicus/archives/master) or if you prefer, clone the repository down to your local machine:

```
git clone http://github.com/nathos/amicus.git my_new_project
```

Finally, do a ```bundle install``` to install the required gems -- even Middleman itself!

Use ```middleman``` to do your live development and ```middleman build``` to render your static file output to the ```/build/``` directory.

For full Middleman documentation, visit the [Middleman website](http://middlemanapp.com/).


## Middleman Template

Middleman now supports project templates. To use Amicus as a template, clone the Git repository into ```~/.middleman```, like so:

```git clone http://github.com/nathos/amicus.git ~/.middleman/amicus```

then use the new template argument for the ```middleman init``` command:

```middleman init my_new_project --template=amicus```

Easy peasy!


## What other cool stuff is in here?

The default [Haml](http://haml-lang.com/) layout is based on [HTML5 Boilerplate](http://html5boilerplate.com/), and is fully commented. (Don't worry, those comments aren't rendered out to your build directory)

[Susy](http://susy.oddbird.net/) is the default grid system.

An included Ruby helper method to generate image placeholders, powered by [Holder.js](http://imsky.github.com/holder/).


## Comments & Suggestions?

Send me a [message](https://github.com/nathos) or submit an [issue](https://github.com/nathos/amicus/issues). Thanks!


## License

Following the lead of [HTML5 Boilerplate](https://github.com/h5bp/html5-boilerplate) here...

Major components:

* HTML5 Boilerplate: MIT license
* Normalize.css: MIT license
* Modernizr: MIT/BSD license
* jQuery: MIT/GPL license
* Susy: MIT license

Everything else:

* MIT license -- see LICENSE.md
