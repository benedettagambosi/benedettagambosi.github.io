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
* Ph.D in Bionegineering, Politecnico di Milano, 2026 (expected)
* M.S. in Biomedical Engineering, Politecnico di Milano, 2021
* B.S. in Biomedical Engineering, Politecnico di Milano, 2019

Work experience
======
* Oct 2024 - Present: Research Fellow
  * Bibilab, Sapienza University of Rome, Rome
  * Supervisor: Prof. Laura Astolfi

* Nov 2023 - July 2024: Visiting Researcher
  * Brain Simulation Section, Charité, Berlin
  * Supervisor: Prof. Petra Ritter

* Oct 2021 - Sept 2024: Research Fellow
  * Nearlab, Politecnico di Milano, Milano
  * Supervisor: Prof. Alessandra Pedrocchi
  
Skills
======
* Computational neuroscience & modeling
  * Neural Mass Models, Spiking Neural Networks
  * Modeling of motor control and neurodegenerative disorders 

* Neural data analysis
  * EEG acquisition and preprocessing
  * Time–frequency and spectral analysis
  * Functional and effective connectivity
  * Network and graph-based analysis
  * Hyperscanning and cross-brain analysis

* Machine learning & AI
  * Sci-kit Learn
  * Pytorch, ANN

* Imaging & multimodal analysis
  * fMRI, DTI   
  * Functional ultrasound imaging (fUSI)–based analysis and simulations
  * Multimodal data integration (electrophysiology and imaging)

* Programming & tools
  * Python, Matlab
  * Github, Docker

* Reproducible research workflows
  * Translational & collaborative research
  * Analysis of patient and clinical data
  * Neurological and neurodevelopmental disorders (PD, epilepsy, autism)
  * Experience in large collaborative projects (e.g. eBRAINS, Aegeus, CrossBrain)

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
  
Grants & Fundings
======
  <ul>{% for post in site.grants reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>