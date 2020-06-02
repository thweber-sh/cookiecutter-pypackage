# Cookiecutter PyPackage

A generic Python Package template that can be used with the utility [cookiecutter](https://github.com/cookiecutter/cookiecutter)

Fork of a popular Python package cookiecutter [template](https://github.com/audreyr/cookiecutter). 
Forked under the BSD license.

## Features

-   Testing setup with `unittest` and `python setup.py test` or `pytest`
-   [Tox](http://testrun.org/tox/) testing: Setup to easily test for
    Python 3.5, 3.6, 3.7, 3.8


## Quickstart

Install the latest Cookiecutter package on your machine if you haven't installed it yet (this
 requires Cookiecutter 1.4.0 or higher):

    pip install -U cookiecutter

Generate a Python package project:

    cookiecutter https://github.com/thweber-sh/cookiecutter-pypackage.git

Then:

1)  Create a virtual environment for your package.
2)  Install the dev requirements into the virtualenv (`pip install -r requirements_dev.txt`)
3)  Begin developing your python package.

## TODO
- Consider adding support for [Sphinx](https://www.sphinx-doc.org/en/master/) the generate code
 documentation.
- Consider adding support for [bump2version](https://pypi.org/project/bump2version/) to help
 automate version bumps.
