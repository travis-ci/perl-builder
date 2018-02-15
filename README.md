# perl-builder
builds Perl distributions with perlbrew

## Building with ease

Use [travis-nightly-builder](https://github.com/travis-ci/travis-nightly-builder).
Set up environment as described there, and then run, e.g.,

	bundle exec rake build['perl-builder','master',"VERSION=5.22.0"]

or

    bundle exec rake build['perl-builder','master',"VERSION=5.22.0 NAME=5.22-extras ALIAS=5.22-shrlibs ARGS='-Duseshrplib -Duseithreads'"]
