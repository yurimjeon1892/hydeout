---
layout: post
title: Development of real-time object detection module using LiDAR sensor
categories: Project
excerpt: LiDAR sensors are resilient to variations in light and weather, providing accurate position measurements that are crucial for object detection algorithms to deliver precise distance information about surrounding objects. Therefore, the use of LiDAR sensors is essential for autonomous driving. This project focuses on developing a deep learning-based object detection algorithm using LiDAR for autonomous vehicles operating in urban environments. As the project lead, I was involved in all stages, from designing the deep learning model to implementing the source code for execution within a ROS environment.
# excerpt_separator:  <!--more-->
---

**Industry-academia cooperation project, Seoul national university**

<div align="center">
    <div style="position: relative; padding-bottom: 56.25%; height: 0;">
        <iframe 
        src="https://www.youtube.com/embed/pnsvPiWt4Ss" 
        frameborder="0" 
        allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen
        style="position: absolute; width: 100%; height: 100%; left: 0; top: 0;"></iframe>
    </div>
</div>

<br>


LiDAR sensors are resilient to variations in light and weather, providing accurate position measurements that are crucial for object detection algorithms to deliver precise distance information about surrounding objects. Therefore, the use of LiDAR sensors is essential for autonomous driving. This project focuses on developing a deep learning-based object detection algorithm using LiDAR for autonomous vehicles operating in urban environments. As the project lead, I was involved in all stages, from designing the deep learning model to implementing the source code for execution within a ROS environment.


Project objectives:
* The final development outcome should be provided in the form of executable source code for the ROS environment.
* The developed object detection algorithm should meet the following performance criteria:
	* Execution time on NVIDIA GeForce GTX 1080 Ti or RTX 2080 with Intel Core i7 machines should be 50 ms or less.
	* The mean average precision (mAP) difference compared to the state-of-the-art object detection algorithm should be 5% or less.


My contributions to the project include:

* Designing the deep learning algorithm in Python using PyTorch and later converting it to C++ for ROS.
* Developing both the pre-processing and post-processing stages of the object detection algorithm in C++ to improve processing speed.
* Converting the deep learning model to ONNX format for enhanced compatibility. In cases where ONNX conversion was not feasible, I used CUDA for better computation speed.

As a result, we achieved the following project objectives:

* Execution time within 40 ms on the testbed.
* mAP difference of 5% or less compared to the state-of-the-art PointPillars.