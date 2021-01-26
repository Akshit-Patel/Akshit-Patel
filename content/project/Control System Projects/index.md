---
title: Control System Projects
summary: MATLAB Based control system problems
tags:
- Robotics
date: "2020-11-03T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  # caption: Photo by rawpixel on Unsplash
  focal_point: Smart
# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: "https://github.com/Akshit-Patel/Control-System-Projects"
# url_pdf: "https://drive.google.com/drive/folders/1oktp8P8gfRQQ1KgVw75gvh7lcxKnPhgI?usp=sharing"
# url_slides: "https://drive.google.com/drive/folders/1oktp8P8gfRQQ1KgVw75gvh7lcxKnPhgI?usp=sharing"
# url_video: "https://drive.google.com/drive/folders/1oktp8P8gfRQQ1KgVw75gvh7lcxKnPhgI?usp=sharing"
# url_efficienyData: "https://drive.google.com/drive/folders/1oktp8P8gfRQQ1KgVw75gvh7lcxKnPhgI?usp=sharing"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

**GITHUB Link - https://github.com/Akshit-Patel/Control-System-Projects**

This repository contains some common problems to control systems and their MATLAB SIMULINK solutions.


**Problem 1 - Closed Loop PID speed control for mathematical model of BLDC Motor**

This is a starter problem in which a basic mathematical model of BLDC motor is designed and controlled via PID. Same controller is designed with both MATLAB and SIMULINK


Resources - 

* Four Video Series of SIMULINK Basics by MATLB
    * https://www.youtube.com/watch?v=iOmqgewj5XI&feature=emb_title

**Problem 2 - Normal PID, Self Tuning Fuzzy PID and PID with Genetic Algorithm for Angle Control of Inverted Pendulum**

<!-- ![Output Surface](Images/Surface.png) -->

An inverted pendulum is a pendulum that has its center of mass above its pivot point. It is unstable and without additional help will fall over. It can be suspended stably in this inverted position by using a control system to monitor the angle of the pole and move the pivot point horizontally back under the center of mass when it starts to fall over, keeping it balanced. The inverted pendulum is a classic problem in dynamics and control theory and is used as a benchmark for testing control strategies. 

Resources -

   * Understanding Basics of Fuzzy System
     *  https://www.youtube.com/watch?v=OVINlUaEiS8&list=PLk8_UfafEClpL0r1YaYHz-F1AbGJDQizL 
  * Genetic Algorithm
     *  https://www.youtube.com/watch?v=ZF004x8kd08&feature=youtu.be
  * Inverted Pendulum
     *  http://ctms.engin.umich.edu/CTMS/index.php?example=Introduction&section=SystemModeling

**Problem 2 b - Sub part only normal PID control of inverted Pendulum**

Basic Version of the above problem and only normal PID Control

**Problem 3 - Tune a proportional controller using root locus for a generalized second order system to have a specific settling time and maximum overshoot for step reference input**
Resources -

   * Understanding Root Locus
     * https://ctms.engin.umich.edu/CTMS/index.php?example=Introduction&section=ControlRootLocus


**Problem 4 - Self Tuning based Fuzzy logic-based control of speed and position of DC shunt motor.**

