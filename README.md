# OPAM orb for CircleCI

[![argent-smith](https://circleci.com/gh/argent-smith/opam_orb.svg?style=shield)](https://circleci.com/gh/argent-smith/opam_orb)

An opinionated OPAM workbench for CircleCI.

This orb supposes you are CI'ing a standard OCaml package
with correct <package_name>.opam file in its root and
a Dune build system (probably with a test suite).

This orb was written to use official ocaml/opam docker images.

MirageOS support is under construction.
