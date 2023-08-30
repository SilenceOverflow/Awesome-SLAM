# Awesome-SLAM [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of SLAM resources

## Stay Tuned for Constant Updates

> Last updated: Mar. 14th, 2021. 

The repo is maintained by [Youjie Xia](https://github.com/YoujieXia). The repo mainly summarizes the awesome repositories relevant to SLAM/VO on GitHub, including those on the PC end, the mobile end and some learner-friendly tutorials. 

Regrading awesome SLAM papers, please refer to [**Awesome-SLAM-Papers**](https://github.com/YoujieXia/Awesome-SLAM-Papers).

If you want to know more about dependencies/packages of SLAM systems, please refer to [Installing Dependencies on Ubuntu 16.04 LTS towards SLAM Projects (Updating)](Misc/2018-03-10-Installing-Dependencies-on-Ubuntu-towards-SLAM-Projects.md).

If you think this repo is useful, please ***watch***, ***star*** or ***fork*** it!

Welcome to contribute to this repo, if you are interested in SLAM! Feel free to creat a pull request or contact me.


> Note: Name Format - `repository name: one-sentence introduction` (with link to the corresponding repo)

------

## Table of Contents

- [1. Hot SLAM Repos on GitHub](#HotRepos)
- [2. Visual SLAM](#VSLAM)
	- [2.1 Framework](#VFramework)
	- [2.2 Monocular](#VMono)
	- [2.3 Stereo](#VStereo)
	- [2.4 RGBD](#VRGBD)
	- [2.5 Others](#VOthers)
- [3. Visual Inertial SLAM](#VISLAM)
	- [3.1 Framework](#VIFramework)
	- [3.2 Monocular](#VIMono)
	- [3.3 Stereo](#VIStereo)
	- [3.4 RGBD](#VIRGBD)
	- [3.5 Others](#VIOthers)
- [4. LIDAR based SLAM](#LIDARSLAM)
	- [4.1 Framework](#LFramework)
	- [4.2 Others](#LOthers)
- [5. Learning based SLAM](#LSLAM)
	- [5.1 Survey](#LSurvey)
	- [5.2 Others](#LOthers5)
	- [5.3 Deep Features](#DeepFeat)
	- [5.4 Semantic SLAM](#Semantic)
- [6. Mobile End SLAM](#MSLAM)
	- [6.1 Visual SLAM](#MV)
	- [6.2 Visual Inertial SLAM](#MVI)
	- [6.3 Augmented Reality](#MAR)
	- [6.4 Others](#MOthers)
- [7. Datasets](#Datasets)
- [8. Tutorials](#Tutorials)
	- [8.1 3D Vision](#3DVision)
	- [8.2 Robotics](#Robotics)
	- [8.3 Lie Algebra and Lie Groups](#Lie)
	- [8.4 Optimization Techniques](#Opt)
	- [8.5 Calibration](#Calibr)
	- [8.6 RANSAC](#RANSAC)
- [9. Selected Blogs](#Blogs)
- [10. Research Groups](#Groups)
- [11. Community](#Community)

------
<a name="HotRepos"></a>
## 1. Hot SLAM Repos on GitHub
- [Awesome-SLAM: Resources and Resource Collections of SLAM](https://github.com/YoujieXia/Awesome-SLAM)
- [awesome-slam: A curated list of awesome SLAM tutorials, projects and communities.](https://github.com/kanster/awesome-slam)
- [SLAM: learning SLAM,curse,paper and others](https://github.com/liulinbo/slam)
- [A list of current SLAM (Simultaneous Localization and Mapping) / VO (Visual Odometry) algorithms](https://github.com/kafendt/List-of-SLAM-VO-algorithms)
- [awesome-visual-slam: The list of vision-based SLAM / Visual Odometry open source, blogs, and papers](https://github.com/tzutalin/awesome-visual-slam)
- [Lee-SLAM-source: SLAM 开发学习资源与经验分享](https://github.com/AlbertSlam/Lee-SLAM-source)
- [awesome-SLAM-list](https://github.com/OpenSLAM/awesome-SLAM-list)
- [VIO-Resources](https://github.com/hhmaizi/VIO-Resources/blob/master/resources4vio)

------
<a name="VSLAM"></a>
## 2. Visual SLAM
<a name="VFramework"></a>
### 2.1 Framework 
- [OpenVSLAM: A Versatile Visual SLAM Framework](https://github.com/OpenVSLAM-Community/openvslam)
- [OpenSfM: Open source Structure-from-Motion pipeline](https://github.com/mapillary/OpenSfM)
- [GSLAM (A General SLAM Framework and BenchMark)](https://github.com/zdzhaoyong/GSLAM)
- [ScaViSLAM](https://github.com/strasdat/ScaViSLAM)

<a name="VMono"></a>
### 2.2 Monocular
- [ORB_SLAM: A Versatile and Accurate Monocular SLAM ](https://github.com/raulmur/ORB_SLAM)
- [LSD-SLAM: Large-Scale Direct Monocular SLAM](https://github.com/tum-vision/lsd_slam)
- [DSO: Direct Sparse Odometry](https://github.com/JakobEngel/dso)
- [LDSO: Direct Sparse Odometry with Loop Closure](https://github.com/tum-vision/LDSO)
- [SVO: Semi-direct Visual Odometry](https://github.com/uzh-rpg/rpg_svo)
- [PTAM: Parallel Tracking and Mapping](https://github.com/Oxford-PTAM/PTAM-GPL)
- [LPVO: Line and Plane based Visual Odometry](https://github.com/PyojinKim/LPVO)
- [LCSD_SLAM: Loosely-Coupled Semi-Direct Monocular SLAM](https://github.com/sunghoon031/LCSD_SLAM)
- [CCM-SLAM: Robust and Efficient Centralized Collaborative Monocular SLAM for Robotic Teams](https://github.com/VIS4ROB-lab/ccm_slam)

<a name="VStereo"></a>
### 2.3 Stereo
- [ORB_SLAM2](https://github.com/raulmur/ORB_SLAM2)
- [ORBSLAM2_with_pointcloud_map](https://github.com/gaoxiang12/ORBSLAM2_with_pointcloud_map)
- [PL-SLAM: a Stereo SLAM System through the Combination of Points and Line Segments](https://github.com/rubengooj/pl-slam)
- [StVO-PL: Stereo Visual Odometry by combining point and line segment features](https://github.com/rubengooj/StVO-PL)
- [PL-SVO](https://github.com/rubengooj/pl-svo)
- [stereo-dso: Direct Sparse Odometry with Stereo Cameras](https://github.com/JiatianWu/stereo-dso)
- [S-PTAM: Stereo Parallel Tracking and Mapping](https://github.com/lrse/sptam), Python implementation: [stereo_ptam](https://github.com/uoip/stereo_ptam)
- [Robust Stereo Visual Odometry](https://github.com/famoreno/stereo-vo)
- [OV²SLAM: A Fully Online and Versatile Visual SLAM for Real-Time Applications](https://github.com/ov2slam/ov2slam)

<a name="VRGBD"></a>
### 2.4 RGBD
- [Dense Visual Odometry and SLAM](https://github.com/tum-vision/dvo_slam)
- [DVO](https://github.com/tum-vision/dvo):Dense Visual Odometry
- [PlanarSLAM](https://github.com/yanyan-li/PlanarSLAM)
- [badslam](https://github.com/ETH3D/badslam): Bundle Adjusted Direct RGB-D SLAM
- [RESLAM](https://github.com/fabianschenk/RESLAM): A real-time robust edge-based SLAM system
- [VDO-SLAM](https://github.com/halajun/VDO_SLAM): A Visual Dynamic Object-aware SLAM System
- [REVO](https://github.com/fabianschenk/REVO): Robust Edge-based Visual Odometry 

<a name="VOthers"></a>
### 2.5 Others
- [CubeSLAM](https://github.com/shichaoy/cube_slam): Monocular 3D Object Detection and SLAM
- [se2lam](https://github.com/izhengfan/se2lam): Visual-Odometric On-SE(2) Localization and Mapping
- [se2clam](https://github.com/izhengfan/se2clam): SE(2)-Constrained Localization and Mapping by Fusing Odometry and Vision
- [BreezySLAM](https://github.com/simondlevy/BreezySLAM): Simple, efficient, open-source package for Simultaneous Localization and Mapping in Python, Matlab, Java, and C++
- [MultiCol-SLAM](https://github.com/urbste/MultiCol-SLAM): a multi-fisheye camera SLAM
- [Event-based Stereo Visual Odometry](https://github.com/HKUST-Aerial-Robotics/ESVO)

------
<a name="VISLAM"></a>
## 3. Visual Inertial SLAM
<a name="VIFramework"></a>
### 3.1 Framework 
- [maplab](https://github.com/ethz-asl/maplab): An open visual-inertial mapping framework.
- [ORB-SLAM3](https://github.com/UZ-SLAMLab/ORB_SLAM3): An Accurate Open-Source Library for Visual, Visual-Inertial and Multi-Map SLAM
- [VINS-Fusion](https://github.com/HKUST-Aerial-Robotics/VINS-Fusion): An optimization-based multi-sensor state estimator
- [Kimera](https://github.com/MIT-SPARK/Kimera): an open-source library for real-time metric-semantic localization and mapping
- [OpenVINS](https://github.com/rpng/open_vins): An open source platform for visual-inertial navigation research

<a name="VIMono"></a>
### 3.2 Monocular
- [OKVIS](https://github.com/ethz-asl/okvis_ros): Open Keyframe-based Visual-Inertial SLAM (ROS Version)
- [ROVIO](https://github.com/ethz-asl/rovio): Robust Visual Inertial Odometry
- [R-VIO](https://github.com/rpng/R-VIO): Robocentric Visual-Inertial Odometry
- [LARVIO](https://github.com/PetWorm/LARVIO): A lightweight, accurate and robust monocular visual inertial odometry based on Multi-State Constraint Kalman Filter
- [msckf_mono](https://github.com/daniilidis-group/msckf_mono)
- LearnVIORB: Visual Inertial SLAM based on ORB-SLAM2 [(ROS Version)](https://github.com/jingpang/LearnVIORB), [LearnViORB_NOROS (Non-ROS Version)](https://github.com/OpenSLAM/LearnViORB_NOROS/tree/master/master/LearnVIORB_NOROS)
- [PVIO](https://github.com/zju3dv/PVIO): Robust and Efficient Visual-Inertial Odometry with Multi-plane Priors
- [PL-VIO](https://github.com/HeYijia/PL-VIO): monocular visual inertial system with point and line features
- [PL-VINS](https://github.com/cnqiangfu/PL-VINS): Real-Time Monocular Visual-Inertial SLAM with Point and Line Features
- [Adaptive Line and Point Feature-based Visual Inertial Odometry for Robust Localization in Indoor Environments](https://github.com/ankh88324/ALVIO)
- [REBiVO](https://github.com/JuanTarrio/rebvo): Realtime Edge Based Inertial Visual Odometry for a Monocular Camera
- [Co-VINS](https://github.com/qintonguav/Co-VINS): Collaborative Localization for Multiple Monocular Visual-Inertial Systems

<a name="VIStereo"></a>
### 3.3 Stereo
- [msckf_vio](https://github.com/KumarRobotics/msckf_vio): Robust Stereo Visual Inertial Odometry for Fast Autonomous Flight
- [OKVIS](https://github.com/ethz-asl/okvis): Open Keyframe-based Visual-Inertial SLAM
- [Basalt](https://gitlab.com/VladyslavUsenko/basalt): Visual-Inertial Mapping with Non-Linear Factor Recovery
- [ICE-BA](https://github.com/baidu/ICE-BA): Incremental, Consistent and Efficient Bundle Adjustment for Visual-Inertial SLAM
- [ORBSLAM_DWO](https://github.com/JzHuai0108/ORB_SLAM): stereo + inertial input based on ORB_SLAM
- [VI-Stereo-DSO](https://github.com/RonaldSun/VI-Stereo-DSO)
- [Semi-Dense Direct Visual Inertial Odometry](https://github.com/KumarRobotics/sdd_vio)
- [LearnVIORBnorosgai2](https://github.com/ZuoJiaxing/LearnVIORBnorosgai2): Visual Inertial SLAM based on ORB-SLAM2 (Non-ROS Version)
- [ygz-stereo-inertial](https://github.com/gaoxiang12/ygz-stereo-inertial): a stereo-inertial visual odometry

<a name="VIRGBD"></a>
### 3.4 RGBD

<a name="VIOthers"></a>
### 3.5 Others
- [X Inertial-aided Visual Odometry](https://github.com/ucla-vision/xivo)

------
<a name="LIDARSLAM"></a>
## 4. LIDAR based SLAM
<a name="LFramework"></a>
### 4.1 Framework
- [Cartographer](https://github.com/cartographer-project/cartographer)
- [LOAM-Livox](https://github.com/hku-mars/loam_livox): A robust LiDAR Odometry and Mapping (LOAM) package for Livox-LiDAR

<a name="LOthers"></a>
### 4.2 Others
- [FAST-LIO](https://github.com/hku-mars/FAST_LIO)
- [LOL](https://github.com/RozDavid/LOL): Lidar-only Odometry and Localization in 3D point cloud maps
- [PyICP SLAM](https://github.com/gisbi-kim/PyICP-SLAM): Full-python LiDAR SLAM using ICP and Scan Context
- [LIO-SAM](https://github.com/TixiaoShan/LIO-SAM): Tightly-coupled Lidar Inertial Odometry via Smoothing and Mapping
- [LeGO-LOAM](https://github.com/RobustFieldAutonomyLab/LeGO-LOAM): Lightweight and Ground-Optimized Lidar Odometry and Mapping on Variable Terrain
- [hdl_graph_slam](https://github.com/koide3/hdl_graph_slam): 3D LIDAR-based Graph SLAM
- [A-LOAM](https://github.com/HKUST-Aerial-Robotics/A-LOAM): Advanced implementation of LOAM
- [LIO-mapping: A Tightly Coupled 3D Lidar and Inertial Odometry and Mapping Approach](https://github.com/hyye/lio-mapping)
- [SC-LeGO-LOAM](https://github.com/irapkaist/SC-LeGO-LOAM): LiDAR SLAM: Scan Context + LeGO-LOAM
- [Fast LOAM](https://github.com/wh200720041/floam): Fast and Optimized Lidar Odometry And Mapping for indoor/outdoor localization
- [SuMa](https://github.com/jbehley/SuMa): Surfel-based Mapping using 3D Laser Range Data
- [LINS](https://github.com/ChaoqinRobotics/LINS---LiDAR-inertial-SLAM): LiDAR-inertial-SLAM
- [ISCLOAM](https://github.com/wh200720041/iscloam): Intensity Scan Context based full SLAM implementation for autonomous driving
- [MULLS](https://github.com/YuePanEdward/MULLS): Versatile LiDAR SLAM via Multi-metric Linear Least Square

------
<a name="LSLAM"></a>
## 5. Learning based SLAM
The SLAM algorithms using conventional methods are listed above by default. The section is to list SLAM algos using learning based methods.

<a name="LSurvey"></a>
### 5.1 Survey
- [A collection of deep learning based localization models](https://github.com/changhao-chen/deep-learning-localization-mapping)
- [3D-Reconstruction-with-Deep-Learning-Methods](https://github.com/natowi/3D-Reconstruction-with-Deep-Learning-Methods)

<a name="LOthers5"></a>
### 5.2 Others
- [TLIO](https://github.com/CathIAS/TLIO): Tight Learned Inertial Odometry
- [Unsupervised Learning of Monocular Depth Estimation and Visual Odometry with Deep Feature Reconstruction](https://github.com/Huangying-Zhan/Depth-VO-Feat)
- [SuperPoint + ORB_SLAM2](https://github.com/KinglittleQ/SuperPoint_SLAM)
- [VINet](https://github.com/HTLife/VINet): Visual-Inertial Odometry as a Sequence-to-Sequence Learning Problem
- [DeepSFM](https://github.com/weixk2015/DeepSFM): Structure From Motion Via Deep Bundle Adjustment
- [Unsupervised Monocular Visual-inertial Odometry Network](https://github.com/Ironbrotherstyle/UnVIO)
- [Semantic SLAM](https://github.com/hridaybavle/semantic_slam)
- [CNN-DSO](https://github.com/muskie82/CNN-DSO): Direct Sparse Odometry with CNN Depth Prediction
- [CNN-SVO](https://github.com/yan99033/CNN-SVO)
- [KFNet](https://github.com/zlthinker/KFNet): Learning Temporal Camera Relocalization using Kalman Filtering
- [Unsupervised Depth Completion from Visual Inertial Odometry](https://github.com/alexklwong/unsupervised-depth-completion-visual-inertial-odometry)
- [The Perfect Match](https://github.com/zgojcic/3DSmoothNet): 3D Point Cloud Matching with Smoothed Densities
- [Beyond Photometric Loss for Self-Supervised Ego-Motion Estimation](https://github.com/hlzz/DeepMatchVO)
- [M^3SNet](https://github.com/whubaichuan/M3VSNet): Unsupervised Multi-metric Multi-view Stereo Network
- [Deep EKF VIO](https://github.com/lichunshang/deep_ekf_vio)
- [Active Neural SLAM](https://github.com/devendrachaplot/Neural-SLAM)
- [DeepFactors](https://github.com/jczarnowski/DeepFactors)
- [OverlapNet](https://github.com/PRBonn/OverlapNet): Loop Closing for 3D LiDAR-based SLAM
- [SO-Net](https://github.com/lijx10/SO-Net): Self-Organizing Network for Point Cloud Analysis
- [Geometry-Aware Learning of Maps for Camera Localization](https://github.com/NVlabs/geomapnet)
- [DeepV2D](https://github.com/princeton-vl/DeepV2D): Video to Depth with Differentiable Structure from Motion
- [PVN3D](https://github.com/ethnhe/PVN3D): A Deep Point-wise 3D Keypoints Voting Network for 6DoF Pose Estimation
- [DeepMVS](https://github.com/phuang17/DeepMVS): Learning Multi-View Stereopsis
- [Epipolar Transformers](https://github.com/yihui-he/epipolar-transformers)
- [DF-VO](https://github.com/Huangying-Zhan/DF-VO): Depth and Flow for Visual Odometry
- [DeepTAM](https://github.com/lmb-freiburg/deeptam): Deep Tracking and Mapping

<a name="DeepFeat"></a>
### 5.3 Deep Features
- [GCNv2 SLAM](https://github.com/jiexiong2016/GCNv2_SLAM): Real-time SLAM system with deep features
- [FCGF](https://github.com/chrischoy/FCGF): Fully Convolutional Geometric Features: Fast and accurate 3D features for registration and correspondence
- [Deep Image Retrieval](https://github.com/naver/deep-image-retrieval)
- [Key.Net](https://github.com/axelBarroso/Key.Net): Keypoint Detection by Handcrafted and Learned CNN Filters

<a name="Semantic"></a>
### 5.4 Semantic SLAM
- [SuMa++](https://github.com/PRBonn/semantic_suma): Efficient LiDAR-based Semantic SLAM
- [DS-SLAM](https://github.com/ivipsourcecode/DS-SLAM)
- [Probabilistic Data Association via Mixture Models for Robust Semantic SLAM](https://github.com/MarineRoboticsGroup/mixtures_semantic_slam)
- [SIVO](https://github.com/navganti/SIVO): Semantically Informed Visual Odometry and Mapping
- [orbslam_semantic_nav_ros, RGBD](https://github.com/MRwangmaomao/semantic_slam_nav_ros)
- [Pop-up SLAM](https://github.com/shichaoy/pop_up_slam): Semantic Monocular Plane SLAM for Low-texture Environments
- [Semantic SLAM using ROS, ORB SLAM, PSPNet101](https://github.com/1989Ryan/Semantic_SLAM)

------
<a name="MobileSLAM"></a>
## 6. Mobile End SLAM
The SLAM algorithms running on PC end are listed above by default. The section is to list references and resources for SLAM algo dev on mobile end.

<a name="MV"></a>
### 6.1 Visual SLAM
- [ORB_SLAM-iOS](https://github.com/ygx2011/ORB_SLAM-IOS)
- [ORB_SLAM2-iOS](https://github.com/ygx2011/ORB_SLAM2-IOS)
- [MobileSLAM](https://github.com/xorthat/MobileSLAM): LSD SLAM on Mobile Phone
- [SLAM_AR_Android](https://github.com/Martin20150405/SLAM_AR_Android)

<a name="MVI"></a>
### 6.2 Visual Inertial SLAM
- [VINS-Mobile](https://github.com/HKUST-Aerial-Robotics/VINS-Mobile): Monocular Visual-Inertial State Estimator on Mobile Phones

<a name="MAR"></a>
### 6.3 Augmented Reality
- [Awesome-ARKit](https://github.com/olucurious/Awesome-ARKit)
- [Awesome-ARCore](https://github.com/olucurious/Awesome-ARCore)
- [MixedRealityToolkit-Unity](https://github.com/microsoft/MixedRealityToolkit-Unity)
- [arcore-android-sdk](https://github.com/google-ar/arcore-android-sdk)
- [OpenARK](https://github.com/augcog/OpenARK)
- [opencv-markerless-AR-Mobile](https://github.com/meiroo/opencv-markerless-AR-Mobile)

#### 6.3.1 Depth Image API with iPhone 7 Plus (or newer)
- [DepthAPISampleForiOS11](https://github.com/fromkk/DepthAPISampleForiOS11)
- [AVDepthCamera](https://github.com/faceowener/AVDepthCamera)
- [ios11-depth-map-test](https://github.com/xiangcong/ios11-depth-map-test)
- [ARCore Depth Lab](https://github.com/googlesamples/arcore-depth-lab): Depth API Samples for Unity
- [AR-Depth](https://github.com/facebookresearch/AR-Depth): Fast Depth Densification for Occlusion-Aware Augmented Reality
- [AR-Depth-cpp](https://github.com/muskie82/AR-Depth-cpp): C++ implementation of Fast Depth Densification for Occlusion-aware Augmented Reality (SIGGRAPH-Asia 2018)

<a name="MOthers"></a>
### 6.4 Others
- [Microsoft Computer Vision API](https://github.com/microsoft/Cognitive-Vision-Android): Android Client Library & Sample
- [GPUImage](https://github.com/BradLarson/GPUImage): An open source iOS framework for GPU-based image and video processing

------
<a name="Datasets"></a>
## 7. Datasets
- [Awesome SLAM Datasets](https://github.com/youngguncho/awesome-slam-datasets)
- [Awesome Robotics Datasets](https://github.com/sunglok/awesome-robotics-datasets): A collection of useful datasets for robotics and computer vision


- [TUM - Monocular Visual Odometry Dataset](https://vision.cs.tum.edu/data/datasets/mono-dataset), [[code](https://github.com/tum-vision/mono_dataset_code)]
- [ADVIO](https://github.com/AaltoVision/ADVIO): An Authentic Dataset for Visual-Inertial Odometry

------
<a name="Tutorials"></a>
## 8. Tutorials

- 视觉SLAM十四讲/14 lectures on visual SLAM，[English Version](https://github.com/gaoxiang12/slambook-en)，[中文版](https://github.com/gaoxiang12/slambook)
- [Practice of the SlamBook](https://github.com/leftthomas/SlamBook)
- [GraphSLAM_tutorials_code](https://github.com/HeYijia/GraphSLAM_tutorials_code)
- [SLAM 开发学习资源与经验分享](https://github.com/AlbertSlam/Lee-SLAM-source)
- [Visual SLAM/VIO 算法笔记](https://blog.csdn.net/MulinB/article/details/53421864)

<a name="3DVision"></a>
### 8.1 3D Vision
- [An Invitation to 3D Vision: A Tutorial for Everyone](https://github.com/sunglok/3dv_tutorial)
- [Computer Vision/Geometric Fundamentals of SLAM](Misc/Geometric-Fundamentals-of-SLAM.md)

#### 8.1.1 Libs
- [opengv](https://github.com/laurentkneip/opengv)
- [Geometry Central](https://github.com/nmwsharp/geometry-central)
- [vilib](https://github.com/uzh-rpg/vilib): CUDA Visual Library by RPG
- [Vitis Vision Library](https://github.com/Xilinx/Vitis_Libraries/tree/master/vision)
- [OpenGR: A C++ library for 3D Global Registration](https://github.com/STORM-IRIT/OpenGR)
- [OpenCP](https://github.com/norishigefukushima/OpenCP): Computational photography library. The code is parallelized by using SIMD intrinsics and multi-threading.


<a name="Robotics"></a>
### 8.2 Robotics
- [RoboticSystemsBook](https://github.com/krishauser/RoboticSystemsBook)
- [MATLABRobotics](https://github.com/AtsushiSakai/MATLABRobotics): MATLAB sample codes for mobile robot navigation
- [Kindr](https://github.com/ANYbotics/kindr): Kinematics and Dynamics for Robotics
- [Sensor Fusion in ROS](https://github.com/methylDragon/ros-sensor-fusion-tutorial): An in-depth step-by-step tutorial for implementing sensor fusion with robot_localization
- [fuse](https://github.com/locusrobotics/fuse): The fuse stack provides a general architecture for performing sensor fusion live on a robot. Some possible applications include state estimation, localization, mapping, and calibration.
- [GPU Computing in Robotics](https://github.com/JanuszBedkowski/gpu_computing_in_robotics)

<a name="Lie"></a>
### 8.3 Lie Algebra and Lie Groups
- [Lie groups for Computer Vision](http://ethaneade.com/lie_groups.pdf)
- [Lie groups for 2D and 3D Transformations](http://ethaneade.com/lie.pdf)
- [Hermite Splines in Lie Groups as Products of Geodesics](http://ethaneade.com/lie_spline.pdf)
- [LieTransformer](https://github.com/anonymous-code-0/lie-transformer)

#### 8.3.1 Libs
- [Sophus](https://github.com/strasdat/Sophus): C++ implementation of Lie Groups using Eigen
- [manif](https://github.com/artivis/manif): A small C++11 header-only library for Lie theory

<a name="Opt"></a>
### 8.4 Optimization Techniques 
- [Gauss-Newton/Levenberg-Marquardt Optimization](http://ethaneade.com/optimization.pdf)
- [How a Kalman filter works, in pictures](http://www.bzarg.com/p/how-a-kalman-filter-works-in-pictures/)
- [卡爾曼濾波 (Kalman Filter)](http://silverwind1982.pixnet.net/blog/post/167680859)
- [翻譯 Understanding the Basis of the Kalman Filter Via a Simple and Intuitive Derivation](http://silverwind1982.pixnet.net/blog/post/171132644)

#### 8.4.1 Libs
- [ceres-solver](https://github.com/ceres-solver/ceres-solver): A large scale non-linear optimization library
- [g2o](https://github.com/RainerKuemmerle/g2o): A General Framework for Graph Optimization
- [GTSAM](https://github.com/borglab/gtsam): Georgia Tech Smoothing and Mapping Library
	- [miniSAM](https://github.com/dongjing3309/minisam): A general and flexible factor graph non-linear least square optimization framework
	- [AprilSAM](https://github.com/xipengwang/AprilSAM): Real-time Smoothing and Mapping
	- [GTSAM Tutorial Examples](https://github.com/dongjing3309/gtsam-examples)
- [AMGCL](https://github.com/ddemidov/amgcl): C++ library for solving large sparse linear systems with algebraic multigrid method
- [Armadillo](https://gitlab.com/conradsnicta/armadillo-code): fast C++ library for linear algebra & scientific computing
- [IFOPT](https://github.com/ethz-adrl/ifopt): An Eigen-based, light-weight C++ Interface to Nonlinear Programming Solvers (Ipopt, Snopt)
- [LBFGS++](https://github.com/yixuan/LBFGSpp): A header-only C++ library for L-BFGS and L-BFGS-B algorithms
- [OptimLib](https://github.com/kthohr/optim): a lightweight C++ library of numerical optimization methods for nonlinear functions
- [PoseLib](https://github.com/vlarsson/PoseLib): a collection of minimal solvers for camera pose estimation
- [fpm](https://github.com/MikeLankamp/fpm): C++ header-only fixed-point math library

<a name="Calibr"></a>
### 8.5 Calibration
#### 8.5.1 Libs
- [kalibr](https://github.com/rpng/kalibr_allan): The Kalibr visual-inertial calibration toolbox
	- [kalibr_allan](https://github.com/rpng/kalibr_allan): IMU Allan standard deviation charts for use with Kalibr and inertial kalman filters
- [Accurate geometric camera calibration with generic camera models](https://github.com/puzzlepaint/camera_calibration)
- [LI-Calib](https://github.com/APRIL-ZJU/lidar_IMU_calib): Targetless Calibration of LiDAR-IMU System Based on Continuous-time Batch Estimation
- [Online Photometric Calibration](https://github.com/tum-vision/online_photometric_calibration)
- [IMU-TK](https://github.com/Kyle-ak/imu_tk): Inertial Measurement Unit ToolKit
- [crisp](https://github.com/hovren/crisp): Camera-to-IMU calibration and synchronization toolbox
- [VersaVIS](https://github.com/ethz-asl/versavis): An Open Versatile Multi-Camera Visual-Inertial Sensor Suite

<a name="RANSAC"></a>
### 8.6 RANSAC
- [RansacLib](https://github.com/tsattler/RansacLib): Template-based implementation of RANSAC and its variants in C++


------
<a name="Blogs"></a>
## 9. Selected Blogs
- [The Future of Real-Time SLAM and Deep Learning vs SLAM](http://www.computervisionblog.com/2016/01/why-slam-matters-future-of-real-time.html)
- [IMU Data Fusing: Complementary, Kalman, and Mahony Filter](http://www.olliw.eu/2013/imu-data-fusing/)

------
<a name="Groups"></a>
## 10. Research Groups
TBA

------
<a name="Community"></a>
## 11. Community
- [PaoPaoRobot - 泡泡机器人](https://github.com/PaoPaoRobot)
- [OpenSLAM.org](https://github.com/OpenSLAM-org)
- [OpenVSLAM-Community](https://github.com/OpenVSLAM-Community)
