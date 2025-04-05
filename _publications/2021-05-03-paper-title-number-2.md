---
title: "The DGDD method for reduced-order modeling of conservation laws"
collection: publications
category: article
permalink: /publication/2021-05-03-paper-title-number-2
excerpt: ''
date: 2021-05-03
venue: 'Journal of Computational Physics'
paperurl: 'https://doi.org/10.1016/j.jcp.2021.110336'
author: 'S. Riffaud, M. Bergmann, C. Farhat, S. Grimberg, A. Iollo'
citation: 'S. Riffaud, M. Bergmann, C. Farhat, S. Grimberg, and A. Iollo. The DGDD method for the reduced-order modeling of conservation laws. <i>Journal of Computational Physics</i>, 437:110336. 2021.'
---
The discontinuous Galerkin domain decomposition (DGDD) method couples subdomains of high-fidelity polynomial approximation to regions of low-dimensional resolution for the numerical solution of systems of conservation laws. In the low-fidelity regions, the solution is approximated by empirical modes constructed by Proper Orthogonal Decomposition and a reduced-order model is used to predict the solution. The high-dimensional model instead solves the system of conservation laws only in regions where the solution is not amenable to a low-dimensional representation. The coupling between the high-dimensional and the reduced-order models is then performed in a straightforward manner through numerical fluxes at discrete cell boundaries. We show results from application of the proposed method to parametric problems governed by the quasi-1D and 2D compressible Euler equations. In particular, we investigate the prediction of unsteady flows in a converging-diverging nozzle and over a NACA0012 airfoil in presence of shocks. The results demonstrate the stability and the accuracy of the proposed method and the significant reduction of the computational cost with respect to the high-dimensional model.
