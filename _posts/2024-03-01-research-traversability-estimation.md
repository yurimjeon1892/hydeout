---
layout: post
title: "Follow the Footprints: Self-supervised Traversability Estimation for Off-road Vehicle Navigation based on Geometric and Visual Cues"
categories: Research
# excerpt_separator:  <!--more-->
---

<div align="center">
    <div style="position: relative; padding-bottom: 56.25%; height: 0;">
        <iframe 
        src="https://www.youtube.com/embed/zZ7iKr001Z4" 
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
        <a href="https://arxiv.org/abs/2402.15363" target="_blank">Paper Link</a>
    </span> 
    <span class="link-with-icon">
        <i data-feather="github"></i>
        <a href="https://github.com/yurimjeon1892/FtFoot.git" target="_blank">Code</a>
    </span> 
    <span class="link-with-icon">
        <i data-feather="youtube"></i>
        <a href="https://youtu.be/zZ7iKr001Z4" target="_blank">Video</a>
    </span>    
</div>

<br>


In this study, we address the off-road traversability estimation problem, that predicts areas where a robot can navigate in off-road environments. An off-road environment is an unstructured environment comprising a combination of traversable and non-traversable spaces, which presents a challenge for estimating traversability. This study highlights three primary factors that affect a robot's traversability in an off-road environment: surface slope, semantic information, and robot platform. We present two strategies for estimating traversability, using a guide filter network (GFN) and footprint supervision module (FSM). The first strategy involves building a novel GFN using a newly designed guide filter layer. The GFN interprets the surface and semantic information from the input data and integrates them to extract features optimized for traversability estimation. The second strategy involves developing an FSM, which is a self-supervision module that utilizes the path traversed by the robot in pre-driving, also known as a footprint. This enables the prediction of traversability that reflects the characteristics of the robot platform. Based on these two strategies, the proposed method overcomes the limitations of existing methods, which require laborious human supervision and lack scalability. Extensive experiments in diverse conditions, including automobiles and unmanned ground vehicles, herbfields, woodlands, and farmlands, demonstrate that the proposed method is compatible for various robot platforms and adaptable to a range of terrains.


This paper is presented at **IEEE International Conference on Robotics and Automation (ICRA), May. 2024**. 
