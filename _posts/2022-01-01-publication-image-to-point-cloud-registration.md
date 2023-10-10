---
layout: post
title: "EFGHNet: A Versatile Image-to-Point Cloud Registration Network for Extreme Outdoor Environment"
categories: Publication
# excerpt_separator:  <!--more-->
---

<!-- [<img src="https://img.youtube.com/vi/Xo7GRKyvKuo/maxresdefault.jpg" width="960" height="540"/>](https://www.youtube.com/embed/Xo7GRKyvKuo) -->
<div align="center">
    <iframe width="720" height="405"
    src="https://www.youtube.com/embed/Xo7GRKyvKuo" 
    frameborder="0" 
    allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" 
    allowfullscreen></iframe>
</div>

[**Paper**](https://ieeexplore.ieee.org/document/9799751) / [**Code**](https://github.com/yurimjeon1892/EFGH.git) / [**Video**](https://youtu.be/Xo7GRKyvKuo)

We present an accurate and robust image-to-point cloud registration method that is viable in urban and off-road environments. Existing image-to-point cloud registration methods have focused on vehicle platforms along paved roads. Therefore, image-to-point cloud registration on UGV platforms for off-road driving remains an open question. Our objective is to find a versatile solution for image-to-point cloud registration. 


We present a method that stably estimates a precise transformation between an image and a point cloud using a two-phase method that aligns the two input data in the virtual reference coordinate system (virtual-alignment) and then compares and matches the data to complete the registration (compare-and-match). Our main contribution is the introduction of divide-and-conquer strategies to image-to-point cloud registration. The virtual-alignment phase effectively reduces relative pose differences without cross-modality comparison. The compare-and-match phase divides the process of matching the image and point cloud into the rotation and translation steps. By breaking down the registration problem, it is possible to develop algorithms that can robustly operate in various environments. 



We performed extensive experiments on four datasets (Rellis-3D, KITTI odometry, nuScenes, and KITTI raw). Experiments cover a variety of situations in which image-to-point cloud registration is applied, from image-based localization in off-road environments to camera-LiDAR extrinsic calibration in urban environments. The experiments demonstrate that the proposed method outperforms the existing methods in accuracy and robustness.


This paper is published in **IEEE Robotics and Automation Letters (RA-L)**, and presented at **IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Oct. 2022**. 
