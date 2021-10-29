# fortran2python

Inspired by https://www.matecdev.com/posts/fortran-in-python.html

On Mac OS:
- Install gfortran `brew install gfortran`
- Convert fortran file to python lib `f2py3 -c -m myflib my_fortran_lib.f90`
- Execute `python call_fortran.py`:
```
[[ 0.54030231+0.84147098j -0.41614684+0.90929743j -0.9899925 +0.14112001j
  -0.65364362-0.7568025j ]
 [ 0.28366219-0.95892427j  0.96017029-0.2794155j   0.75390225+0.6569866j
  -0.14550003+0.98935825j]]
  ```
