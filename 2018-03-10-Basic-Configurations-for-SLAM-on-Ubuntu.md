---
layout: post-new
title: Basic Configurations on Ubuntu 16.04 LTS for SLAM Systems (Updating)
category: SLAM
tags: [SLAM, Linux] 
comments: true
---

* content
{:toc}


The blog mainly summuries some basic configurations under Ubuntu 16.04 LTS on my laptop (Thinkpad T460s) for SLAM-related projects.








### Packages
#### 1. Sougou Pinyin Input - Chinese 
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

#### 2. ROS
Refer to [kinetic ROS](http://wiki.ros.org/kinetic/Installation/Ubuntu)

#### 3. Pangolin
Refer to [Pangolin](https://github.com/stevenlovegrove/Pangolin)

#### 4. OpenCV
Refer to  [OpenCV](http://opencv.org) and 
[Install OpenCV3 on Ubuntu](https://www.learnopencv.com/install-opencv3-on-ubuntu/)

#### 5. Eigen3
The first way is referring to [Eigen](http://eigen.tuxfamily.org/), and download the Eigen2/3 package，then compile on the laptop。

Another way is using the following commands to install, but you should remeber to **change the default path**.

```
sudo apt-get install libeigen3-dev 
cd /usr/include/eigen3
sudo cp Eigen -r /usr/include
```

#### 6. DBoW2
Refer to [DBoW2](https://github.com/dorian3d/DBoW2)

However, it's normal that many popular SLAM repositories provide "**DBoW2**" in their **3rdparty** folder.

#### 7.  g2o
[g2o](http://opencv.org.) is a very important package on graph optimization. It requires Cmake and Eigen3.

On Ubuntu / Debian some other dependencies are resolved by installing the following packages: **libsuitesparse-dev, qtdeclarative5-dev, qt5-qmake, libqglviewer-dev**.

Moreover, you may refer to [1-3] to find more useful information about how to install and test g2o.



### Supported Open Source SLAM Systems after the above Configurations
[1] [ORB-SLAM2](https://github.com/raulmur/ORB_SLAM2)




### References:
1. [第六讲 图优化工具g2o的入门](http://www.cnblogs.com/gaoxiang12/p/4739934.html)
2.  [在Ubuntu KyLin 16.04上安装g2o](http://blog.csdn.net/zpp13hao1/article/details/53942589)
3. [g2o的安装及初步使用](http://blog.csdn.net/jasmine_shine/article/details/50205503)
