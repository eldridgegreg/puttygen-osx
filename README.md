puttygen-osx
============

Xcode project for building puttygen command line tool for Mac OS X.

https://github.com/eldridgegreg/puttygen-osx

[PuTTY](http://www.chiark.greenend.org.uk/~sgtatham/putty/) is an amazingly good project that does pretty much everything you'll ever need to use SSH on Windows.  However, its PPK files are incompatible with the standard SSH key format used on Mac OS X (and every other Unix-y OS I've ever used).  It includes an easy utility to convert in and out of PPK format, but it only runs on Windows by default.  You can compile PuTTY source on Mac if you have MacPorts installed - I don't and didn't want to.

This project simply packages puttygen from the PuTTY 0.62 source in a convenient Xcode project.  This eliminates the need for MacPorts or other make utilities.  I have also provided a binary distribution for those users who do not have Xcode or wish to compile themselves (see the Downloads tab).

The binary is 64 bit, and has only been tested (limitedly) on Mac OS X 10.7.4.  I am happy to provide other binary versions if requested, but cannot test on older Mac OS X version very easily.  If you run into any problems, please comment on github or email me at greg@desult.com, and I will do my best to help.

All project files that I have produced to enable this project are public domain.  I claim no copyright in them and you are free to use/abuse them as you please.

All PuTTY source files are copyright their original authors.  See puttygen-osx/LICENCE for details on the license terms for relevant PuTTY source.