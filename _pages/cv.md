---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

A PDF version of this CV is available [here](/files/cv.pdf).

Education
======
* **Ph.D. in Operations Research**, Southern Methodist University, 2025 - present
  * Department of Operations Research and Engineering Management
  * Coursework: Linear Programming, Stochastic Modeling, Markov Decision Process, Network Flow
* **M.S. in Computer Science**, Texas A&M University, 2025
  * Department of Computer Science & Engineering
  * Coursework: Data Structures, Algorithm Analysis, Data Science, Object-Oriented Programming, Software Engineering, Artificial Intelligence, Computer Organization, Virtual Reality, Data Visualization, Robotics & Spatial Intelligence, Human-AI Interaction
* **B.S. in Mathematics**, University of Illinois at Urbana-Champaign, 2022
  * College of Liberal Arts & Sciences
  * Coursework: Linear Algebra, Probability Theory, Discrete Mathematics, Abstract Algebra, Calculus, Real Analysis

Employment
======
* **Graduate Research Assistant**, Southern Methodist University (08/2025 - present)
  * Research on Bayesian inference, Markov decision processes, and large language models
* **Graduate Teaching Assistant**, Southern Methodist University (08/2025 - present)
  * Department of Operations Research and Engineering Management
  * OREM 3362 Production and Operations Engineering
  * OREM 5357 Analytics for Decision Support
* **Information Technology Intern**, YAPP USA Automotive Systems, Inc. (06/2023 - 08/2023)
  * Provided onsite and remote technical support to end users, reducing overall support requests by 20%.
  * Renovated the company's official website (content, product descriptions, images, technical specifications) using HTML, CSS, and JavaScript.

Research experience
======
* **Bayesian Information Seeking for LLM Agents** (Southern Methodist University; manuscript submitted to ICLR 2027)
  * Developed a method for improving how large language models gather information and make decisions in multi-turn interactive settings, combining Bayesian inference with LLM fine-tuning.
  * Built the full experimental pipeline in Python/PyTorch: data generation, model training on GPU clusters (Slurm), and a reproducible evaluation framework with statistical testing.
  * The resulting model significantly outperforms the base model and strong reported baselines on a public multi-turn benchmark.

* **LLM-Generated Feedback Interpretability and Image-Labeling Sketch Features** (M.S. thesis, 05/2024 - 05/2025; defended 03/05/2025)
  * Sketch Recognition Lab, Texas A&M University
  * Generated synthetic stroke data by extracting contours and performing stochastic resampling to mimic human free-hand sketches for image-labeling tasks.
  * Quantified LLM-generated feedback accuracy using the RAGAS evaluation framework.
  * Compared prompting strategies with non-parametric tests to understand how they influence LLM-generated feedback.
  * Performed correlation analyses between sketch features and LLM feedback interpretability metrics, revealing modest correlations.

Technical skills
======
* **Programming languages:** Java, Python, C++, C, Ruby on Rails, MySQL, Shell, JavaScript, HTML, CSS
* **Frameworks and libraries:** Express, Node.js, Pandas, OpenCV, React, Unity, Robot Operating System (ROS)
* **Tools:** Git, GitHub, Cucumber, Bootstrap, Linux, RESTful APIs

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
