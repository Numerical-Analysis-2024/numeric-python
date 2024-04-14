# Welcome to numeric

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/Numerical-Analysis-2024/numeric-python/ci.yml?branch=main)](https://github.com/Numerical-Analysis-2024/numeric-python/actions/workflows/ci.yml)
[![Documentation Status](https://readthedocs.org/projects/numeric-python/badge/)](https://numeric-python.readthedocs.io/)
[![codecov](https://codecov.io/gh/Numerical-Analysis-2024/numeric-python/branch/main/graph/badge.svg)](https://codecov.io/gh/Numerical-Analysis-2024/numeric-python)

## Installation

The Python package `numeric` can be installed from PyPI:

```
python -m pip install numeric
```

## Development installation

If you want to contribute to the development of `numeric`, we recommend
the following editable installation from this repository:

```
git clone https://github.com/Numerical-Analysis-2024/numeric-python
cd numeric
python -m pip install --editable .[tests]
```

Having done so, the test suite can be run using `pytest`:

```
python -m pytest
```

## Acknowledgments

This repository was set up using the [SSC Cookiecutter for Python Packages](https://github.com/ssciwr/cookiecutter-python-package).
