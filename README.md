# Cookiecutter PyPackage

A generic Python Package template that can be used with the utility [cookiecutter](https://github.com/cookiecutter/cookiecutter)

Fork of a popular Python package cookiecutter [template](https://github.com/audreyr/cookiecutter). Forked under the BSD license.

## Features

-   Testing setup with `unittest` and `python setup.py test` or `pytest`
-   [Tox](http://testrun.org/tox/) testing: Setup to easily test for
    Python 3.5, 3.6, 3.7, 3.8
-   [bump2version](https://github.com/c4urself/bump2version):
    Pre-configured version bumping with a single command


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
