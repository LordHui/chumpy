chumpy
======

[![build status](https://img.shields.io/circleci/project/github/metabolize/chumpy/master.svg)][circle]
[![version](https://img.shields.io/pypi/v/metabochumpy.svg)][pypi]
[![license](https://img.shields.io/pypi/l/metabochumpy.svg)](LICENSE.txt)

**This is an active fork of [mattloper/chumpy][upstream].**

[upstream]: https://github.com/mattloper/chumpy
[circle]: https://circleci.com/gh/metabolize/chumpy
[pypi]: https://pypi.org/project/metabochumpy/


Chumpy is a Python-based framework designed to handle the **auto-differentiation** problem,
which is to evaluate an expression and its derivatives with respect to its inputs, by use of the chain rule.

Chumpy is intended to make construction and local
minimization of objectives easier.

Specifically, it provides:

- Easy problem construction by using Numpy’s application interface
- Easy access to derivatives via auto differentiation
- Easy local optimization methods (12 of them: most of which use the derivatives)

Installation
------------

```sh
pip install metabochumpy
```

```py
import chumpy as ch
```


Usage
-----

Chumpy comes with its own demos, which can be seen by typing the following:

```python
import chumpy
chumpy.demo() # prints out a list of possible demos
```


License
-------

Licensing is specified in the attached LICENSE.txt.

