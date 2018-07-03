# pylib &mdash; Python Packaging

This is the rather simplistic packaging example from the Tools & Skills class of The Python Quants.

<br>

<img src="http://hilpisch.com/images/finaince_visual_low.png" width=300px>

## Package

The package contains a total of three simple Python files, two of which are in sub-folders/sub-packages, with a single function each.

## Training

In addition to the package files, the Git repository contains also other files used for the training session.

## Tutorial

### Environment

On the shell, create an environment with `conda`:

    conda create -n test-pylib python=3.6 ipython
    conda activate test-pylib

### Installation from Source

Clone the Github repository to your local working folder:

    git clone --depth=1 http://github.com/yhilpisch/packaging
    
Navigate to the repository folder and install the package:

    cd packaging
    python setup.py install

### Installation via pip

Alternatively, install the `pylib` package via

    pip install --index-url https://test.pypi.org/simple/ pylib
    
### First Steps
    
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
