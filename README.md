# fortran2python

Inspired by https://www.matecdev.com/posts/fortran-in-python.html

On Mac OS:
- Install gfortran `brew install gfortran`
- Convert fortran file to python lib `f2py3 -c -m myflib my_fortran_lib.f90`
- Execute `python call_fortran.py`
