---
layout: post
title: A BRIEF-Gist Based Efficient Place Recognition for Indoor Home Service Robots
categories: Publication
# excerpt_separator:  <!--more-->
---

![Overview of the proposed method](../../../../_posts/figure/place_recognition_overview.png "Overview")

[**Paper**](https://ieeexplore.ieee.org/document/7832506)

Visual place recognition has been vastly researched in the last decade. Most of the previous works have concentrated on improvement of performance when the environment changes due to illumination, weather or season at outdoor with abundant features and textures for place recognition. On the other hand, when a robot moves in a home environment, input images sometimes contain less features or textures for place recognition, which in turn degrades the precision and recall performance.  


This paper presents an efficient place recognition method based on a binary robust independent elementary features gist (BRIEF-Gist) descriptor for indoor home service robot. The proposed method simply extracts multiple BRIEF-Gist descriptors from an input image, which results in a higher performance. A simple data structure for fast comparison between images is also presented. In home environment experiments, the original BRIEF-Gist and the proposed method shows the maximum recall rate of 1.6% and 9.7%, respectively, both with a precision of 100%. On the other hand, local feature based DLoopDetector method shows below 5% of both recall and precision performance. For comparison, computation times, which are the average execution times for processing place recognition algorithms of one image with 2058 places in a map, are measured; the proposed method without the proposed data structure takes 31.4 ms, and the proposed method with the proposed data structure takes 10.5 ms.  


This paper is presented in **International Conference on Control, Automation and Systems (ICCAS)**. 
