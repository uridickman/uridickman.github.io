---
title: "Research"
date: 2026-07-07
---

Deep Learning for solving Partial Differential Equations, especially those relevant in engineering applications, is becoming increasingly crucial for (1) developing synthetic data for Foundation Models, and more importantly, (2) real-time predictions of engineering systems.
Recent advances have been made in this field including the Neural Operator framework, such as with DeepONet and Fourier Neural Operator, which, equipped with Universal Operator Approximation, can learn the dynamics of operators instead of individual solutions to initial or boundary value problems.
These networks therefore have useful properties such as output, and sometimes input, discretization-invariance and fast inference on to approximate PDEs on regular domains.
However, when solving PDEs on irregular domains with sharp interfaces, these networks can be predicted to smear out discontinuities.
These interfaces are typically represented by the level-set of a higher-dimensional function, and consequently solutions of PDEs on evolving interfaces that experience topological changes is difficult numerically.

Although efforts have been made to capture the movement of such interfaces with Neural Operators, these efforts may not be necessary.
Predicting fields in diffusion-dominated regions has been shown to be effective, so my work intends to develop neural operators that capture physics in the sharp regions near the interface, which will in turn require the development of a Neural Operator on an irregular domain that can be trained on an adaptive mesh discretization.
After these fields are predicted by the Neural Operator, the velocity fields can be computed in order to advect the level set function that defines the interface using Direct Numerical Simulation methods, such as flux-conserving schemes and the like.

I intend to apply methods in scientific machine learning and high-performance computing to  free-boundary and interface problems in fluid dynamics and solid mechanics.

---

## Research Areas

- Computational Science and Engineering
- Scientific Machine Learning
- Hyperbolic Conservation Laws
- Computational Solid Mechanics