---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Work experience
======
#### [Toposens GmbH](https://toposens.com/) 
**Robotics engineer (internship)** Munich, Germany (Sep. 2019 - Feb. 2020)

Worked with a 3D ultrasound sensor, able to extract a point cloud from a near-field environment for slowly moving robots. 
Through machine learning, I have created a surface classifier in a three steps procedure: segmentation, fitting and classification.

  - Design and development of a constrained least-squares algorithm in python, applied after segmentation.
  - Built a plugin in Gazebo (C++) to simulate the model and classify several different surfaces.
  - Wrote a scientific paper to explain the model and show the result associated.

#### [National Institute for Nuclear Physics, Legnaro national laboratories, INFN - LNL](https://www.lnl.infn.it/index.php/en/)
**Mechatronics engineer (internship)** Padua, Italy (Feb. 2017 - Sep. 2017)

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
  * Basic knowledge: Java, VHDL

* Tools:
  * Docker, Vim, Git, RViz, Webots, Gazebo, Jupyter, Kafka, MySQL, Vivado, Simulink

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
  
  
