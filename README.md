[![Build Status](https://travis-ci.org/MolSSI/python_template.svg?branch=master)](https://travis-ci.org/MolSSI/python_template)[![Documentation Status](https://readthedocs.org/projects/molssi-python-template/badge/?version=latest)](http://molssi-python-template.readthedocs.io/en/latest/?badge=latest)[![codecov](https://codecov.io/gh/MolSSI/python_template/branch/master/graph/badge.svg)](https://codecov.io/gh/MolSSI/python_template)[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

# python_template
This repository will provide a starting template for new Python-based projects.
It demonstrates how to use tox to automate the testing process.  This cleans 
up the testing and install process considerably, allowing the developer to
test against multiple versions of python in one go, as well as to ensure that
the package setup works, the documentation compiles, and the code obeys style-
guidelines.  Moreover, it has the advantage that it tests an installed version
of the code, not the local files.  This helps catch errors in python
installation process.

The following tools will be used:
 - [GitHub](github.com) - Version Control
 - [Travis CI](https://travis-ci.org) - Continous Integration
 - [pytest](https://docs.pytest.org/en/latest/) - Unit and Regression Testing
 - [CodeCov](https://codecov.io) - Testing Coverage Analysis
 - [Read the Docs](https://readthedocs.org) - Documentation
 - [Tox](https://tox.readthedocs.io=en/latest/) - Wrapping all the tests together 

## Testing

If you have tox configured, you can run the tests simply by running the 
command `tox`.  Easy peasy!
