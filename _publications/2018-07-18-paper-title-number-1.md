---
title: "Reduced-order model for the BGK equation based on POD and optimal transport"
collection: publications
category: article
permalink: /publication/2018-07-18-paper-title-number-1
excerpt: ''
date: 2018-07-18
venue: 'Journal of Computational Physics'
paperurl: 'https://doi.org/10.1016/j.jcp.2018.07.001'
author: 'F. Bernard, A. Iollo, S. Riffaud'
citation: 'F. Bernard, A. Iollo, S. Riffaud. "Reduced-order model for the BGK equation based on POD and optimal transport." <i>Journal of Computational Physics</i> <b>373</b> (2018), p. 545-570.'
---
We present a reduced-order approximation of the BGK equation leading to fast and accurate computations. The BGK model describes the dynamics of a gas flow in both hydrodynamic and rarefied regimes. The particles of the gas are represented by a density distribution function depending on physical space, velocity space and time. In this work, the density distribution function is approximated in the velocity space by a small number of basis functions computed offline. In the offline phase, the BGK equation is sampled in order to collect information on the density distribution function. To complete this sampling, optimal transport is used to add new information by interpolating the samples of the density distribution function. Finally, the basis functions are built by Proper Orthogonal Decomposition. During the online phase, the offline knowledge is used to compute approximations of the density distribution function at low cost. To do so, the BGK equation is projected onto the basis functions, leading to a system of partial differential equations. The system obtained is hyperbolic by construction and is solved by an IMEX Runge–Kutta scheme in time and a finite-volume scheme in space. To improve the accuracy, the reduced-oder model is modified to conserve mass, momentum and energy of the gas. Numerical illustrations of 1D and 2D flows are given. In particular, we investigate the reconstruction and the prediction of shock waves, boundary layers and vortices. The results demonstrate the accuracy of the reduced-order model and the significant reduction of the computational cost.
