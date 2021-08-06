# template-python

[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/serverhorror/template-python/main.svg)](https://results.pre-commit.ci/latest/github/serverhorror/template-python/main) &nbsp;
[![Python package](https://github.com/serverhorror/template-python/actions/workflows/python-package.yml/badge.svg)](https://github.com/serverhorror/template-python/actions/workflows/python-package.yml)

This is a `template-python` project that you can use to get started with VS Code and Python.

By default it pulls the latest available Python 3 container

## Usage

1. Find and replace `serverhorror/template-python` with your GitHub username and repository name
1. Find and replace `template-python` with your repository name
1. Find and replace `Your Name <you@example.com>` with the actual name you want to use

## Features

* devcontainer.json

  Let's you start with all the right settings and a few extensions pre-installed.

* poetry

  Poetry is set up so that the .venv is created right inside of this project.

* https://pre-commit.org

  Configured to check/lint Python code with MyPy and format everything with black.


* GitHub Actions

  Checks the code with flake8 and runs pytest against the codebase.

  * https://pre-commit.ci/

    Runs the pre-commit checks when commiting to GitHub.

  Check `pyproject.toml` for the details.
