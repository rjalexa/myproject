# myproject

![Build Status](https://github.com/rjalexa/myproject/actions/workflows/python-app.yml/badge.svg)

Python Continuous Integration with GitHub Actions demo

This minimal example is to show how to setup a project directory for a python project
structuring:

- all the code under the src directory, with each subdirectory being a package
  and under it one or more module files each containing one or more functions
- all the tests are under the tests directory to be picked up by pytest and each test imports the needed modules and functions.
- the workflow automating all of this is in the .github/workflows directory and is triggered by a push to the master branch

This project has been tested automatically with a Git workflow
