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
* <b>Postdoctoral researcher</b> (Dec. 2023 - Today)<br />
  <i>École Polytechnique Fédérale de Lausanne (Lausanne, Switzerland)</i><br />
  <u>Suject:</u> Dynamical low-rank approximations for data assimilation<br />
  <u>Supervisor:</u> Prof. Fabio Nobile

* <b>Postdoctoral researcher</b> (Nov. 2021 - Nov. 2023)<br />
  <i>Centre Inria de Paris (Paris, France)</i><br />
  <u>Suject:</u> Parameter estimation in blood flow model<br />
  <u>Supervisors:</u> Damiano Lombardi and Miguel A. Fernández

* <b>Postdoctoral researcher</b> (Apr. 2021 - Oct. 2021)<br />
  <i>Centre Inria de Bordeaux (Talence, France)</i><br />
  <u>Suject:</u> Extraction of the geometry associated with aortic aneurysms<br />
  <u>Supervisor:</u> Prof. Angelo Iollo

* <b>Scientific stay</b> (Jan. 2020 - Apr. 2020)<br />
  <i>Stanford University (Stanford, CA, USA)</i><br />
  <u>Suject:</u> Development of a space-local reduced-order model<br />
  <u>Supervisors:</u> Prof. Angelo Iollo and Prof. Charbel Farhat

* <b>Doctoral student</b> (Oct. 2017 - Nov. 2020)<br />
  <i>Université de Bordeaux (Talence, France)</i><br />
  <u>Suject:</u> Development of reduced-order models for fluid mechanics<br />
  <u>Supervisor:</u> Prof. Angelo Iollo
  
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
