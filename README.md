# Navigation and Registration using PCL

## 🧠 Description

A C++ project that performs 3D point cloud registration using the Iterative Closest Point (ICP) algorithm from the Point Cloud Library (PCL). Useful for aligning scans in SLAM and navigation tasks.

* ROS-Boxer UGV tutorials: https://www.clearpathrobotics.com/assets/guides/noetic/boxer/index.html  
* ICP algorithm: How to incrementally register pairs of clouds: https://pcl.readthedocs.io/projects/tutorials/en/latest/pairwise_incremental_registration.html

## 🔧 Installation

```bash
git clone https://github.com/josgarvil/Navigation-Registration-PCL.git
cd Navigation-Registration-PCL

mkdir build && cd build
cmake ..
make
```

Requires PCL (libpcl-dev) to be installed.

## 🚀 Usage

```bash
./nav_register ../data/pointcloud1.pcd ../data/pointcloud2.pcd
```

* Loads two point clouds
* Runs ICP registration
* Outputs the merged cloud to output.pcd

## 📁 Project Structure

```arduino
Navigation-Registration-PCL/
├── src/
│   ├── main.cpp
│   ├── navigation.cpp
│   └── navigation.h
├── data/
│   ├── pointcloud1.pcd
│   └── pointcloud2.pcd
```
## 🛠️ Technologies

* C++
* Point Cloud Library (PCL)
* ICP Registration

## 👨‍💻 Author
José García Villalón – GitHub

