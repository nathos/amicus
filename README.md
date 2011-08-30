# Middleman 2.0 Bootstrap


## What is it?

Middleman Bootstrap is my clean project starting point for the [Middleman](http://middlemanapp.com/) static site renderer. It includes [HTML5 Boilerplate](http://html5boilerplate.com/), your choice of [Blueprint](http://www.blueprintcss.org/tests/parts/grid.html) or [960.gs](http://960.gs/) grid systems, and lots of best practices.


## How do I use it?

Start by installing [Bundler](http://gembundler.com/):

```
gem install bundler
```

Then just download the [latest bootstrap source](https://github.com/nathos/middleman-bootstrap/archives/master) or if you prefer, clone the bootstrap repository down to your local machine:

```
git clone git://github.com/nathos/middleman-bootstrap.git mydirectory
```

Finally, do a ```bundle install``` to install the required gems.

Page templates and [Sass](http://sass-lang.com/) stylesheets are in the ```/views/``` directory. Put your images and JavaScripts in the ```/public/``` directory. Use ```middleman server``` to do your live development and ```middleman build``` to render your static file output to the ```/build/``` directory. 

For full Middleman documentation, visit the [Middleman website](http://middlemanapp.com/).

## Middleman 2.0 Template

Middleman 2.0 now supports project templates. To use Middleman Bootstrap as a template, clone the Git repository into ```~/.middleman```, like so:

```git clone git://github.com/nathos/middleman-bootstrap.git ~/.middleman/mm-bootstrap```

then use the new template argument for the ```middleman init``` command:

```middleman init my_new_project --template=mm-bootstrap```

Easy peasy!

## What other cool stuff is in here?

The default [Haml](http://haml-lang.com/) layout is based on HTML5 Boilerplate, and is fully commented. (Don't worry, those comments aren't rendered out to your build directory)

You can enable either 960.gs or Susy grid systems by uncommenting the appropriate line in ```config.rb``` and the main ```screen.css.sass``` file. Each grid partial (```_960gs.sass``` and ```_susy.sass```) includes a basic grid setup with comments.

(Note: You can use the Blueprint grid system just by uncommenting the appropriate line in ```screen.css.sass```.)


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