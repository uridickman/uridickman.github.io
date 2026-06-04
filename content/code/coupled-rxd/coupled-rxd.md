---
title: "coupled-rxd" 
date: 
tags: []
author: 
description: "Solver for N Coupled Reaction-Diffusion Equations in 2-D"
summary: "Second-order ADI solver for N coupled reaction-diffusion equations in 2 dimensions. Examples are included for solving the Gray-Scott and FitzHugh-Nagumo equations."
---

##### Description

Pattern Formation is of particular interest in the field of Mathematical Biology. Alan Turing predicted in 1952 that instability in the reaction-diffusion equations results in the formation of heterogeneous patterns, as a result of the interactions between an activator and an inhibitor that diffuse at different rates.

coupled-rxd solves these equations in Python, utilizing Scipy's sparse matrix data structures and sparse_lu solver for more efficient memory and time complexity. coupled-rxd enables solving any number of coupled Reaction-Diffusion equations. The Laplacian operator is approximated using the Peaceman-Rachford Alternating Direction Implicit method, with the second derivatives discretized using second-order centered differences. The reaction term is approximated with Crank-Nicolson method, using Heun's Predictor-Corrector method for the implicit term. Examples are included for solving the Gray-Scott and FitzHugh-Nagumo equations.

Future work involves using Python multiprocessing to solve each uncoupled equation on its own process, with the reaction term being computed on a the main process. It can also include extension to 3D or using a higher-order 9-point Laplacian for 2D.

##### Download

+ [Code](https://github.com/uridickman/coupled-rxd/tree/main)