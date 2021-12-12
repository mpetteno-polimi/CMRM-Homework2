# Computer Music: Representations and Models - Homework2

Repository for Homework #2 of CMRM course.
Required Python version is `3.9.x`  
For packages and virtual environment management the chosen tool is `pipenv`.

## Setup
1. Download and install [PyCharm IDE](https://www.jetbrains.com/pycharm/download).
2. Install `pipenv`. A guide is available [here](https://pipenv.pypa.io/en/latest/install/#installing-pipenv).
3. Create a new PyCharm project from this GIT repository.
5. Execute `PIPENV_VENV_IN_PROJECT=1 pipenv sync --dev` to initialize the virtual env and download the required 
   packages.
6. Reboot PyCharm to activate the new virtual environment.

## Install new Python packages
If you need a new package while developing, always use `pipenv`:
```shell script
# Use [package_name]==[version] to install a specific package's version 
# If you don't specify any version Pipfile package requirement will be inserted with '*' (allow any version)
# Use -d option to install the package as dev-requirement
pipenv install <package>
```
This will update the `Pipfile` and `Pipfile.lock` files and share the requirements with the other developers and 
environments.

## Run the notebook
Run the notebook with `jupyter notebook ./ChordRecognitionTemplateBased.ipynb`

