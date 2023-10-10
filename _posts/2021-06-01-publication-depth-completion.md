---
layout: post
title: "ABCD: Attentive Bilateral Convolutional Network for Robust Depth Completion"
categories: Publication
# excerpt_separator:  <!--more-->
---

<!-- [<img src="https://img.youtube.com/vi/29uWojsPU4A/sddefault.jpg" width="960" height="540"/>](https://www.youtube.com/embed/29uWojsPU4A) -->
<div align="center">
    <iframe width="720" height="405"
    src="https://www.youtube.com/embed/29uWojsPU4A" 
    frameborder="0" 
    allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" 
    allowfullscreen></iframe>
</div>

[**Paper**](https://ieeexplore.ieee.org/document/9565353) / [**Code**](https://github.com/yurimjeon1892/ABCD.git) / [**Video**](https://youtu.be/29uWojsPU4A)


We propose a point-cloud-centric depth completion method called attention bilateral convolutional network for depth completion (ABCD). The proposed method uses LiDAR data and camera data to improve the resolution of the sparse depth information. Color images, which have been seen as fundamental to depth completion tasks, are inevitably sensitive to light and weather conditions. 

We designed an attentive bilateral convolutional layer (ABCL) to build a robust depth completion network under diverse environmental conditions. An ABCL efficiently learns geometric characteristics by directly leveraging a 3D point cloud and enhances the representation capability of sparse depth information by highlighting the core while suppressing clutter. The ABCD, with an ABCL as a building block, stably fills the void in sparse depth images even under unfamiliar conditions with minimum dependency on unstable camera sensors. Therefore, the proposed method is expected to be a solution to depth completion problems caused by changes in the environment in which images are captured. 

Through comparative experiments with other methods using the KITTI and VirtualKITTI2 datasets, we demonstrated the outstanding performance of the proposed method in diverse driving environments.

This paper is published in **IEEE Robotics and Automation Letters (RA-L)**. 

