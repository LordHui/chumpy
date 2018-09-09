metabochumpy
============

[![pip install](https://img.shields.io/badge/pip%20install-metabochumpy-f441b8.svg?style=flat-square)][pypi]
[![version](https://img.shields.io/pypi/v/metabochumpy.svg?style=flat-square)][pypi]
[![python versions](https://img.shields.io/pypi/pyversions/metabochumpy.svg?style=flat-square)][pypi]
[![build status](https://img.shields.io/circleci/project/github/metabolize/chumpy/master.svg?style=flat-square)][circle]
[![last commit](https://img.shields.io/github/last-commit/metabolize/chumpy.svg?style=flat-square)][commits]
[![open pull requests](https://img.shields.io/github/issues-pr/metabolize/chumpy.svg?style=flat-square)][pull requests]

This is an active fork of [chumpy][upstream], Matt Loper's autodifferentiation
tool for Python.

The fork's goals are modest:

- Keep the library working in current versions of Python and other tools.
- Make bug fixes.
- Provide API stability and backward compatibility with the upstream version.
- Respond to community contributions.

[upstream]: https://github.com/mattloper/chumpy
[circle]: https://circleci.com/gh/metabolize/chumpy
[pypi]: https://pypi.org/project/metabochumpy/
[pull requests]: https://github.com/metabolize/chumpy/pulls
[commits]: https://github.com/metabolize/chumpy/commits/master


Installation
------------

Install the fork:

```sh
pip install metabochumpy
```

And import it just like the upstream library:

```py
import chumpy as ch
```

Overview
--------

Chumpy is a Python-based framework designed to handle the **auto-differentiation** problem,
which is to evaluate an expression and its derivatives with respect to its inputs, by use of the chain rule.

Chumpy is intended to make construction and local
minimization of objectives easier.

Specifically, it provides:

- Easy problem construction by using Numpy’s application interface
- Easy access to derivatives via auto differentiation
- Easy local optimization methods (12 of them: most of which use the derivatives)

Usage
-----

Chumpy comes with its own demos, which can be seen by typing the following:

```python
import chumpy
chumpy.demo() # prints out a list of possible demos
```


Acknowledgements
----------------

Chumpy was created by [Matthew Loper][].

[matthew loper]: http://github.com/mattloper


License
-------

This project is licensed udner the MIT License.
