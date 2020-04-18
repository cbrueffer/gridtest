# GridTest

![https://img.shields.io/pypi/v/gridtest.svg](https://pypi.python.org/pypi/gridtest)
![https://img.shields.io/travis/vsoch/gridtest.svg](https://travis-ci.com/vsoch/gridtest)
![https://pyup.io/repos/github/vsoch/gridtest/shield.svg](https://pyup.io/repos/github/vsoch/gridtest/)

Simple grid testing setup for Python functions and modules.

## Overview 

GridTest is a small python library that will read in one or more python
scripts or modules, and generate a testing file that can be used to run grid
tests. Take a look at the [examples](examples) folder 
for getting started.

## Who is this software for?

Gridtest is intended for quick generation of running tests. It is not intended
to be a robust testing library like pytest or even unittest, but rather a quick
way to write tests for an entire module or set of files, and then have them
run on some CI service. My specific use case is that I wanted a way to quickly
generate tests for the libraries that I "did not have time to write tests for."
This is, at it's core, for the lazy person without a lot of time that at least
wants something. I considered calling it crappytest, but the name was too long :)

**under development**

 * Free software: MPL 2.0 License
