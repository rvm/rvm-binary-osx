# Static Ruby

[![Build Status](https://travis-ci.org/rvm/rvm-binary-osx.png?branch=master)](https://travis-ci.org/rvm/rvm-binary-osx)
[latest binaries](http://rvm.io/binaries/osx/10.9/x86_64/)

*(make sure to read messages and warnings)*

Installing used software:

    curl -ksSL https://install.smf.sh | sm_curl_command="curl -k"  bash -
    curl -L https://get.rvm.io | bash

Compiling static ruby:

    source ~/.rvm/scripts/rvm
    rvm autolibs smf
    rvm install 2.1.1 --movable

Ruby is installed in `$HOME/.rvm/rubies/ruby-2.1.1/`, to package:

    rvm prepare 2.1.1

Will generate: `ruby-2.1.1.tar.bz2`.
