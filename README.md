camlp4
======

Camlp4 is a software system for writing extensible parsers for
programming languages. It provides a set of OCaml libraries that are
used to define grammars as well as loadable syntax extensions of such
grammars. Camlp4 stands for Caml Preprocessor and Pretty-Printer and
one of its most important applications is the definition of
domain-specific extensions of the syntax of OCaml.

Camlp4 was part of the official OCaml distribution until its version
4.01.0. Since then it has been replaced by a simpler system which is
easier to maintain and to learn: ppx rewriters and extension points.

Installation
------------

You should have OCaml installed. To build and install camlp4, type:

    ./configure
    make all
    make install

If you don't want or can't build the native code version, replace
`make all` by `make`.

Building from git
-----------------

Camlp4 branches try to follow OCaml ones. To build with the trunk of
OCaml, you need to use the trunk branch of Camlp4. To build for a
specific version, for instance 4.02.1, use the 4.02 branch of Camlp4.
