# RecursiveFilters
Recursive filter implementations which works on digital samples. In signal processing, a recursive filter is a type of filter which re-uses one or more of its outputs as an input. The discrete-time implementation of a simple low-pass filter is equivalent of the exponentially weighted moving average.

### Build
Includes a simple makefile for the C++ build. Tested in Debian Stretch with g++ 6.3.0 and the plotter script with Python 3.5.3.

### Already implemented filters:
**Low-pass filter**

https://en.wikipedia.org/wiki/Low-pass_filter

**Exponentially weighted moving average**

https://en.wikipedia.org/wiki/Exponential_smoothing

**High-pass filter**

https://en.wikipedia.org/wiki/High-pass_filter

![alt text](https://raw.githubusercontent.com/janohhank/RecursiveFilters/master/doc/sinus-with-noise.png)

![alt text](https://raw.githubusercontent.com/janohhank/RecursiveFilters/master/doc/linear-with-noise.png)