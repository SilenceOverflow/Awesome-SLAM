# Awesome-SLAM 
A curated list of SLAM resources

#### Stay Tuned for Constant Updates

> Last updated: Mar. 29th,  2019. 

The repo is maintained by [Youjie Xia](https://github.com/YoujieXia). The repo mainly summuries the awesome repositories relevant to SLAM/VO on GitHub, including those on the PC end, the mobile end and some learner-friendly tutorials. 

Regrading awesome SLAM papers, please refer to [**Awesome-SLAM-Papers**](https://github.com/YoujieXia/Awesome-SLAM-Papers).

If you want to know more about dependencies/packages of SLAM systems, please refer to [Installing Dependencies on Ubuntu 16.04 LTS towards SLAM Projects (Updating)](https://youjiexia.github.io/2018/03/10/Installing-Dependencies-on-Ubuntu-towards-SLAM-Projects/).

If you think this repo is useful, please ***watch***, ***star*** or ***fork*** it!

Welcome to contribute to this repo, if you are interested in SLAM! Feel free to creat a pull request or contact me.


> 
> Note: Name Format - `repository name: one-sentence introduction` (with link to the corresponding repo)
>

------

## TOC

* [Hot SLAM Repos on GitHub](#hot-slam-repos-on-github)
* [PC End SLAM](#pc-end-slam)
  * [Visual SLAM](#visual-slam)
  * [Visual Inertial SLAM](#visual-inertial-slam)
* [Mobile End SLAM](#mobile-end-slam)
* [Tutorials](#tutorials)
	* [General](#general)
	* [Lie Algebra and Lie Groups](#lie-algebra-and-lie-groups)
	* [Optimization Techniques](#optimization-techniques)
* [Selected Blogs](#selected-blogs)
* [Organizations](#organizations)

------

## Hot SLAM Repos on GitHub
0. [Awesome-SLAM: Resources and Resource Collections of SLAM](https://github.com/YoujieXia/Awesome-SLAM)
1. [awesome-slam: A curated list of awesome SLAM tutorials, projects and communities.](https://github.com/kanster/awesome-slam)
2. [SLAM: learning SLAM,curse,paper and others](https://github.com/liulinbo/slam)
3. [A list of current SLAM (Simultaneous Localization and Mapping) / VO (Visual Odometry) algorithms](https://github.com/kafendt/List-of-SLAM-VO-algorithms)
4. [awesome-visual-slam: The list of vision-based SLAM / Visual Odometry open source, blogs, and papers](https://github.com/tzutalin/awesome-visual-slam)
5. [Lee-SLAM-source: SLAM 开发学习资源与经验分享](https://github.com/AlbertSlam/Lee-SLAM-source)
6. [awesome-SLAM-list](https://github.com/OpenSLAM/awesome-SLAM-list)
7. [VIO-Resources](https://github.com/hhmaizi/VIO-Resources/blob/master/resources4vio)

## PC End SLAM
### Visual SLAM
#### General 
1. [BreezySLAM: Simple, efficient, open-source package for Simultaneous Localization and Mapping in Python, Matlab, Java, and C++](https://github.com/simondlevy/BreezySLAM)

#### Monocular Visual SLAM
1. [ORB_SLAM: A Versatile and Accurate Monocular SLAM ](https://github.com/raulmur/ORB_SLAM)

#### Stereo Visual SLAM
1. [ORB_SLAM2](https://github.com/raulmur/ORB_SLAM2)
2. [ORBSLAM2_with_pointcloud_map](https://github.com/gaoxiang12/ORBSLAM2_with_pointcloud_map)
3. [PL-SLAM: a Stereo SLAM System through the Combination of Points and Line Segments](https://github.com/rubengooj/pl-slam)
4. [StVO-PL: Stereo Visual Odometry by combining point and line segment features](https://github.com/rubengooj/StVO-PL)
5. [stereo-dso: Direct Sparse Odometry with Stereo Cameras](https://github.com/JiatianWu/stereo-dso)
6. [S-PTAM: Stereo Parallel Tracking and Mapping](https://github.com/lrse/sptam)
7. [Robust Stereo Visual Odometry](https://github.com/famoreno/stereo-vo)
8. [ProSLAM: Graph SLAM from a Programmer's Perspective](https://gitlab.com/srrg-software/srrg_proslam)

#### RGB-D Visual SLAM

### Visual Inertial SLAM
#### General 
1. [maplab: An open visual-inertial mapping framework.](https://github.com/ethz-asl/maplab)

#### Monocular Visual-Inertial SLAM
1. [ROVIO (Robust Visual Inertial Odometry)](https://github.com/ethz-asl/rovio)
2. [OKVIS: Open Keyframe-based Visual-Inertial SLAM (ROS Version)](https://github.com/ethz-asl/okvis_ros)
3. [LearnVIORB: Visual Inertial SLAM based on ORB-SLAM2 (ROS Version)](https://github.com/jingpang/LearnVIORB), [LearnViORB_NOROS (Non-ROS Version)](https://github.com/OpenSLAM/LearnViORB_NOROS/tree/master/master/LearnVIORB_NOROS)

#### Stereo Visual-Inertial SLAM
1. [msckf_vio: Robust Stereo Visual Inertial Odometry for Fast Autonomous Flight](https://github.com/KumarRobotics/msckf_vio)
2. [ORBSLAM_DWO: stereo + inertial input based on ORB_SLAM](https://github.com/JzHuai0108/ORB_SLAM)
3. [LearnVIORBnorosgai2: Visual Inertial SLAM based on ORB-SLAM2 (Non-ROS Version)](https://github.com/ZuoJiaxing/LearnVIORBnorosgai2)
4. [ygz-stereo-inertial: a stereo-inertial visual odometry](https://github.com/gaoxiang12/ygz-stereo-inertial)


## Mobile End SLAM
1. [VINS-Mobile: Monocular Visual-Inertial State Estimator on Mobile Phones](https://github.com/HKUST-Aerial-Robotics/VINS-Mobile)
2. [ORB_SLAM2-iOS](https://github.com/ygx2011/ORB_SLAM2-IOS)
3. [ORB_SLAM-iOS](https://github.com/ygx2011/ORB_SLAM-IOS)
4. [MobileSLAM - LSD SLAM on Mobile Phone](https://github.com/xorthat/MobileSLAM)

### Depth Image API with iPhone 7 Plus (or newer)
1. [DepthAPISampleForiOS11](https://github.com/fromkk/DepthAPISampleForiOS11)
2. [AVDepthCamera](https://github.com/faceowener/AVDepthCamera)
3. [ios11-depth-map-test](https://github.com/xiangcong/ios11-depth-map-test)

## Tutorials
1. [Computer Vision/Geometric Fundamentals of SLAM](./Geometric-Fundamentals-of-SLAM.md)

### General
1. 视觉SLAM十四讲/14 lectures on visual SLAM，[English Version](https://github.com/gaoxiang12/slambook-en)，[中文版](https://github.com/gaoxiang12/slambook)
2. [Practice of the SlamBook](https://github.com/leftthomas/SlamBook)
3. [GraphSLAM_tutorials_code](https://github.com/HeYijia/GraphSLAM_tutorials_code)
4. [SLAM 开发学习资源与经验分享](https://github.com/AlbertSlam/Lee-SLAM-source)
5. [Visual SLAM/VIO 算法笔记](https://blog.csdn.net/MulinB/article/details/53421864)
6. [Probabilistic Robotics - Sapienza](https://sites.google.com/dis.uniroma1.it/probabilistic-robotics) by Giorgio Grisetti (2018)

### Lie Algebra and Lie Groups
1. [Lie groups for Computer Vision](http://ethaneade.com/lie_groups.pdf)
2. [Lie groups for 2D and 3D Transformations](http://ethaneade.com/lie.pdf)
3. [Hermite Splines in Lie Groups as Products of Geodesics](http://ethaneade.com/lie_spline.pdf)

### Optimization Techniques 
1. [Gauss-Newton/Levenberg-Marquardt Optimization](http://ethaneade.com/optimization.pdf)
2. [How a Kalman filter works, in pictures](http://www.bzarg.com/p/how-a-kalman-filter-works-in-pictures/)
3. [卡爾曼濾波 (Kalman Filter)](http://silverwind1982.pixnet.net/blog/post/167680859)
4. [翻譯 Understanding the Basis of the Kalman Filter Via a Simple and Intuitive Derivation](http://silverwind1982.pixnet.net/blog/post/171132644)

##  Selected Blogs
1. [The Future of Real-Time SLAM and Deep Learning vs SLAM](http://www.computervisionblog.com/2016/01/why-slam-matters-future-of-real-time.html)
2. [IMU Data Fusing: Complementary, Kalman, and Mahony Filter](http://www.olliw.eu/2013/imu-data-fusing/)

## Organizations
1. [泡泡机器人](http://www.slamcn.org/index.php)
