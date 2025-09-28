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
* DPhil (PhD) in Physics, University of Oxford, 2026 (expected)
* MSci in Natural Sciences (Part III Physics), University of Cambridge, 2022
* BA in Natural Sciences (Part II Physics), University of Cambridge, 2021

Research experience
======
* 2022-2026: DPhil (PhD) student, University of Oxford
  * Project title: Modelling iceberg capsize in glacial fjords
  * Supervisor: Professor Andrew Wells

* 2022: MSci student, Department of Physics, University of Cambridge
  * Project title: Radiation belt modelling using Ensemble Kalman Filters
  * Supervisor: Dr Johnathan Ross

* Summer 2021: Summer student, CERN
  * Project title: Setting limits on quark Contact Interaction scales from ATLAS inclusive jet cross section measurements
  * Supervisor: Dr Tancredi Carli
  
* Summer 2020: Summer student, Department of Physics, University of Cambridge
  * Project title:  Characterising the Ge(001) surface using He-3 spin echo spectrometry data
  * Supervisor: Dr Holly Hedgeland

Skills
======
* Mathematics: Linear algebra, calculus, differential equations, probability, statistics
* Computing: Python (numpy, pandas, scipy, matplotlib), C++, Julia
* Parallel computing: limited experience with MPI and CUDA
* Languages: English (native), Spanish (fluent)

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
  
Scholarships and Funding
======
* UKRI, NERC Doctoral Training Partnership, 2022-2026
