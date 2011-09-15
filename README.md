# Middleman 2.0 Bootstrap


## What is it?

Middleman Bootstrap is my clean project starting point for the [Middleman](http://middlemanapp.com/) static site renderer. It includes [HTML5 Boilerplate](http://html5boilerplate.com/), [Haml](http://haml-lang.com/), [Sass](http://sass-lang.com/), [Compass](http://compass-style.org/), your choice of grid frameworks, and lots of best practices.


## How do I use it?

Start by installing [Bundler](http://gembundler.com/), if you don't already have it:

```
gem install bundler
```

Then just download the [latest bootstrap source](https://github.com/nathos/middleman-bootstrap/archives/master) or if you prefer, clone the bootstrap repository down to your local machine:

```
git clone git://github.com/nathos/middleman-bootstrap.git my_new_project
```

Finally, do a ```bundle install``` to install the required gems -- even Middleman itself!

Use ```middleman server``` to do your live development and ```middleman build``` to render your static file output to the ```/build/``` directory. 

For full Middleman documentation, visit the [Middleman website](http://middlemanapp.com/).


## Middleman 2.0 Template - NEW!

Middleman 2.0 now supports project templates. To use Middleman Bootstrap as a template, clone the Git repository into ```~/.middleman```, like so:

```git clone git://github.com/nathos/middleman-bootstrap.git ~/.middleman/mm-bootstrap```

then use the new template argument for the ```middleman init``` command:

```middleman init my_new_project --template=mm-bootstrap```

Easy peasy!


## What other cool stuff is in here?

The default [Haml](http://haml-lang.com/) layout is based on [HTML5 Boilerplate](http://html5boilerplate.com/), and is fully commented. (Don't worry, those comments aren't rendered out to your build directory)

You can enable either [960.gs](http://960.gs/) or [Susy](http://susy.oddbird.net/) grid systems by uncommenting the appropriate lines in ```config.rb``` and the main ```screen.css.sass``` file. Each grid partial (```_960gs.sass```, ```_susy.sass```, ```_blueprint.sass```) includes a basic grid setup with comments.

(Note: Blueprint is built into Compass, so you can use its grid system just by uncommenting the appropriate ```@import``` line in ```screen.css.sass```.)


## Comments & Suggestions?

Send me a [message](https://github.com/nathos) or submit an [issue](https://github.com/nathos/middleman-bootstrap/issues). Thanks!


## License

Following the lead of [HTML5 Boilerplate](https://github.com/paulirish/html5-boilerplate) here...

Major components:

* Modernizr: MIT/BSD license
* jQuery: MIT/GPL license
* Respond.js: MIT/GPL license
* YUI Profiling: BSD license
* HTML5Doctor CSS reset: Public Domain
* CSS Reset Reloaded: Public Domain
* Blueprint CSS: MIT license
* 960.gs: MIT/GPL license

Everything else:

* [The Unlicense](http://unlicense.org/) (aka: public domain)