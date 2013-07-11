gettrainingwheels.org
=====================

The old source for the gettrainingwheels.org website. This is no longer used. Please see trainingwheels/trainingwheels.github.io instead.


Generated using Yeoman.

Getting started
---------------

1. Install [yeoman](http://yeoman.io/).
2. Run `yeoman build`
3. The build site will be in the newly created *dist*.

To run the webserver, do:

1. `yeoman server`
2. Point your browser at `http://localhost:3501/`

Yeoman server will watch the SASS files using Compass and rebuild them for you.

Installing phantomjs
--------------------

One of the Yeoman dependencies is PhantomJS. To set it up on Linux:

1. Download the tarball at http://phantomjs.org/download.html#linux. Don't worry that it's built on Centos.
2. Extract using `bunzip2 phantomjs-xxx.tar.bz2; tar xf phantomjs-xxx.tar`
3. `mv bin/phantomjs /usr/local/bin`

On OSX, the instructions on the PhantomJS site use the `brew` package manager.
