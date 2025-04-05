---
title: "Robust high-order low-rank BUG integrators based on explicit Runge-Kutta methods"
collection: publications
category: preprint
permalink: /publication/2025-02-10-paper-title-number-7
excerpt: ''
date: 2025-02-10
venue: 'arXiv'
paperurl: 'https://doi.org/10.48550/arXiv.2502.07040'
author: 'F. Nobile, S. Riffaud'
citation: 'F. Nobile and S. Riffaud. Robust high-order low-rank BUG integrators based on
explicit Runge-Kutta methods. <i>arXiv preprint arXiv:2502.07040</i>. 2025.'
---
In this work, we propose high-order basis-update & Galerkin (BUG) integrators based on explicit Runge-Kutta methods for large-scale matrix differential equations. These dynamical low-rank integrators are high-order extensions of the BUG integrator and are constructed by performing one time-step of the first-order BUG integrator at each stage of the Runge-Kutta method. In this way, the resulting Runge-Kutta BUG integrator is robust to the presence of small singular values and does not involve backward time-integration steps. We provide an error bound, which shows that the Runge-Kutta BUG integrator retains the order of convergence of the associated Runge-Kutta method until the error reaches a plateau corresponding to the low-rank truncation and which vanishes as the rank increases. This error bound is finally validated numerically on three different test cases. The results demonstrate the high-order convergence of the Runge-Kutta BUG integrator and its superior accuracy compared to other low-rank integrators proposed in the literature.