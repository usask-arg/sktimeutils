# sktimeutils

[![Documentation Status](https://readthedocs.org/projects/showlib/badge/?version=latest)](https://showlib.readthedocs.io/en/latest/?badge=latest)
[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/usask-arg/showlib/main.svg)](https://results.pre-commit.ci/latest/github/usask-arg/showlib/main)

This package  provides common time conversion functions used by the usask-arg group. The
code tries to be friendly for arrays, sequences and scalars. This package is focussed on converting time expressed as 
Universal Time in one format to Universal Time in another format.  This package makes no provision for time zone conversions etc.  

## Installation
    
    pip install sktimeutils

also

    conda install setuptools build
    python -m build --wheel

## Usage
Documentation can be found at https://nick.argpages.usask.ca/skoptics/index.html

## Unit Tests
It is useful to run the unit tests as the tests will automatically download leap-second files and earth rotation 
information. Needless to say you must have an internet connection to successfully run the unit tests 

    python -m unittest discover -s sktimeutils.tests

## License
This project is licensed under the MIT license.




