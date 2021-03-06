Module 1
=========

The videos are recorded with at least 1K resolution but the default
resolution when you open it in your browser may be lower than this. You
can manually select a higher resolution if your device and network
bandwidth support it.

Learning goals
---------------
- Have a working Jupyter notebook (or Jupyter lab) environment.
- Understand how to download, run, modify and save a Jupyter notebook file.
- Understand the computer representation of integer and floating point numbers.
- Concrete understanding of scalar, vector and matrix.
- Have working knowledge of various numpy date types.
- Know how to store and retrive files using HDF5 format via `h5py`
- Learn how to read numpy documentation


Video Lectures and Jupyter notebooks
------------------------------------

-   Using Jupyter notebook

    - How to launch Jupyter notebook: [video](https://drive.google.com/open?id=1GsqeLggLkij__xaCp7ncvtCq9VX-aND6)


-   Number representation

    - Unsigned integer: [video](https://drive.google.com/open?id=1ZRwuLeYNtDfAnDLDTuuPVktCeHIcMu54)
    - Signed integer: [video](https://drive.google.com/open?id=1TywujJ5eJT356X-BQPVBX1cPYOc0K3Zg)
    - The summation notation: [video](https://drive.google.com/open?id=1Ik10kG3KkVhOx1eVVG2N3c3YcWr5Ct8M)
    - Numpy demo of integers: [video](https://drive.google.com/open?id=1sEE6G2oU1lAGzaHasF1qS3tT-OO2yJIs) | [Jupyter notebook](../ipynb/ch1/signed-vs-unsigned-int.ipynb)
    - Floating point numbers: [video](https://drive.google.com/open?id=1eekW-LJfrDSBGLMGSUIxug87TLfo0hfQ)
    - Numpy demo of floating point numbers: [video](https://drive.google.com/open?id=1t3zD5dqlFj2moXi3emBUV0VPew6Ie1e3) | [Jupyter notebook](../ipynb/ch1/fp-representation.ipynb)


-   Vector and Matrix

    - Scalar, vector and matrix: [video](https://drive.google.com/open?id=1J3dRr6Bq9Gqe8-QeGnrbXkeYBqjTFlnh)
    - Numpy demo: [video](https://drive.google.com/open?id=1QXUoYlUfZwX4ZUZnj0hyJPf8_GF8bN2u) | [Jupyter notebook](../ipynb/ch1/vector-and-matrix-basics.ipynb)
    - Index of vector and matrix: [video](https://drive.google.com/open?id=1aA-XtU5WSrsCrO2M2zSzz_8xUquB-uYs)
    - A matrix-vector multiplication example: [video](https://drive.google.com/open?id=1QFAPLd00g_T7XKGpbDyWYAhgMHuBW382) | [demo](https://drive.google.com/open?id=1UxbzF59LnDRWbPDrLa1qF8owkvrkJKF6) | [Jupyter notebook](../ipynb/ch1/matrix-vector-multiplication-demo.ipynb)
    - Matrix-vector multiplication example -- neural net weights: [video](https://drive.google.com/open?id=1cfaTgyXhhn6a-2qqOLIJK0JXfFQyhOiy)
    - Vector-vector multiplication example -- inner and outer products: [video](https://drive.google.com/open?id=1Ixsexw6oGRHxDcKAdUADCMi0Z0o9fOqt) | [Jupyter notebook](../ipynb/ch1/vector-vector-product.ipynb)

-   Save or load data using `h5py`

    - Example: [video](https://drive.google.com/open?id=1fFt5D34Tvtp_VTpbuzsrRyqmgOb2zwg4) | [Jupyter notebook](../ipynb/ch1/save-load-arrays-h5py.ipynb)

Additional readings
-------------------

-   Jupyter notebook: <https://jupyter.org/>
-   Floating point representation: <https://en.wikipedia.org/wiki/IEEE_754>
-   Numpy data types: <https://docs.scipy.org/doc/numpy/user/basics.types.html>
-   Numpy iinfo(): <https://docs.scipy.org/doc/numpy/reference/generated/numpy.iinfo.html#numpy.iinfo>
-   Numpy finfo(): <https://docs.scipy.org/doc/numpy/reference/generated/numpy.finfo.html>
-   h5py: <https://www.h5py.org/>
-   HDF5: <https://www.hdfgroup.org/solutions/hdf5/>

Exercises
---------

1.  What *signed* integer is represented by the 8-bit binary notation 11001100?
2.  What *unsigned* integer is represented by the 8-bit binary notation 11001100?
3.  What is the maximum 16-bit *signed* integer?
4.  What is the smallest number of bits to represent the positive integer 1025?
5.  What is the smallest number of bits to represent the negative integer -1025?
