# myproject: a demo python repository with GitHub actions for code quality

## Live status:

![Main workflow](https://github.com/rjalexa/myproject/actions/workflows/python-app.yml/badge.svg) [![Codecov](https://codecov.io/gh/rjalexa/myproject/branch/main/graph/badge.svg?token=1F2VGHFJ3S)](https://codecov.io/gh/rjalexa/myproject)

## Tooling

[![contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg?style=flat)](https://github.com/rjalexa/myproject/issues) ![Linter](https://img.shields.io/badge/Linting-pylint-orange) ![Formatter](https://img.shields.io/badge/Formatter-black-orange) ![my badge](https://badgen.net/badge/Createdby/RJA/orange?icon=gitlab)

---

### Python Continuous Integration with GitHub Actions demo

This minimal example is to show how to setup a project directory for a python project
structuring:

- all the code under the src directory, with each subdirectory being a package,
  and under it one or more module files, each containing one or more functions/classes
- Code is evaluated with pylint (pylint src)
- all the tests are under the tests directory to be picked up by pytest and each test imports the needed modules and functions.
- pytest will also perform a coverage test to be sent to Codecov
- the workflow automating all of this is in the .github/workflows directory and is triggered by a push to the master branch
