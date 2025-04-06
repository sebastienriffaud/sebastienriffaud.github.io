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
* Ph.D in applied mathematics and scientific computing, Université de Bordeaux, 2020
* M.S. in applied mathematics and scientific computing, Ensimag - Grenoble INP, 2017
* B.S. in mathematics, Université de Bordeaux, 2015

Work experience
======
* <b>Post-doctoral researcher</b> (Dec. 2023 - Today)<br />
  <i>École Polytechnique Fédérale de Lausanne (Lausanne, Switzerland)</i><br />
  <u>Suject:</u> Dynamical low-rank approximations for data assimilation.<br />
  <u>Supervisor:</u> Prof. Fabio Nobile.<br />

* Nov. 2021 - Nov. 2023: Postdoctoral fellow
  * Centre Inria de Paris (Paris, France)
  * Suject: Parameter estimation in blood flow model.
  * Supervisors: Damiano Lombardi and Miguel A. Fernández.

* Apr. 2021 - Oct. 2021: Postdoctoral fellow
  * Centre Inria de Bordeaux (Bordeaux, France)
  * Suject: Extraction of the geometry associated with aortic aneurysms.
  * Supervisor: Prof. Angelo Iollo.

* Jan. 2020 - Apr. 2020: Stay
  * Stanford University (Stanford, États-Unis)
  * Suject: Development of a space-local reduced-order model.
  * Supervisors: Prof. Angelo Iollo and Prof. Charbel Farhat.

* Oct. 2017 - Nov. 2020: Ph.D fellow
  * Université de Bordeaux (Bordeaux, France)
  * Suject: Development of reduced-order models for fluid mechanics.
  * Supervisor: Prof. Angelo Iollo.
  
Skills
======
* Programming languages: Maple, Matlab, Python, Julia, Fortran, C++.
* Software and libraries: FreeFem++, OpenMP, MPI, ScaLAPACK, PETSc.

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
