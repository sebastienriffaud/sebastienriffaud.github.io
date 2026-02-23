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
* PhD in applied mathematics and scientific computing, Université de Bordeaux, 2020
* MS in applied mathematics and scientific computing, Ensimag - Grenoble INP, 2017
* BS in mathematics, Université de Bordeaux, 2015

Work experience
======
* <b>Postdoctoral researcher</b> (Dec. 2023 - Today)<br />
  <i>École Polytechnique Fédérale de Lausanne (Switzerland)</i><br />
  <u>Research topics:</u> Dynamical low-rank approximations for data assimilation<br />
  <span style="visibility: hidden;"><u>Research topics:</u></span>Reduced-order and machine learning surrogates for turbulent flows<br />
  <u>Postdoctoral advisors:</u> Prof. Fabio Nobile and Prof. Jürg A. Schiffmann

* <b>Postdoctoral researcher</b> (Nov. 2021 - Nov. 2023)<br />
  <i>Centre Inria de Paris (France)</i><br />
  <u>Research topic:</u> Low-rank methods for inverse problems and uncertainty quantification<br />
  <u>Postdoctoral advisors:</u> Damiano Lombardi and Miguel A. Fernández

* <b>Postdoctoral researcher</b> (Apr. 2021 - Oct. 2021)<br />
  <i>Centre Inria de Bordeaux (France)</i><br />
  <u>Research topic:</u> Graph-based methods for geometry extraction of abdominal aortic aneurysms<br />
  <u>Postdoctoral advisor:</u> Prof. Angelo Iollo

* <b>Scientific stay</b> (Jan. 2020 - Apr. 2020)<br />
  <i>Stanford University (USA)</i><br />
  <u>Research topic:</u> Space-local reduced-order modeling for compressible flows<br />
  <u>PhD supervisor and collaborator:</u> Prof. Angelo Iollo and Prof. Charbel Farhat

* <b>Doctoral student</b> (Oct. 2017 - Nov. 2020)<br />
  <i>Université de Bordeaux (France)</i><br />
  <u>Research topic:</u> Projection-based reduced-order models for transport-dominated and kinetic equations<br />
  <u>PhD supervisor:</u> Prof. Angelo Iollo
  
Skills
======
* Programming languages: Maple, Matlab, Python, Julia, Fortran, C++.
* Software and libraries: FreeFem++, OpenMP, MPI, ScaLAPACK, PETSc, OpenFOAM.

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
