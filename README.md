# Navigation and Registration using PCL

[![ROS](https://img.shields.io/badge/ROS-Noetic-brightgreen)](https://wiki.ros.org/noetic)
[![C++](https://img.shields.io/badge/C++-11-blue)](https://www.cplusplus.com/)
[![PCL](https://img.shields.io/badge/PCL-1.4.0-red)](https://pointclouds.org/)

## Description

A C++ project that performs 3D point cloud registration using the Iterative Closest Point (ICP) algorithm from the Point Cloud Library (PCL). Useful for aligning scans in SLAM and navigation tasks.

* ROS-Boxer UGV tutorials: https://www.clearpathrobotics.com/assets/guides/noetic/boxer/index.html  
* ICP algorithm: How to incrementally register pairs of clouds: https://pcl.readthedocs.io/projects/tutorials/en/latest/pairwise_incremental_registration.html

## Installation

```bash
git clone https://github.com/josgarvil/Navigation-Registration-PCL.git
cd Navigation-Registration-PCL/ICP

mkdir build && cd build
cmake ..
make
```

Requires PCL (libpcl-dev) to be installed.

## Usage

```bash
./pairwise_incremental_registration
```

* Loads point clouds
* Runs ICP registration
* Outputs the merged cloud to output.pcd

## Technologies

* C++
* Point Cloud Library (PCL)
* ICP Registration

## Author
José García Villalón

