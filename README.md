# eigenpy [![Build Status](https://travis-ci.org/ipab-slmc/eigenpy_catkin.svg?branch=master)](https://travis-ci.org/ipab-slmc/eigenpy_catkin)

**DEPRECATED** This repository wraps and releases version 1.5 of [eigenpy](https://github.com/stack-of-tasks/eigenpy) for use in catkin-based projects.

# IMPORTANT NOTE

The upstream project has been fixed and made compatible with catkin. As thus, we are in the process of deprecating this wrapper. Please use [eigenpy](https://github.com/stack-of-tasks/eigenpy) directly in your catkin workspace. You can include it via

```cmake
find_package(PkgConfig)
pkg_check_modules(eigenpy REQUIRED eigenpy)
include_directories(${eigenpy_INCLUDE_DIRS})
```
