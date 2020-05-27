# Cookiecutter PyPackage

Fork of a [cookiecutter](https://github.com/audreyr/cookiecutter) template for a
Python package. Forked under the BSD license.

## Features

-   Testing setup with `unittest` and `python setup.py test` or `pytest`
-   [Tox](http://testrun.org/tox/) testing: Setup to easily test for
    Python 3.5, 3.6, 3.7, 3.8
-   [Sphinx](http://sphinx-doc.org/) docs: Documentation ready for
    generation with, for example, [Read the
    Docs](https://readthedocs.io/)
-   [bump2version](https://github.com/c4urself/bump2version):
    Pre-configured version bumping with a single command
-   Auto-release to [PyPI](https://pypi.python.org/pypi) when you push a
    new tag to master (optional)
-   Command line interface using Click (optional)


## Quickstart

Install the latest Cookiecutter if you haven\'t installed it yet (this
requires Cookiecutter 1.4.0 or higher):

    pip install -U cookiecutter

Generate a Python package project:

    cookiecutter https://github.com/thweber-sh/cookiecutter-pypackage.git

Then:

-   Create a virtual environment for your package.
-   Install the dev requirements into the virtualenv.
    (`pip install -r requirements_dev.txt`)
-   Begin developing your python package.

## TODO
-   Add support for [Sphinx](https://www.sphinx-doc.org/en/master/) documentation.
-   Refactor this repository to conform to our build system.
