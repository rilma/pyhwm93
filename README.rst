.. image:: https://travis-ci.org/scienceopen/pyhwm93.svg
    :target: https://travis-ci.org/scienceopen/pyhwm93
.. image:: https://coveralls.io/repos/github/scienceopen/pyhwm93/badge.svg?branch=master 
    :target: https://coveralls.io/github/scienceopen/pyhwm93?branch=master

============    
python-hwm93
============
NASA Horizontal Wind Model HWM93 in Python

.. contents::

.. image:: tests/example.png
    :scale: 25%

Installation
=============
::

    python setup.py develop

Example usage
=============
::
    
    python demo_hwm93.py

Optional Fortran-only use
=========================
::
   
    cd bin
    cmake ../fortran
    make


Reference
=========
Original A. E. Hedin Fortran 77 HWM93 code from 
ftp://hanna.ccmc.gsfc.nasa.gov/pub/modelweb/atmospheric/hwm93/
