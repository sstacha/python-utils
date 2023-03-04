# python-utils-core
Extracting common python utilities I re-use between all projects.  My intent is to have minimal dependencies
so the library can be used by django settings without circular references.  I also have color logging class for
jupyter notebooks.  I will have a couple of libraries that will extend this functionality.  The main one for working
with web pages is the python-utils-requests library.  Scan the test cases in the tests folder for common use cases.

python-utils-core:
- basic conversion helper utilities
- color logging without dependencies
- manipulating urls and their parameters

python-utils-requests:
dependency: requests library
- helper functions to pull data from web services into basic datatypes like string or dict

