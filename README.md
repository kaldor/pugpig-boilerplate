pugpig-boilerplate
==================

Opinionated template for working on static Pugpig Templates

Usage requirements:

* Homebrew - ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"
* jpegtran - brew install jpeg
* optipng - brew install optipng
* nodejs - http://nodejs.org/
* npm - included with nodejs
* * PhantomJS - npm install -g phantomjs
* Ruby - installed by default on OSX
* Compass - gem install compass
* Compass Normalize - gem install compass-normalize
* * Yeoman - http://yeoman.io/index.html check your setup is ready by typing: curl -L get.yeoman.io | bash

Once Yeoman is the only thing that the Yeoman environment check says you do not have, run:

npm install -g yeoman

Before trying to use any Yeoman commands within the project, you will need to run:

npm install

To install the node module dependencies for the project. Once this is done, run:

yeoman server

To kick start the local server (no more refreshing!)
