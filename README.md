# Node.js Add-ons for High Performance Numeric Computing

> Talk for the [International JavaScript Conference, iJS, London (2018)][ijs-london-2018].


## Abstract

Node.js add-ons allow native code written in C and C++ to be run from the Node.js JavaScript runtime. In this talk, Athan will discuss how to utilize native add-ons for high performance numeric computing and machine learning in server-side applications. He will first provide an overview of add-ons and their associated toolchain. Next, he will provide a step-by-step example which involves compiling basic linear algebra subroutines (BLAS), a suite of libraries which are part of the core foundation of most modern numeric computing environments, as native add-ons. While Node.js add-ons are oriented toward C and C++, he will show how to extend compilation support to Fortran libraries in order to maximize computational performance. Throughout this talk, Athan will offer lessons learned, tips and tricks, and other insights gained while writing add-ons to help you maximize Node.js for your server-side applications and to demonstrate why Node.js is an excellent environment for high performance numeric computing and machine learning.

## Installation

``` bash
$ git clone https://github.com/kgryte/talks-ijs-london-2018
```

and

``` bash
$ npm install
```


## Usage

From the top-level directory,

``` bash
$ python -m SimpleHTTPServer 9000
```

and, in your browser, navigate to

```
http://127.0.0.1:9000
```


---

## Copyright

Copyright &copy; 2018. Athan Reines.


[ijs-london-2018]: https://javascript-conference.com/program/
