# FDA Drug Shortages

Code for continuous scraping of data about current and resolved drug shortages, [published](http://www.accessdata.fda.gov/scripts/drugshortages/) by the Food and Drug Administration.

## Pre-requisites

You'll need Python 2.7. You can run the following command to check if you already meet this requirement:

```sh
$ python -V
Python 2.7.11
```

If your using a Mac (like I am), you probably already have this version of Python. However, I strongly recommend following the [Hitchhiker's Guide to Python](http://docs.python-guide.org/en/latest/starting/install/osx/) directions to install and use something other than your system Python.

If your using a Windows machine, I don't have any advise for you (sorry). Check out the [official Python 2.7 docs](https://docs.python.org/2.7/using/windows.html) and the recommendations in the [Hitchhiker's Guide](http://docs.python-guide.org/en/latest/starting/install/win/).

If your using some Linux distribution...well, then you're probably cleverer than I am and already know what to do.

Regardless of your choice of operating system, best practice for Python projects like this is to install them within a contained virtual environment.

[virtualenv](https://virtualenv.pypa.io/en/stable/) and its companion [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/index.html) are very popular modules for this purposes. Once again, the [Hitchhiker's Guide](http://docs.python-guide.org/en/latest/dev/virtualenvs/) has [great walk-through](http://docs.python-guide.org/en/latest/dev/virtualenvs/) on installing and configuring these modules.
