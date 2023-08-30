# search-operators

[![Release](https://img.shields.io/github/v/release/tgran2028/search-operators)](https://img.shields.io/github/v/release/tgran2028/search-operators)
[![Build status](https://img.shields.io/github/actions/workflow/status/tgran2028/search-operators/main.yml?branch=main)](https://github.com/tgran2028/search-operators/actions/workflows/main.yml?query=branch%3Amain)
[![codecov](https://codecov.io/gh/tgran2028/search-operators/branch/main/graph/badge.svg)](https://codecov.io/gh/tgran2028/search-operators)
[![Commit activity](https://img.shields.io/github/commit-activity/m/tgran2028/search-operators)](https://img.shields.io/github/commit-activity/m/tgran2028/search-operators)
[![License](https://img.shields.io/github/license/tgran2028/search-operators)](https://img.shields.io/github/license/tgran2028/search-operators)

This is a template repository for Python projects that use Poetry for their dependency management.

- **Github repository**: <https://github.com/tgran2028/search-operators/>
- **Documentation** <https://tgran2028.github.io/search-operators/>

## Getting started with your project

First, create a repository on GitHub with the same name as this project, and then run the following commands:

``` bash
git init -b main
git add .
git commit -m "init commit"
git remote add origin git@github.com:tgran2028/search-operators.git
git push -u origin main
```

Finally, install the environment and the pre-commit hooks with 

```bash
make install
```

You are now ready to start development on your project! The CI/CD
pipeline will be triggered when you open a pull request, merge to main,
or when you create a new release.

To finalize the set-up for publishing to PyPi or Artifactory, see
[here](https://fpgmaas.github.io/cookiecutter-poetry/features/publishing/#set-up-for-pypi).
For activating the automatic documentation with MkDocs, see
[here](https://fpgmaas.github.io/cookiecutter-poetry/features/mkdocs/#enabling-the-documentation-on-github).
To enable the code coverage reports, see [here](https://fpgmaas.github.io/cookiecutter-poetry/features/codecov/).

## Releasing a new version

- Create an API Token on [Pypi](https://pypi.org/).
- Add the API Token to your projects secrets with the name `PYPI_TOKEN` by visiting 
[this page](https://github.com/tgran2028/search-operators/settings/secrets/actions/new).
- Create a [new release](https://github.com/tgran2028/search-operators/releases/new) on Github. 
Create a new tag in the form ``*.*.*``.

For more details, see [here](https://fpgmaas.github.io/cookiecutter-poetry/features/cicd/#how-to-trigger-a-release).

---

Repository initiated with [fpgmaas/cookiecutter-poetry](https://github.com/fpgmaas/cookiecutter-poetry).