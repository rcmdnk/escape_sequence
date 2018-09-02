escape_sequence
===============

Scripts for checking escape sequences.

## Installation

On Mac, you can install scripts by [Homebrew](https://github.com/mxcl/homebrew):

    $ brew tap rcmdnk/rcmdnkpac
    $ brew install escape_sequence

If you have [brew-file](https://github.com/rcmdnk/homebrew-file), add following lines to Brewfile:

    tap 'rcmdnk/rcmdnkpac'
    brew 'escape_sequence'

then, do:

    $ brew file install

Or if you write like:

    tapall 'rcmdnk/rcmdnkpac'

and do `brew file install`, you will have all useful scripts in
[rcmdnkpac](https://github.com/rcmdnk/homebrew-rcmdnkpac).

You can also use an install script on the web like:

    $ curl -fsSL https://raw.github.com/rcmdnk/escape_sequence/install/install.sh| sh

This will install scripts to `/usr/bin`
and you may be asked root password.

If you want to install other directory, do like:

    $ curl -fsSL https://raw.github.com/rcmdnk/escape_sequence/install/install.sh|  prefix=~/usr/local/ sh

Or, simply download scripts and set where you like.

## Usage

### bin/escseqcheck

Show results of escape sequences.

### bin/256colors

Check 256 colors.

### bin/colcheck

Check Ansi colors,  256 colors and 24 bit true colors.

## References

* [Cygwin+screenで256 colorを有効にする](http://rcmdnk.github.io/blog/2013/09/05/computer-cygwin-putty-vim/)
