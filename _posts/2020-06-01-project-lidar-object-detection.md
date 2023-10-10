---
layout: post
title: Development of real-time object detection module using LiDAR sensor
categories: Project
excerpt: This project focuses on developing a deep learning-based object detection algorithm using LiDAR for autonomous vehicles driving in urban environments. As the project lead, I actively participated in the entire process, starting from designing the deep learning model to implementing the source code for execution in a ROS environment.
# excerpt_separator:  <!--more-->
---

**Industry-academia cooperation project, Seoul national university**

[<img src="https://img.youtube.com/vi/pnsvPiWt4Ss/sddefault.jpg" width="960" height="540"/>](https://www.youtube.com/embed/pnsvPiWt4Ss)
**Click to watch the video!**


This project focuses on developing a deep learning-based object detection algorithm using LiDAR for autonomous vehicles driving in urban environments. As the project lead, I actively participated in the entire process, starting from designing the deep learning model to implementing the source code for execution in a ROS environment.

Project objectives:
* The final development outcome should be provided in the form of executable source code for the ROS environment.
* The developed object detection algorithm should meet the following performance criteria:
	* Execution time on NVIDIA GeForce GTX 1080 Ti or RTX 2080 with Intel Core i7 machines should be 50 ms or less.
	* The mean average precision (mAP) difference compared to the state-of-the-art (sota) object detection algorithm should be 5% or less.

My contributions to the project:
* I implemented the deep learning algorithm using Python with PyTorch and later converted it to C++ with ROS.
* To improve processing speed, I implemented both pre-processing and post-processing stages of the object detection algorithm in C++.
* The deep learning model was converted to ONNX format for enhanced compatibility. In cases where ONNX conversion was not possible, I used CUDA for improved computation speed.

As a result, my team achieved the following project objectives:
* Execution time within 40 ms on the testbed.
* mAP difference of 5% or less when compared to the state-of-the-art PointPillars.
