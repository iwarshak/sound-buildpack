Heroku buildpack: sox
=======================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for using [sox](http://sox.sourceforge.net/)  and [lame](http://sox-buildpack.s3.amazonaws.com/sox.tar.gz) in your project.

Lineage
-------

Shamelessly merged from https://github.com/RBNA/soundselect-sox-buildpack and https://github.com/codeforamerica/heroku-buildpack-lame

Usage
-----
To use this buildpack, you should prepare a .buildpacks file that contains this buildpack url and your real buildpack url:

    heroku buildpacks:add https://github.com/iwarshak/sound-buildpack
