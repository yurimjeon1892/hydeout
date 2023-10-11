---
layout: post
title: "ABCD: Attentive Bilateral Convolutional Network for Robust Depth Completion"
categories: Research
# excerpt_separator:  <!--more-->
---

<div align="center">
    <div style="position: relative; padding-bottom: 56.25%; height: 0;">
        <iframe 
        src="https://www.youtube.com/embed/29uWojsPU4A" 
        frameborder="0" 
        allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen
        style="position: absolute; width: 100%; height: 100%; left: 0; top: 0;"></iframe>
    </div>
</div>

<br>

<div class="icon-container">
    <span class="link-with-icon">
        <i data-feather="paperclip"></i>
        <a href="https://ieeexplore.ieee.org/document/9565353" target="_blank">Paper Link</a>
    </span> 
    <span class="link-with-icon">
        <i data-feather="github"></i>
        <a href="https://github.com/yurimjeon1892/ABCD.git" target="_blank">Code</a>
    </span> 
    <span class="link-with-icon">
        <i data-feather="youtube"></i>
        <a href="https://youtu.be/29uWojsPU4A" target="_blank">Video</a>
    </span>    
</div>

<br>


We propose a point-cloud-centric depth completion method called attention bilateral convolutional network for depth completion (ABCD). The proposed method uses LiDAR data and camera data to improve the resolution of the sparse depth information. Color images, which have been seen as fundamental to depth completion tasks, are inevitably sensitive to light and weather conditions. 

We designed an attentive bilateral convolutional layer (ABCL) to build a robust depth completion network under diverse environmental conditions. An ABCL efficiently learns geometric characteristics by directly leveraging a 3D point cloud and enhances the representation capability of sparse depth information by highlighting the core while suppressing clutter. The ABCD, with an ABCL as a building block, stably fills the void in sparse depth images even under unfamiliar conditions with minimum dependency on unstable camera sensors. Therefore, the proposed method is expected to be a solution to depth completion problems caused by changes in the environment in which images are captured. 

Through comparative experiments with other methods using the KITTI and VirtualKITTI2 datasets, we demonstrated the outstanding performance of the proposed method in diverse driving environments.

This paper is published in **IEEE Robotics and Automation Letters (RA-L)**. 

