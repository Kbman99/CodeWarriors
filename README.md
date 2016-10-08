# CodeWarriors

## Getting Setup
Setting up an environment for this project is simple. You will need virtualenv, pip and git.

## Python
https://www.python.org/downloads/

## pip
pip is a package-management sytem used to install and manage software packages written in Python. Most of these packages can be found on the Python Package Index (PyPI)

Go to:
https://bootstrap.pypa.io/get-pip.py

Right click -> Save as... -> [DirectoryName]

open up some commandline (Bash, Git Bash, PowerShell), navigate to [DirectoryName] and run this command

`python get-pip.py`

https://pip.pypa.io/en/stable/installing/

## virtualenv
This is probably one of the better guides to virtualenv. Read through it completely to get a good understanding of what virtualenv is and what it does.

http://docs.python-guide.org/en/latest/dev/virtualenvs/

## Installing dependencies/requirements
This is the nice part of python. Requirements of a project are the libraries that the project requires in order to function properly. Most every github repo and project file should contain a requirements.txt which is a one step process to getting all the requirements the project needs installed onto your virtualenv.
https://pip.pypa.io/en/latest/user_guide/#requirements-files

`pip install -r requirements.txt`

You can think of the requirements.txt file as a list of everything you need to download. You can specify the version of the software and add flags in the file.

More info on requirements files:
https://pip.pypa.io/en/stable/user_guide/
