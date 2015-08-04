# es7features
Code for trying out the different es7 features.

## Overview

This repository is a bunch of code examples to explore the latest and greatest in *ecmascript 7*.

The gulp setup here will let you write the future of javascript today. The code is transpiled to ES5 for use in current browsers.

The gulp setup also lets you test the ES7 code using karma and jasmine.

The goal is to cover all new features that are introduced in es7 and to check their es5 equivalents using the [babel](https://babeljs.io/) transpiler.

## Usage

To further explore and add to these examples, you can first clone the repo. Then do the following - 

    $ npm install
    $ gulp


The default task in gulp will compile the code in the 'es7' directory and dump a folder called 'es5-babel' which has the 
respective transpiled code to es5.

## Tests

    $ npm install
    $ gulp test

## License

[The MIT License](http://opensource.org/licenses/MIT)
