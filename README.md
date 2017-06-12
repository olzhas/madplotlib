Madplotlib
==========

A C++ wrapper of Qt Charts that looks, tastes and smells like [matplotlib](https://github.com/matplotlib/matplotlib) but isn't.

Madplotlib is a C++ header-only library that provides simple 2D plot capabilities, similar to [matplotlib](https://github.com/matplotlib/matplotlib) for Python. Madplotlib uses Qt Charts behind your back to render cool looking ~~cats~~ graphs that are easy to create with the help of [Eigen](eigen.tuxfamily.org).

Installation
------------
Make sure to use **Qt 5.7** or higher and that you have **Eigen 3.x** properly installed. 
After that, just add **Madplotlib.h** to your projects and don't worry about anything else. 
We got your back, Jack!

Testing
-------
The companion ~~cube~~ file **eigen_tests.cpp** demonstrates several features offered by this library.
Each test case is heavily commentted to make sure you know what it is doing and how. They are a great reference to get you quickly started. By the way, did I mention it resembles [matplotlib](https://github.com/matplotlib/matplotlib)? Did I?!?

Contribute
----------
There's a ginormous number of things I would like to incorporate into this library, including a damn good documentation. **;)** If you are strong with the Force and would like to contribute to this project, I recommend this hands-on guide to [Github-Forking](https://gist.github.com/Chaser324/ce0505fbed06b947d962) to learn the technical shenanigans.
Remember: when in doubt, do not clone... fork!

Contact
-------
[Twitter](http://twitter.com/karlphillip) 
[Stackoverflow](http://stackoverflow.com/users/176769/karlphillip)

Library features
----------------
* Data for plotting must be created through `Eigen::ArrayXf`;
* Draw lines, scatter plots, or both, simultaneously and at the same time:
  * Lines can be continuous, made of dashes or even dots;
  * Circular or squared markers can be used on scatter plots;
* It supports multiple series of data;
* Title, labels, legends and more can be specified;
* Color support for lines and markers;
* Persistence: save your charts on the disk (PNG/JPG);
* Define limits for your axis;
* Show/hide axis ticks or background grid;
* Charts block execution flow when they are `show()` to mimic `plot()` from matplotlib (but this can be disabled);
 