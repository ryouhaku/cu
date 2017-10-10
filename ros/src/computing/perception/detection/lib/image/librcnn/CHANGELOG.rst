^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package librcnn
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.4.0 (2017-08-04)
------------------

1.3.1 (2017-07-16)
------------------

1.3.0 (2017-07-14)
------------------

1.2.0 (2017-06-07)
------------------

1.1.2 (2017-02-27 23:10)
------------------------

1.1.1 (2017-02-27 22:25)
------------------------

1.1.0 (2017-02-24)
------------------

1.0.1 (2017-01-14)
------------------

1.0.0 (2016-12-22)
------------------
* Added SSD node to CV Tracker
* Fix include path and linked library setting issue on Ubuntu 15.04
  Paths of header files and libraries of libhdf5 and CUDA on Ubuntu 15.04 are
  different from Ubuntu 14.04. And those paths are set explicitly at compiling
  time on Ubuntu 15.04.
  And clean up CMake codes by using CMake and pkg-config features instead of
  absolute paths.
* Remove needless dependencies
* updated to search for libraries in caffe path instead of /usr...
* Updated to compile rcnn only if caffe and fast rcnn are installed
* Updated according to Yosh's suggestions.
  Added README
* As suggested by @syohex
  Thanks
* Removed local references
  added $ENV{HOME} as suggested.
* Added files for RCNN node
* Contributors: AMC, Syohei YOSHIDA
