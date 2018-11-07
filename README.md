# Python/Numpy for High-Performance Numerical Processing

Notebooks and slides used for the [Numpy mini-course at Princeton](https://researchcomputing.princeton.edu/events/pythonnumpy-high-performance-numerical-processing) held November 15, 2018.

### Abstract

Python is a notoriously slow language, so why is it widely used by scientists and machine learning experts? In a numerically heavy task, an interpreted, dynamically typed environment can be thousands of times slower than a compiled, statically typed one, which can make the difference between minutes and days or between coarse models on small datasets and fine-grained models on large datasets. The trick is to drive compiled functions from the interpreted commandline, like R, and to frame your problem in array programming primitives, like Matlab, but in a general-purpose programming language with hundreds of thousands of extensions to glue to every conceivable interface.

In this workshop, we will examine the numerical processing ecosystem that has grown up around Python. The key library in this ecosystem is Numpy, which enables fast array programming, and Pandas, a convenient wrapper for organizing data. We will visualize data in and out of JupyterLab, a notebook front-end for exploratory analysis. We'll also work through examples of binding from C++ to Python with pybind11 and from Python to C++ with Cython, which have different strengths and use-cases. We'll also natively compile Python (C++ speeds without C++) using Numba and run code on GPUs with Numba (Python-like), CuPy (Numpy-like), and PyCUDA/PyOpenCL (raw CUDA/OpenCL).

Participants will be encouraged to bring a laptop or log into their favorite cluster to install the software we discuss here for later use. We will use conda and pip-in-conda, so superuser ("sudo") permissions are not required.

Jim Pivarski received his Ph.D. in high-energy particle physics from Cornell in 2006. He helped to commission the CMS experiment at the LHC and later switched to data science as a Big Data consultant. He is now back in physics, integrating computing techniques learned from industry into high-energy physics analysis.

### Plan for the day

![](img/plan-for-the-day.png)
