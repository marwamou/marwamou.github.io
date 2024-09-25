---
title: "Using Deep Neural Networks And Derivative Free Optimization To Accelerate Coverage Closure"
authors: "Raviv Gal, Eldad Haber, Brian Irwin, Marwa Mouallem, Bilal Saleh, and Avi Ziv"
collection: publications
permalink: /publication/using_dnns
excerpt: 'In optimization tasks where functions are noisy and derivatives are unavailable, incorporating deep neural networks as surrogate models can significantly speed up derivative-free optimization (DFO) methods. This approach, applied to Coverage Directed Generation, leads to faster optimization and fewer simulations, reducing computation time by up to 48%.  
---

In computer aided design (CAD), a core task is to optimize the parameters of noisy simulations. Derivative free optimization (DFO) methods are the most common choice for this task. 
In this paper, we show how four DFO methods, specifically implicit filtering (IF), simulated annealing (SA), genetic algorithms (GA), and particle swarm (PS), can be accelerated using a deep neural network (DNN) that acts as a surrogate model of the objective function. In particular, we demonstrate the applicability of the DNN accelerated DFO approach to the coverage directed generation (CDG) problem that is commonly solved by hardware verification teams.
