Pugpig Boilerplate
===

Opinionated template for working on static Pugpig Templates

Dependencies:
---

* nodejs - http://nodejs.org/
* PhantomJS
```npm install -g phantomjs```
* CasperJS - http://casperjs.org/ - install using homebrew
* Karma
```npm install -g karma```
* Compass
```gem install compass```
* Compass Normalize
```gem install compass-normalize```
* Yeoman - http://yeoman.io/index.html
```npm install -g yo grunt-cli bower```

First step
---

The first thing you should do is cd into the project folder and run

```npm install && bower install```

This will install all node and bower dependencies for the project.

Start development server
---

To start your development server, run the following command in the project folder

```grunt server```

This will open the site in your default browser. It will reload every time you save.

Run unit tests
---

You can run your unit tests by running the following command in the project folder

```karma start```

This will open (by default) PhantomJS and run all of your tests each time a file changes. A good tip is to run the following command instead which will allow you to still run commands in the same Terminal tab

```karma start &```

If you wish to stop Karma from running, run

```fg ```

Then kill the task using CTRL + C.

Run functional tests
---

You can run your functional tests by running the following command in the project folder

```casperjs test test/functional```

View Code Coverage reports
---

Your Code Coverage reports can be found in the coverage folder. These are generated automatically by Istanbul when Karma runs your tests.
