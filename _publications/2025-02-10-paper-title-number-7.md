---
title: "Robust high-order low-rank BUG integrators based on explicit Runge-Kutta methods"
collection: publications
category: preprint
permalink: /publication/2025-02-10-paper-title-number-7
excerpt: ''
date: 2025-02-10
venue: 'arXiv preprint'
paperurl: 'https://doi.org/10.48550/arXiv.2502.07040'
author: 'F. Nobile, S. Riffaud'
citation: 'F. Nobile, S. Riffaud, "Robust high-order low-rank BUG integrators based on
explicit Runge-Kutta methods", <i>arXiv preprint arXiv:2502.07040</i> (2025).'
---
In this work, we introduce high-order Basis-Update & Galerkin (BUG) integrators based on explicit Runge-Kutta methods for large-scale matrix diﬀerential equations. These dynamical low-rank integrators extend the BUG integrator to arbitrary explicit Runge-Kutta schemes by performing a BUG step at each stage of the method. The resulting Runge-Kutta BUG (RK–BUG) integrators are robust with respect to small singular values, fully forward in time, and high-order accurate, while enabling conservation and rank adaptivity. We prove that RK-BUG integrators retain the order of convergence of the underlying Runge-Kutta method until the error reaches a plateau corresponding to the low-rank truncation error, which vanishes as the rank becomes full. This theoretical analysis is supported by several numerical experiments. The results demonstrate the high-order convergence of the RK–BUG integrator and its superior accuracy compared to other existing dynamical low-rank integrators.