## Setup

### Get python working

__There is a good chance this is already working on your system.__ Check if either `python --version` or `pip --version` return an error.
If these work you can skip this step.

If you have access to [Spack](https://spack.io/) you get one by running `spack load -first python`.
Else you can also use your package manager of choice.

### Setting up the venv

It is generally not recommended to install python dependencies globally.

`python -m venv /path/to/new/virtual/environment`
