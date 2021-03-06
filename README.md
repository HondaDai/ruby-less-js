Ruby LessJs
=================

Ruby LessJs is a bridge to the official Javascript-based Less.js compiler.

    LessJs.compile File.read("css.less")


Installation
------------

Original Version

    gem install less-js

Fixed Version
	
	git clone https://github.com/HondaDai/ruby-less-js.git
	cd ruby-less-js
	gem build ruby-less-js.gemspec
	gem install less-js-0.1.1
	gem install less-js-source


Dependencies
------------

This library depends on the `less-js-source` gem which will be
updated any time a new version of Less.js is released. (The
`less-js-source` gem's version number is synced with each
official Less.js release.) This way you can build against
different versions of Less.js by requiring the correct version of
the `less-js-source` gem.


### ExecJS

The [ExecJS](https://github.com/sstephenson/execjs) library is used to automatically choose the best JavaScript engine for your platform. Check out its [README](https://github.com/sstephenson/execjs/blob/master/README.md) for a complete list of supported engines.

**Must Using Nodejs**


Lifted From
-----------

The template for this gem was lifted from [Joshua Peek's](https://github.com/josh) [ruby-coffee-script](https://github.com/josh/ruby-coffee-script) gem.
