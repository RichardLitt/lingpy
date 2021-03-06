# QLC-LingPy

Authors: Johann-Mattis List and Steven Moran, Research Unit: [Quantitative Language Comparison](http://www.quanthistling.info/), University of Marburg.

QLC-LingPy is a Python Library for Historical Linguistics that is under development. It is being developed in Python 3.

Available at: (https://github.com/lingpy/lingpy)

For a brief overview, see slides from Euroscipy 2012 ("best paper award"): (http://hprints.org/hprints-00758536)

Other relevant work related to the development of the library and research using it, include:

List, J. M. Forthcoming. Sequence comparison in historical linguistics. PhD dissertation, University of Düsseldorf.

List, J. M. 2012a. Multiple sequence alignment in historical linguistics: a sound class based approach. In Proceedings of Console IXX.

List, J. M. 2012b. SCA: Phonetic alignment based on sound classes. In New Directions in logic, language, and computation. Slavkovik, M. and D Lassiter (Eds.). Springer.

Prokic, J. and S. Moran. 2012. Black box approaches to genealogical classication and their shortcomings. To appear in Comparing Approaches to Measuring Linguistic Dierences, Lars Borin and Anju Saxena (eds). Mouton De Gruyter. 


## Setup

To use the library in its pre-setup.py stage, git clone the library and either put the library's "lingpy/lingpy" folder your path (or Python path).

Alternatively, you can make a symlink in your Python 3 site-packages folder called "lingpy" and link it to "lingpy/lingpy". For example:

1. Start the Python interpreter (make sure you are using Python 3)

$ python

2. At the prompt, locate the site-packages folder:

>>> import sys
>>> print(sys.path)
['', '/opt/local/Library/Frameworks/Python.framework/Versions/3.2/lib/python3.2', '/opt/local/Library/Frameworks/Python.framework/Versions/3.2/lib/python3.2/site-packages']

3. Create the symlink (you may need sudo):

ln -s /path/to/lingpy/lingpy /path/to/site-packages/symlink

4. Test in interpreter:

$ python
>>> import lingpy














