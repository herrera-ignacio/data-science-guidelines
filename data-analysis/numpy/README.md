# Numpy

Python open-source package for scientific computing, adding support for large, multi-dimensional arrays and matrices, along with a collection of high-level mathematical functions to operate on these arrays.

It targets CPython reference implementation. Mathematical algorithms writtn for this version of Python often run much slower than compiled equivalents. NumPy ddresses the slowness problem partly by providing multidimensional arrays and functions and operators that operate efficiently on those data structures.

## n-dimensional-array (ndarray)

The core functionality of NumPy is its "__ndarray__" data structure. These arrays are _strided views_ on memory, and are homogeneously typed.

#### Limitations

Inserting or appending entries to an array is not as trivially possible as it is with Python's lists.