---
title: "adaptive-ode" 
date: 
tags: []
author: 
description: "Adaptive solver for Solving Non-stiff ODEs"
summary: "Uses second-order Predictor-Corrector Linear Multistep Method for solving non-stiff systems of ODEs. Includes support for adaptive timesteps and polynomial interpolation of the solution at specified times."
---

##### Description

adaptive-ode is a solver written in Python which is designed for solving non-stiff systems of Ordinary Differential Equations. The solver uses a second-order Predictor-Corrector Linear Multistep Method, with Adams-Bashforth as the predictor and Adams-Moulton as the corrector. adaptive-ode incorporates adaptive timesteps to ensure solution accuracy within a provided error tolerance, and polynomial interpolation of the solution at specified times.

##### Download

+ [Methodology](/adaptive-ode.pdf)
+ [Code](https://github.com/uridickman/adaptive-ode/tree/main)