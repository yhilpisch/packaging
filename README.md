# pylib -- Python Packaging

This is the rather simplistic packaging example from the Tools & Skills class of The Python Quants.

<img src="http://hilpisch.com/images/finaince_visual_low.png" width=300px>

## Package

The package contains a total of three simple Python files, two of which are in sub-folders/sub-packages, with a single function each.

## Training

In addition to the package files, the Git repository contains also other files used for the training session.

## Tutorial

Install the `pylib` package via

    pip install --index-url https://test.pypi.org/simple/ pylib
    
Start a Python interactive session session and e.g. execute:

    >>> import pylib
    >>> pylib.one(10)
    10
    >>> pylib.two(20)
    40
    >>> pylib.three(3)
    9

## Copyright

The material is copyright (c) Dr. Yves J. Hilpisch | The Python Quants GmbH. MIT License.
