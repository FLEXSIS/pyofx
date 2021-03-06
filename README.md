PYOFX
=====

[![Coverage Status](https://coveralls.io/repos/github/FLEXSIS/pyofx/badge.svg?branch=master)](https://coveralls.io/github/FLEXSIS/pyofx?branch=master) 
[![Build Status](http://jenkins.ael.onl:8080/job/pyofx/badge/icon)](http://jenkins.ael.onl:8080/job/pyofx/)
[![PyPI](https://img.shields.io/pypi/v/pyofx.svg)](https://pypi.python.org/pypi/pyOfx)
[![PyPI](https://img.shields.io/pypi/status/pyofx.svg)]()
[![PyPI](https://img.shields.io/pypi/l/pyofx.svg)](https://pypi.python.org/pypi/pyOfx)
[![PyPI](https://img.shields.io/pypi/pyversions/pyofx.svg)](https://pypi.python.org/pypi/pyOfx)

### A wrapper around [Orcina's OrcFxAPI](https://pypi.python.org/pypi/OrcFxAPI)

**You will need to have OrcaFlex and the Python API installed before any of this will work**

Documentation can be found at [pythonhosted.org/pyOfx/](http://pythonhosted.org/pyOfx/)

TODO
====

* implement Models failed_function
* Complete Documentation
* improve test coverage
* Improve the way Jobs works


CHANGELOG
=========
0.1.5 - add tox, coveralls and jenkins
0.1.4 - fix the pypandoc rubbish, a retry_on_licence_error decorator exists (but is untested)
0.1.3 - update readme to point to OrcFxAPI on pypi, remove mindless import at top of module.
0.1.2 - fixing issues with setup.py  
0.1.1  - Support for OrcaFlex 10.0  
0.1.0  - Added python 3 support  
0.0.16 - Added Documentation (no really!) fixed the drawing helpers [#2](https://github.com/FLEXSIS/pyofx/issues/2)   
0.0.15 - Added clipboard support to vessel_drawing  
0.0.14 - Fix for [#1](https://github.com/FLEXSIS/pyofx/issues/1)  
0.0.13 - Added Model.lines, Model.vessels, Model.six_d_buoys attributes
         various performance enhancements  
0.0.12 - Fixed test for string in objects_of_type to include unicode,
	     addeed yml option to dat_sim_paths  
0.0.11 - Added buoy_drawing  
0.0.10 - Added gamma_dnv function  

The MIT License (MIT)

Copyright (c) 2017 FLEXSIS

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.