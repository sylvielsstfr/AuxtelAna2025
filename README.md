
# auxtelana2025

[![Template](https://img.shields.io/badge/Template-LINCC%20Frameworks%20Python%20Project%20Template-brightgreen)](https://lincc-ppt.readthedocs.io/en/latest/)

[![PyPI](https://img.shields.io/pypi/v/auxtelana2025?color=blue&logo=pypi&logoColor=white)](https://pypi.org/project/auxtelana2025/)
[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/LSSTDESC/auxtelana2025/smoke-test.yml)](https://github.com/LSSTDESC/auxtelana2025/actions/workflows/smoke-test.yml)
[![Codecov](https://codecov.io/gh/LSSTDESC/auxtelana2025/branch/main/graph/badge.svg)](https://codecov.io/gh/LSSTDESC/auxtelana2025)
[![Read The Docs](https://img.shields.io/readthedocs/auxtelana2025)](https://auxtelana2025.readthedocs.io/)
[![Benchmarks](https://img.shields.io/github/actions/workflow/status/LSSTDESC/auxtelana2025/asv-main.yml?label=benchmarks)](https://LSSTDESC.github.io/auxtelana2025/)

This project was automatically generated using the LINCC-Frameworks 
[python-project-template](https://github.com/lincc-frameworks/python-project-template).

A repository badge was added to show that this project uses the python-project-template, however it's up to
you whether or not you'd like to display it!

For more information about the project template see the 
[documentation](https://lincc-ppt.readthedocs.io/en/latest/).

## Dev Guide - Getting Started

Before installing any dependencies or writing code, it's a great idea to create a
virtual environment. LINCC-Frameworks engineers primarily use `conda` to manage virtual
environments. If you have conda installed locally, you can run the following to
create and activate a new environment.

```
>> conda create -n <env_name> python=3.10
>> conda activate <env_name>
```

Once you have created a new environment, you can install this project for local
development using the following commands:

```
>> ./.setup_dev.sh
>> conda install pandoc
```

Notes:
1. `./.setup_dev.sh` will initialize pre-commit for this local repository, so
   that a set of tests will be run prior to completing a local commit. For more
   information, see the Python Project Template documentation on 
   [pre-commit](https://lincc-ppt.readthedocs.io/en/latest/practices/precommit.html)
2. Install `pandoc` allows you to verify that automatic rendering of Jupyter notebooks
   into documentation for ReadTheDocs works as expected. For more information, see
   the Python Project Template documentation on
   [Sphinx and Python Notebooks](https://lincc-ppt.readthedocs.io/en/latest/practices/sphinx.html#python-notebooks)
