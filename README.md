f2kodepack
==========

[![Build Status](https://travis-ci.org/mraveri/f2kodepack.svg?branch=f2kodepack)](https://travis-ci.org/mraveri/f2kodepack)

This folder contains the rewriting of the odepack code in modern fortran.

Now the code has to be developed. The idea is to translate netlib odepack in modern fortran
using all the f2xxx features that we need to make it a modern code.

Main points:

* make sure it is thread safe;
* make sure that the high quality comments present in the original version are mantained intact;
* make sure that the code is doing things right. Write unit testing to ensure that, comparing the output with netlib odepack;
* testing portability might be a problem however full portability is not an immediate issue for me...
