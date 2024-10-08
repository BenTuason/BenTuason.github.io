---
layout: archive
title: "CV"
permalink: /cv/
author_profile: false
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Computer Science, University of Houston, 2025
* B.S. in Mathematics, University of Houston, 2025
* A.S. in Computer Science, Houston Community College, 2023


Research Interests
======

* Complexity Theory - Concrete Complexity
* Boolean Function Analysis
* Learning Theory
* Hardness of Approximation
* Quantum Computing
* Randomization 
* Cryptography

Experience
======
* Summer 2024: Research Assistant
  * Data Driven Computing REU @ The University of Houston
  * Topic/Project: Reduce the binary linear classification problem to Edelsbrunner's Line Stabbing algorithm. See if it's PAC-learnable and if there's a way to generalize the method in higher dimensions efficiently.
  * Supervisor: Dr. Rakesh Verma

* Spring 2024: Research Assistant
  * Intelligent Data & Systems Lab
  * Duties includes: Optimized parameters (wait time, batch size) to minimize latency of ML inference serving time.
  * Supervisor: Dr. Feng Yan

* Summer 2023: Research Assistant
  * Real-Time Systems Lab
  * Duties included: Implemented reinforcement learning for simulated cars using rate monotonic scheduling, which enhanced on-time arrivals and adherence to deadlines.
  * Supervisor: Dr. Albert Cheng


  
Skills
======
* Programming Languages: Python, C++, C, R, SQL
* Tools and Technologies: Git, GitHub, LaTeX
* QC: Qiskit, Classiq
* Other: MySQL

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Awards
======
* Dean's list: Fall 2023, Spring 2024
* Transfer Excellence Scholarship
