---
layout: archive
title: "Curriculum Vitae"
permalink: /
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

---

<br/><br/>

Fields Of Interest
======
Energy transition, Dynamical systems & control, Reduced-order modeling, Physics-informed machine learning, Uncertainty Quantification

Education
======
* Ph.D., Applied Mathematics, University of Arizona, 2025 (expected)
* M.S., Applied Mathematics, University of Arizona, 2021
* B.S., Mathematics & Physics, University of Arizona, 2016

Research
======
* __Machine Learning Statistical Evolution of the Coarse-Grained Velocity Gradient Tensor__
We incorporate modern ML architectures in physics-informed reduced order models of the inherently chaotic evolution of the velocity gradient tensor in isotropic turbulence.
  * *Physics-informed machine learning, interpretable ML, transformers, statistical mechanics, stochastic differential equations, reduced-order modeling, big data*

* __Optimal Natural Gas Flows in a Network with Uncertainty__
We work to determine optimal flows on a natural gas network under the coupled gas and energy grids upon inclusion of intermittent renewable energies and under stressing scenarios.
  * *PDE-constrained optimization, differentiable programming, dynamical systems, numerics, optimal (stochastic) control, optimization under uncertainty*


Work experience
======
* 2020-05-13 to present:  __Graduate Student Researcher__, Los Alamos National Laboratory
  
* 2020-05-13 to present: __Graduate Research Assistant__, University of Arizona

* 2023-05-13 to 2023-08-15: __Google Summer of Code, NumFocus, Contributor__, Julia/SciML
  * Developed software to symbolically discretize a given PDE on a staggered grid and handle boundary conditions

* 2016-05-13 to 2019-08-15: __Sofware Engineer II__, Raytheon Missile Systems, Tucson, AZ
  * Led a small team designing, implementing, and integrating an embedded software subsystem.
  * Worked as scrum master to remove impediments, communicate timelines and expectations intra- and inter-team, and triage and alleviate failures.
  
Skills
======
* Mathematics
  * Dynamical systems & Numerical methods
  * Optimization & Control
  * Stochastic Processes
  * Analysis
* Software/Computer Science
  * Expertise in developing software for high performance, distributed systems
  * Experience in software design
  * Symbolic Programming
  * Experience adapting algorithms to embedded, real-time systems
* Physics
  * Developing expertise in turbulent flows & statistical mechanics
  * General knowledge of classical and non-relativistic quantum mechanics

Development Tools
======
* __Languages:__ Julia, Python, C/C++, Bash, Matlab, Ada, Cuda
* __HPC:__ Slurm, development and deployment of parallelizable codes, Docker
* __Methodologies:__ Continuous integration, Test-driven development, Agile
* __Open-source/collaboration:__ git, github, workflows
* __ML Workflows:__ Pytorch, TensorFlow, Flux

Fellowships
======
* Orin Flanigan Scholarship: Pipeline Simulation Interest Group
* NSF Data-Driven Research Training Group Traineeship
* Roots for Resilience Data Science Scholarship

Service and leadership
======
* Aug 2023: Organized and presented _Programming for Applied Mathematicians Bootcamp_ for incoming graduate students
* Jul 2023: Mentored undergraduate student as part of NSF Data-Driven REU
* Apr 2023: Organized and presented _Introduction to Parallelization_ for NSF Data-Driven Research Training
* Mar 2023: Graduate Mentor for American Statistical Association DataFest Competition
* Quarterly: Organized and presented _Introduction to HPC_ seminar for Math PhD students
* 2021-22: SIAM Brown Bag Student Colloquium Organizer
* 2018-19: Certified Scrum Master: Scaled Agile Framework

Human Languages
======
* English
  * Native Speaker
* Spanish
  * Basic

Publications & Talks
======
{% assign posts = site.publications | sort: 'date' | reverse %}
  <ul>{% for post in posts %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
{% assign posts = site.talks | sort: 'date' | reverse %}
  <ul>{% for post in posts %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>  

References
======
* PhD Advisor, Dr. Michael Chertkov
