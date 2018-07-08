---
layout: post-new
title: Installing Dependencies on Ubuntu 16.04 LTS towards SLAM Projects (Updating)
category: SLAM
tags: [SLAM, Linux] 
comments: true
---

* content
{:toc}


The blog mainly summuries some basic configurations and installing dependencies under Ubuntu 16.04 LTS on my laptop (Thinkpad T460s) towards SLAM-related projects.


-------------

### Dependencies
Generally, after your installing dependencies/packages, the header files ('.hpp') are usually under the folder `/usr/local/include/dependency_name/`, and the library files are usually under the folder `/usr/local/lib/`. Therefore, when you finish installation steps, you could check whether the corresponding files are under the correct path. Or you could search some test code online to test if it could call packages and run correctly. 

However, if you compile or run the specific code with errors on those packages, you should check the version of those necessary packages, and the pre-set path. If it still does not work, you could turn to your best friend -- Google to find the corresponding dependencies or alternatives to fix issues.



#### 1. ROS
Refer to [kinetic ROS](http://wiki.ros.org/kinetic/Installation/Ubuntu)

#### 2. Pangolin
Refer to [Pangolin](https://github.com/stevenlovegrove/Pangolin)

#### 3. OpenCV
Refer to  [OpenCV](http://opencv.org) and 
[Install OpenCV3 on Ubuntu](https://www.learnopencv.com/install-opencv3-on-ubuntu/)

#### 4. Eigen3
The first way is referring to [Eigen](http://eigen.tuxfamily.org/), and download the Eigen2/3 package，then compile on the laptop。

Another way is using the following commands to install, but you should remeber to **change the default path**.

```
sudo apt-get install libeigen3-dev 
cd /usr/include/eigen3
sudo cp Eigen -r /usr/include
```

#### 5. Sophus
Sophus supports Lie Algebra, which is the C++ implementation of Lie Groups using Eigen. Here we would install the (non-template version) [Sophus](https://github.com/strasdat/Sophus) maintained by Strasdat.

Via the following command line instructions to install Sophus:

```
git clone https://github.com/strasdat/Sophus.git
cd Sophus/
git checkout a621ff

mkdir build
cd build
cmake ..
make
```


#### 6. PCL (Point Cloud Library)
Refer to official guide in [PCL](http://pointclouds.org/), or use the following commands:

```
sudo apt-get install libpcl-dev

//install visualization tools and open a '.pcd' file
sudo apt install pcl-tools
pcl_viewer XXX.pcd
```



#### 7.  g2o
[g2o](https://github.com/RainerKuemmerle/g2o) is a very important package on graph (non-linear) optimization in SLAM applications. It requires Cmake and Eigen3.

First, on Ubuntu / Debian some other dependencies are resolved by installing the following packages:  

```
sudo apt-get install libqt4-dev qt4-qmake libqglviewer-dev libsuitesparse-dev libcxsparse3.1.4 libcholmod3.0.6 
```

Next, you should download g2o from github, unzip the file, enter the g2o folder with the following commands to compile this Cmake project:

```
mkdir build
cd  build
cmake ..
make 
sudo make install
```

Moreover, you may also refer to [1-3] to find more useful information about how to install and test g2o.

#### 8. Ceres
[Ceres](https://github.com/ceres-solver/ceres-solver)is another very important package on non-linear optimization in SLAM applications besides g2o.  

First, on Ubuntu / Debian some other dependencies are resolved by installing the following packages:

```
sudo apt-get install liblapack-dev libsuitesparse-dev libcxsparse3.1.4 libgflags-dev libgoogle-glog-dev libgtest-dev
```

Next, you should download g2o from github, unzip the file, enter the g2o folder with the following commands to compile this Cmake project:

```
mkdir build
cd  build
cmake ..
make 
sudo make install
```


#### 9. DBoW2
Refer to [DBoW2](https://github.com/dorian3d/DBoW2)

However, it's normal that many popular SLAM repositories provide "**DBoW2**" in their **3rdparty** folder.



----------
### Misc: Packages
#### 1. C/C++ IDE
- Clion
- Kdevelop

#### 2. Sougou Pinyin Input - Chinese 
First, install "GDebi" with

```
sudo apt-get install gdebi
```

Then search and download the Sougou package for Ubuntu/Debian. Next, enter the correspoding folder and use

```
sudo gdebi sogoupinyin_2.2.0.0102_amd64.deb
```

to install Sougou Pinyin Input. At last, change the keyboard settings to add the sougou pinyin.
Remeber to restart or suspend to make it work.



### Supported Open Source SLAM Systems after the above Configurations
1. [ORB-SLAM2](https://github.com/raulmur/ORB_SLAM2)
2. 视觉SLAM十四讲练习/practice code of the "14 lectures on visual SLAM"，[English Version](https://github.com/gaoxiang12/slambook-en)，[中文版](https://github.com/gaoxiang12/slambook)




### References:
1. [第六讲 图优化工具g2o的入门](http://www.cnblogs.com/gaoxiang12/p/4739934.html)
2.  [在Ubuntu KyLin 16.04上安装g2o](http://blog.csdn.net/zpp13hao1/article/details/53942589)
3. [g2o的安装及初步使用](http://blog.csdn.net/jasmine_shine/article/details/50205503)
