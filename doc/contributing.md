Run locally
===========

You can run the `develop.sh` script to automatically watch all the sources and run tests, see the script for more
information.

Once you are ready, run the ```pre-push.sh``` which mimics what the CI server will build.

Releases
=========

Alphabetically using the [Crayola colours](http://en.wikipedia.org/wiki/List_of_Crayola_crayon_colors), but not any green variations naturally!

Heroku
======

You will need to specify a buildpack using:

```heroku config:add 'BUILDPACK_URL=https://github.com/ddollar/heroku-buildpack-multi.git''```

Our instances

```
prod	git@heroku.com:nevergreen.git
staging	git@heroku.com:nevergreen-staging.git
```