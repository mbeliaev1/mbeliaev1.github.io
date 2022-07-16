---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

[Download CV here](https://markbeliaev.com/files/markbeliaev_cv_2022.pdf)

{% include base_path %}

Education
======
* University of California Santa Barbara
_PhD Candidate in Electrical and Computer Engineering;
Advisor: Prof. Ramtin Pedarsani_, June 2020 - Present
* University of California Santa Barbara
_Master of Science in Electrical and Computer Engineering; GPA: 4.00/4.00_, Sep 2018 – Jun 2020
* Stony Brook University
_Bachelor of Engineering in Electrical Engineering;_
_Bachelor of Engineering in Applied Mathematics and Statistics; GPA: 3.84/4.00_, Aug 2013 – Jun 2017


Research Interests
======
* **Reinforcement Learning**:
Reinforcement Learning (RL) has shown great success in training agents to solve human-relevant tasks. One area of interest has been leveraging RL techniques in decentralized multi-agent problems. In a past project, I have looked at the challenge of coordinating agents to cooperate in such environments, analyzing the benefit gifting has in guiding agents towards socially desirable equilibria. Another area within RL that I have investigated is imitation learning and learning from mixed and sub-optimal data. In a recent project I propose an algorithm that learns a policy from sub-optimal data by inferring information from estimated models of the different annotators.
  

* **Adversarial Machine Learning**:
Parallel to the rising popularity of utilizing deep neural network architectures, we have been witnessing how fragile the very same prediction models are. Tiny perturbations to the inputs can cause misclassification errors throughout entire datasets. In a recent work, I have explored the specific setting of l0–bounded adversarial attacks. Based on theoretical evidence from my advisor’s earlier work, we propose an algorithm and analyze its robustness on large image datasets such as MNIST and CIFAR. We plan to continue this work by analyzing further ways to improve the robustness of our algorithm, and applying it to the domain of Natural Language Processing.

* **Human Cyberphysical Systems**: 
The previous topics discussed are intertwined to the development of Human Cyberphysical Systems as robotic learning and safety are essential in these domains. I have done work that utilizes optimization techniques to solve challenging problems in the context of transportation networks. Previously I have investigated how different incentives can be used to promote safe and efficient transportation in the face of the COVID-19 pandemic. In a recent work, I look at bi-modal delivery systems utilizing drones [2], where the next step is to extend the setting to dynamical systems and utilize modern RL techniques to derive the routing schedules efficiently.

Honors & Awards
======
* **2018-19 & 2021-2022 Outstanding Teaching Assistant Award**: Received by the ECE department.
* **Stony Brook University - Magna Cum Laude**: Graduating with an overall GPA of 3.84 in 2017.


Skills
======
* Python
* PyTorch
* TensorFlow
* MATLAB
* C++
* <span class="latex">L<sup>a</sup>T<sub>e</sub>X</span></p>

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
