---
layout: page
title: Projects
---



<h2 align="center">Stochastic Analysis of the Imperfect Column based on the Numerical Method</h2>

![image](https://user-images.githubusercontent.com/89813720/209562576-4ff9b4b9-cb41-4976-b87a-e740dae5017a.png)


**Objective:**
This study investigates the statistics of the buckling load of a beam with a random initial imperfection profile that rests on a nonlinear elastic foundation using the numerical method. 

**Method:** 
The finite–difference scheme converts the governing differential equation into a system of nonlinear algebraic equations, which I solved utilizing the Newton–Raphson technique. The beam is discretized into 10,000 elements, sufficient for capturing the spatial correlation of the initial imperfection profile and estimating the displacement profile’s second and fourth-order spatial derivatives. Using 1000 Monte Carlo simulations, I calculated the mean and standard deviation of the buckling load for various beam lengths. 

**Results:**
The findings of the study are presented in this paper: [paper] (https://asmedigitalcollection.asme.org/appliedmechanics/article/90/1/011003/1146780/Stochastic-Buckling-of-Geometrically-Imperfect?casa_token=YuT-Z9dUPAYAAAAA:YOMHURRv2UYZYIeFwAdMiL9LXZOcZHtXH2Zlz-VjTQB1KCxJcHHyg5dURvTpuin2H-22T10k)


<h2 align="center">Dimensionality reduction method using the ISOMAP method</h2>

![image](https://user-images.githubusercontent.com/89813720/209562750-46deeace-5850-40ed-b386-a7065bc43f82.png)


**Objective:**
This project aims to develop a technique that reduces the dimension of the dataset by preserving the geodesic distance between points. The method provides a way to map points from a 3D manifold into 2D Euclidian space.

**Method:**
- Developed the computer code to produce the neighborhood graph for a dataset.
- Implemented Dijkstra's shortest path algorithm of a graph.
- Used mathematical analysis through numerical simulations to reduce the dimensionality of a dataset by preserving the geodesic distance between the points.


**Results:**
The effectiveness of the ISOMAP approach was analyzed using the hemispherical, swiss roll, C-shaped roll, and hypersurface manifolds. The numerical investigation demonstrated that the procedure successfully transformed points from 3D space into 2D space.



<h2 align="center">Designing a lightweight double-clamped beam with an allowable deflection</h2>

![image](https://user-images.githubusercontent.com/89813720/209562839-1231e1c1-78dd-4d27-a594-5b0ed8e92ba4.png)


**Objective:**
The objective of this project is to optimize the cross-sectional area of a double-clamped beam with a distributed load, aiming to design a minimum-mass beam that meets economic criteria with allowable deflection.

**Method:**
- Employed the SciPy library in Python to determine the deflection for a beam.
- Applied the design criteria to optimize the geometry of a beam.
- Developed the correlation between the dimensions of the beam's cross-section to control the allowable deflection.


**Result:**
GitHub repository of my work can be found [here](https://github.com/Zheren1999/optimization-the-cross-sectional-geometry-of-a-doubly-clamped-beam-).



<h2 align="center">Numerical Solution of the Hopf Equation</h2>

![image](https://user-images.githubusercontent.com/89813720/209562884-6e9e3849-35a5-4f1d-a3e0-a8bc8e0701e3.png)


**Objective:**
The goal of this project is to calculate the numerical solution for the Hopf equation, which models a one-dimensional gas with non-zero pressure that takes into account the overturning effect that can cause the formation of shock waves.

**Method:**
- Implemented the computer code in Python to solve the equation using numerical method (Newton's method).
- Conducted mathematical calculations to get the analytical solution to compare with numerical.
- Analyzed the physical concept of the equation.


**Result:**
GitHub repository of my work can be found [here](https://github.com/Zheren1999/investigation-of-the-Hopf-equation-). 

