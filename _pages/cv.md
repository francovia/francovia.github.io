---
layout: archive
title: "Resume"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

My research interests are in Geometric Deep Learning,  Graph Neural Networks, Federated Learning, 
Distributed Optimization, Edge Computing, Cognitive Systems, IoT, Industry 4.0 & Cyber Physical Systems. 

Work experience
======

Fraunhofer Institute for Cognitive Systems IKS
-----
- *Research Engineer*

   Munich, Germany (Jun. 2020 - now)
   
   Involved in several projects, from resilient architectures for safety machine learning systems, 
   to smart manufacturing interfaces for Industry 4.0.
  - Developing an asset administration shell for training several industrial devices with the federated learning approach.
  - Designing resilient service-oriented architectures for safety-critical systems running machine learning programs.
  - Detection of out-of-distribution samples with attention networks.

Toposens GmbH 
-----
- *Robotics engineer (internship)* 
    
    Munich, Germany (Sep. 2019 - Feb. 2020)

    Worked with a 3D ultrasound sensor, able to extract a point cloud from a near-field environment for slowly moving robots. 
    Through machine learning, I have created a surface classifier in a three steps procedure: segmentation, fitting and classification.

  - Design and development of a constrained least-squares algorithm in python, applied after segmentation.
  - Built a plugin in Gazebo (C++) to simulate the model and classify several different surfaces.
  - Wrote a scientific paper to explain the model and show the result associated.

National Institute for Nuclear Physics, Legnaro national laboratories, INFN - LNL 
-----
- *Mechatronics engineer (internship)* 
    
  Padua, Italy (Feb. 2017 - Sep. 2017)

  An automatic storage facility of exhausted targets used to allow a drop in radioactivity.
  The movement was fully autonomous, from target extraction until the storage phase. A prototype of the deposit system has been designed and implemented.
  ([video](https://www.youtube.com/watch?v=lCyCAb-AQD0))
  
  - An automatic storage facility of exhausted targets used to allow a drop in radioactivity.
  - Development of a supervision system with Scada as HMI. Documentation of the storage usages and procedures.

Education
======
* M.S. in automation engineering, University of Bologna, 2019
* B.S. in mechatronics engineering, University of Padua, 2017

  
Skills
====== 
* Programming languages:
  * Medium knowledge: C/C++, Python, Matlab, Bash, PLC's standards
  * Basic knowledge: Java, Scala, Go, Prolog, VHDL, Verilog

* Libraries:
  * Pytorch, Pytorch geometric, Tensorflow, Keras, Networkx, PCL, OpenCV, Eigen

* OS
  * Ubuntu, Mac, ROS, ROS2, VxWorks 
 
* Tools:
  * Docker, Kubernetes, Tensorflow Extended, Vim, Git, Kafka, MySQL, Jupyter

* Simulators:
  * Webots, Gazebo, RViz, Simulink, CARLA

Languages
======
* English: B2, IELTS: 6.5, 
* German: B1, 
* Italian: mother lang.


Projects
======
  <ul>{% for post in site.projects %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
  
