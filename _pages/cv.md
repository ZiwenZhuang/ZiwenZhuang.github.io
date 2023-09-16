---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Get file from [here](/files/ZiwenZhuang_CV.pdf)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Education
======
* B.S. in Computer Science and Technology, ShanghaiTech University, 2020
* Summer session, University of California, Berkeley, 2017
* M.S. in Computer Science and Technology, ShanghaiTech University, 2024 (expected)

Work experience
======
* Spring 2021 - Present: Research Assistant
  * Shanghai Qi Zhi Institute
  * Duties included:
    * Self-supervised robot learning
    * Real quadruped robot with Reinforcement Learning
  * Supervisor: [Professor Hang Zhao](https://hangzhaomit.github.io)

* Fall 2020: Research Assistant
  * ShanghaiTech University
  * Duties included: Hardware and Software system design and implementation on Cotton harvesting robot
  * Supervisor: [Professor Soeren Schwertfeger](https://robotics.shanghaitech.edu.cn/people/soeren)

* Summer 2019: Research Intern
  * Carnegie Mellon University
  * Duties included: Self-supervised Reinforcement Learning and tactile sensing
  * Supervisor: [Professor David Held](https://davheld.github.io)
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Skills
======
* Programming
  * Python
  * Pytorch
  * Reinforcement Learning
* Mechanical design
  * Solidworks
  * Shapr3D
* Robotics hardware
  * Drilling Machines
  * STM32 Cortex-M development board
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Service
======
* CoRL 2022, 2023 Reviewer
* AAAI 2022 Reviewer
