Python package template
=======================

A template for a python package.

## Requirements to use the cookiecutter template

- Python 3.8+
- Cookiecutter Python package >= 2.1.0.

For cookiecutter install you can to use the following command

```bash
python3 -m pip install cookiecutter
```

## Start a new project

To start a new project, run:

```bash
# clone the template repository
git clone git@github.com:denisart/cookiecutter-python-package-template.git

# create a new service
python3 -m cookiecutter cookiecutter-python-package-template/
```

and answer to the following questions

```
project_name [Package Name]: Your package name
py_version [310]: 310
version [0.0.1]: Init version for package
short_description [A short description of the package.]:
maintainer_name [<First Name> <Last Name>]:
maintainer_email [<maintainer>@<domen>]:
```
