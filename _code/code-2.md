---
title: "Dynamical Low‑Rank Ensemble Kalman filter for State/Parameter estimation"
excerpt: "DLR-EnKF"
collection: code
codeurl: 'https://doi.org/10.5281/zenodo.18655790'
---
We propose a Dynamical Low-Rank Ensemble Kalman Filter (DLR-ENKF) for efficient joint state-parameter estimation in high-dimensional dynamical systems. The method extends the DLR-ENKF formulation of arXiv:2509.11210 to the augmented state-parameter framework, tracking the filtering density within a dynamically evolving low-dimensional subspace. Key developments include a time-integration strategy that combines the Basis Update & Galerkin scheme with forecast/analysis discretisation, and a DEIM-based hyper-reduction technique for efficient evaluation of nonlinear terms. We demonstrate the effectiveness, robustness, and computational advantages of the proposed approach on benchmark problems. The results highlight the potential of dynamically evolving reduced bases to achieve accurate filtering and parameter estimation at reduced computational cost.
