# Module 3

## Learning goals

- Interpolation fundamentals
- Linear regression fundamentals
- Additional discussions of Matplotlib plotting


## Interpolation

-   Linear interpolation:

    -   Concept: [video](https://drive.google.com/open?id=1py23zkYE25dxevltNfK6iI5Evdv3ADIp)
    -   Demo: [video](https://drive.google.com/open?id=1ahwpz7aUoiNPHYnshAcjnMxomq_Czyf1) | [Jupyter notebook](../ipynb/ch3/interpolation-1d.ipynb)

    High-order interpolation:

    -   Choosing different kinds of interpolation: [video](https://drive.google.com/open?id=18BAcjXrfmSk9Frp2NpqKk-lzvKlmWkEy) | [Jupyter notebook](../ipynb/ch3/interp1d-orders.ipynb)
    -   Data outside of interpolation domain: [video](https://drive.google.com/open?id=1R7n_xtzjOUv7seJY4D0XzgLbnWVcFT9S) (see the notebook above)

## Regression

-   Linear regression (least squares):

    -   Concept: [video](https://drive.google.com/open?id=1MCrTP9tf-n2NEB1R6c57nVEbybLXl_On)
    -   Demo: [video](https://drive.google.com/open?id=1Z5BP5UByFJ-FkDGKzZojNPT_u6_cGhPC) | [Jupyter notebook](../ipynb/ch3/linear-regression.ipynb)

## Further readings

-   `argsort()`: <https://docs.scipy.org/doc/numpy/reference/generated/numpy.argsort.html>
-   `searchsorted()`: <https://docs.scipy.org/doc/numpy/reference/generated/numpy.searchsorted.html>
-   `interp1d()`: <https://docs.scipy.org/doc/scipy/reference/generated/scipy.interpolate.interp1d.html>
-   `linspace()`: <https://docs.scipy.org/doc/numpy/reference/generated/numpy.linspace.html>
-   `solve()`: <https://docs.scipy.org/doc/numpy/reference/generated/numpy.linalg.solve.html>

## Assignments

Assignment explanation: [video](https://drive.google.com/open?id=1No26tprQwsrAskonM6iet4WYoyq6Ac1C)

### Problem 1

John is running a marathon. The speed measured at the following
locations are:

```
location    speed
1 mile      6.0
2 mile      6.5
3 mile      6.2
4 mile      5.5
5 mile      6.0
```

Write a Python code that uses linear interpolation between two adjacent
locations (e.g. 2-mile and 3-mile locations) to estimate John\'s speed
at the following locations: \[1.25, 2.2, 3.5, 4.75\] (miles). Upload
your code to Canvas.

### Problem 2

Download this the file
[ex2.h5](../../../../raw/master/src/ipynb/ch3/ex2.h5)
which contains the x,y coordinates of a data set. You can read the x and
y values using the command:

```python
import h5py
f = h5py.File('ex2.h5', 'r')
x = f['x'][:]
y = f['y'][:]
f.close()
# at this point, you can use x and y as numpy arrays
```

Answer the following questions:

1.  What is the dimension of x?
2.  Using the x,y data, compute best fit line using the linear
    regression procedure discussed in the class.
3.  Plot the linear-regression line on top of the data points.
4.  Submit your code and plot (screenshot is fine), similar to what we
    did in the lecture, to Canvas.

