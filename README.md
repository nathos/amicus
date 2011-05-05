Middleman Bootstrap
===================

What is it?
-----------

Middleman Bootstrap is my clean project starting point for the [Middleman](http://middlemanapp.com/) static site renderer. It includes [HTML5 Boilerplate](http://html5boilerplate.com/), your choice of [Blueprint](http://www.blueprintcss.org/tests/parts/grid.html) or [960.gs](http://960.gs/) grid systems, and lots of best practices.


How do I use it?
----------------

Start by installing the [Middleman gem](http://rubygems.org/gems/middleman):

```
gem install middleman
```

Then just download the [latest source](https://github.com/nathos/middleman-bootstrap/archives/master) or if you prefer, clone the bootstrap repository down to your local machine:

```
git clone git://github.com/nathos/middleman-bootstrap.git mydirectory
```

Page templates and [Sass](http://sass-lang.com/) stylesheets are in the ```/views/``` directory. Put your images and JavaScripts in the ```/public/``` directory. Use ```mm-server``` to do your live development and ```mm-build``` to render your static file output to the ```/build/``` directory. 

For full Middleman documentation, visit the [Middleman wiki](https://github.com/tdreyno/middleman/wiki).


What cool stuff is in here?
---------------------------

The default [Haml](http://haml-lang.com/) layout is based on HTML5 Boilerplate, and is fully commented. (Don't worry, those comments aren't rendered out to your build directory)

You can enable either Blueprint or 960.gs grid systems by uncommenting the appropriate line in the main ```style.css.sass``` file. Each grid partial (```_960grid.sass``` and ```_blueprintgrid.sass```) includes a basic grid setup with comments.


Comments & Suggestions?
-----------------------

Send me a [message](https://github.com/nathos) or submit an [issue](https://github.com/nathos/middleman-bootstrap/issues). Thanks!


License
-------

Following the lead of [HTML5 Boilerplate](https://github.com/paulirish/html5-boilerplate) here...

Major components:

* Modernizr: MIT/BSD license
* jQuery: MIT/GPL license
* DD_belatedPNG: MIT license
* YUI Profiling: BSD license
* HTML5Doctor CSS reset: Public Domain
* CSS Reset Reloaded: Public Domain

Everything else:

* [The Unlicense](http://unlicense.org/) (aka: public domain)