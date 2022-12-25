---
layout: page
title: Projects
---



### Stochastic Analysis of the Imperfect Column based on the Numerical Method

**Objective:**
This study investigates the statistics of the buckling load of a beam with a random initial imperfection profile that rests on a nonlinear elastic foundation using the numerical method. 

**Method:** 
The finite–difference scheme converts the governing differential equation into a system of nonlinear algebraic equations, which I solved utilizing the Newton–Raphson technique. The beam is discretized into 10,000 elements, sufficient for capturing the spatial correlation of the initial imperfection profile and estimating the displacement profile’s second and fourth-order spatial derivatives. Using 1000 Monte Carlo simulations, I calculated the mean and standard deviation of the buckling load for various beam lengths. 

**Results:**
The findings of the study are presented in this paper: [paper] (https://asmedigitalcollection.asme.org/appliedmechanics/article/90/1/011003/1146780/Stochastic-Buckling-of-Geometrically-Imperfect?casa_token=YuT-Z9dUPAYAAAAA:YOMHURRv2UYZYIeFwAdMiL9LXZOcZHtXH2Zlz-VjTQB1KCxJcHHyg5dURvTpuin2H-22T10k)



### Representation the random fields over the manifold using ISOMAP method

**Objective:**
The use of shell structures is impeded by their sensitivity to geometry imperfections, leading to different buckling loads. Attempts at modeling the shell structures under loads often consider the geometries’ randomness. Generating random fields over irregular geometries, however, can be a challenge. The Isometric Feature Mapping Method (ISOMAP) may offer a solution by providing a way to map points from the manifold onto 2D Euclidian space. Through this, it is possible to maintain the geodesic distance between the mapped points in 2D Euclidian space and the original points on the manifold.

**Method:**
I employed the technique laid out in the paper to execute this method.

[Feng, De‐Cheng, Yan‐Ping Liang, Xiaodan Ren, and Jie Li. “Random fields representation over manifolds via isometric feature mapping‐based dimension reduction.” Computer‐Aided Civil and Infrastructure Engineering 37, no. 5 (2022): 593-611.]

The process included forming the neighborhood graph for each point in the  manifold, determining the geodesic distance with Dijkstra‘s algorithm, and creating the lower dimensional embedding.

**Results:**
The ISOMAP technique has been implemented to create random fields across the irregular domains of the hemisphere, swiss roll, C-shaped roll, and hypersurface. Results from the numerical study show that the ISOMAP approach effectively produces random fields on manifold geometries.



### Optimization of the Cross-Sectional Geometry of a Double - Clamped Beam

**Objective:**
For this project, I optimized the cross-sectional area of a double-clamped beam with a distributed load, aiming to construct and design a minimum-mass beam that meets economic criteria.

**Method:**
I used the SciPy library in Python to obtain the general solution to the ODE equation for a double-clamped beam.
I applied the optimization criteria to generate a contour plot for a given material property and distributed load.

**Result:**
GitHub repository of my work can be found [here] (https://github.com/Zheren1999/optimization-the-cross-sectional-geometry-of-a-doubly-clamped-beam-)



### Numerical Solution of the Hopf Equation

**Objective:**
Determine the numerical solution of the Hopf equation, which describes the one–dimensional gas dynamics equation with nonzero pressure. I take into account the overturning effect which can lead to the formation of shock waves.

**Method:**
I employed Newton‘s method to determine the root of the Hopf equation. I utilized two numerical methods (Lax-Friedrichs and MacCormack schemes) to solve the equation with an initial exponential condition function

**Result:**
GitHub repository of my work can be found [here] (https://github.com/Zheren1999/investigation-of-the-Hopf-equation-)

