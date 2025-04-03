---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)
* M.S. in Jekyll, GitHub University, 2014
* B.S. in GitHub, GitHub University, 2012

Work experience
======
* Fall 2022 - Present: Research Developer, SPIN Intern @ [National Center of Supercomputing Applications](https://www.ncsa.illinois.edu/) 
  * Engineered parallelized visualization pipeline using VisIT Visualization across distributed cloud computing infrastructure,
processing 800+ TBs of cosmological simulation data and communicating observational signatures in 14+ peer-reviewed
publications 
  * Implemented GPU acceleration into elliptical PDE solvers in C++ and Python, reducing initial data compute times from
168 hours to 45 minutes (2000 % Speed up) through OpenACC and OpenMP parallelization
  * Developed a low-code GUI application enabling efficient utilization of open-source models on cloud-computing infras-
tructure, streamlining biophysicists’ workflow for computational experimentation and saving an estimated 20+ developer
hours per week
  * Implemented an automated software support system by integrating Slack with GitHub, reducing response time for bug
fixes and feature requests by 40% and maintaining seamless software updates for 18+ months 

* Summer 2024: Data Science Intern @ [John Deere](https://about.deere.com/en-us/our-company-and-purpose/technology-and-innovation) 
  * Automated end-to-end CI/CD pipeline using Airflow and Spark, processing 1.2TB of IoT sensor data daily with 99.4%
schema validation accuracy 
  * Engineered multimodal CNN-RNN fusion model (PyTorch) combining LiDAR point clouds and RGB imagery, achieving
0.85 F1 score and sub-300 ms response time on trench condition classification, reducing false positives in crop health
alerts by 38% 


* Spring 2022 & Summer 2022 & Summer 2023: Machine Learning Engineering Intern @ [Flexday AI](https://flexday.ai/) 
  * Engineered application that integrates YAML configuration files to automate data science workflows on AWS and Azure,
collaborating with executives to create intuitive ML model prototyping interface 
  * Developed embedded object-tracking model, reducing size by 53% through Q-HyVIT and INT8 quantization, delivering
0.81 F1 score, 98.7% up-time, and sub-150 ms response time on resource-constrained hardware 
  * Designed and deployed customer service chatbot using TF-IDF classification, effectively directing 200+ conference
attendees to relevant FAQs and company resources 
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
