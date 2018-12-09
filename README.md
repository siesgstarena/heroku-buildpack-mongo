# Heroku Buildpack: MongoDB 4.1.5

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) to run mongo commands (http://www.mongodb.org/). <br/>
It installs MongoDB 4.1.5 for Ubuntu 18.04 (stack: heroku-18).

Usage
-----

Example usage:

    $ heroku create myapp --buildpack http://github.com/siesgstarena/heroku-buildpack-mongo.git
    $ git push heroku master

or:
	
	$ heroku buildpacks:add http://github.com/siesgstarena/heroku-buildpack-mongo.git