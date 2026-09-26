# Synopsis #

The objective of the project is to scrap the user phone number, email and address details of every search.

* selenium
* mechanize
* requests
* lxml

# Code Example #

# Installation #

Clone the repository, then install dependencies:

**pip install -r requirements.txt**

All libraries are pinned for Python 2.7 compatibility.

# Pipeline and Workflow #

A GitHub Actions workflow is available at:

**.github/workflows/pipeline.yml**

It performs:

* dependency installation
* source compilation checks
* test execution with `nosetests tests`

# API Reference #

* http://selenium-python.readthedocs.org/
* http://wwwsearch.sourceforge.net/mechanize/documentation.html
* http://docs.python-requests.org/en/latest/
* http://lxml.de/

# Tests #

The tests can be run by entering in the root path

* nosetests tests

To check whether the code is intact.

# Contributors #

**Ajan Lal Shrestha**

ajan.shresh@gmail.com

**Amrit Kshetri**

kshetriamrit@gmail.com

# License #

Copyright (C) 2015
