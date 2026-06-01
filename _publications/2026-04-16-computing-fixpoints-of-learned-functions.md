---
title: "Computing Fixpoints of Learned Functions: Chaotic Iteration and Simple Stochastic Games"
collection: publications
category: conferences
permalink: /publication/2026-04-16-computing-fixpoints-of-learned-functions
excerpt: 'An significant generalization of the results from the CAV paper, including results for stochastic games, chaotic iteration, and generalizations of convergence results for purely model-based reinforcement learning algorithms.'
date: 2026-04-16
venue: 'TACAS'
slidesurl: 'https://flo-witt.github.io/files/tacas-26.pdf'
paperurl: 'https://doi.org/10.1007/978-3-032-22752-2_28'
bibtexurl: 'https://flo-witt.github.io/files/tacas-26.bib'
citation: 'Baldan, P., Gurke, S., König, B., Wittbold, F. (2026). Computing Fixpoints of Learned Functions: Chaotic Iteration and Simple Stochastic Games. In: Junges, S., Katz, G. (eds) Tools and Algorithms for the Construction and Analysis of Systems. TACAS 2026. Lecture Notes in Computer Science, vol 16505. Springer, Cham.'
---
The problem of determining the (least) fixpoint of (higher-dimensional) functions over the non-negative reals frequently occurs when dealing with systems endowed with a quantitative semantics. We focus on the situation in which the functions of interest are not known precisely but can only be approximated. As a first contribution we generalize an iteration scheme called dampened Mann iteration, recently introduced in the literature. The improved scheme relaxes previous constraints on parameter sequences, allowing learning rates to converge to zero or not converge at all. While seemingly minor, this flexibility is essential to enable the implementation of chaotic iterations, where only a subset of components is updated in each step, allowing to tackle higher-dimensional problems. Additionally, by allowing learning rates to converge to zero, we can relax conditions on the convergence speed of function approximations, making the method more adaptable to various scenarios. We also show that dampened Mann iteration applies immediately to compute the expected payoff in various probabilistic models, including simple stochastic games, not covered by previous work.
