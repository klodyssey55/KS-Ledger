# KS-Ledger
Kevin and Sheila ledger application

Python best practices recommend using virtual environments to isolate your Python projects and manage their dependencies effectively.

To install the venv module and the pip package manager on Ubuntu, run the following commands in your terminal:
$ sudo apt update
$ sudo apt install python3-venv python3-pip

Proceed to create and activate a Python virtual environment for our PySide6 project:

$ mkdir project/ && cd project/

$ python3 -m venv ./venv

$ source venv/bin/activate

(venv) $

The prompt indicator changes to (venv) to signal that we're working inside an active virtual environment.

(venv) $ pip3 install pyside6

This command downloads PySide6 from the Python package index (PyPI) and installs it along with its dependencies into our virtual environment.

Run the python3 command in your virtual environment to start an interactive session and import the library:

>>> import PySide6

>>> print(PySide6.__version__)
