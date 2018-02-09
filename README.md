This OPAM repository contains development versions of packages required for
building Mirage/Solo5 against Solo5 `master`.

To use this repository in an OPAM switch, add it using the following:

    opam repo add solo5-dev git://github.com/Solo5/opam-solo5

If you've previously installed Mirage/Solo5 in that switch, you should be able to upgrade to the development version(s) by doing:

    opam update && opam upgrade
