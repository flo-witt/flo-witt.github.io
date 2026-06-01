---
title: "Approximating Fixpoints of Approximated Functions"
collection: publications
category: conferences
permalink: /publication/2025-07-22-approximating-fixpoints-of-approximated-functions
excerpt: 'Approximating fixpoints of non-expansive functions using only a sequence of approximations to the function of interest with applications to model-based reinforcement learning.'
date: 2025-07-22
venue: 'CAV 2025'
slidesurl: 'https://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://doi.org/10.1007/978-3-031-98679-6_9'
bibtexurl: 'https://flo-witt.github.io/files/approximating-25.bib'
citation: 'Baldan, P., Gurke, S., König, B., Padoan, T., Wittbold, F. (2025). Approximating Fixpoints of Approximated Functions. In: Piskac, R., Rakamarić, Z. (eds) Computer Aided Verification. CAV 2025. Lecture Notes in Computer Science, vol 15932. Springer, Cham.'
---
Fixpoints are ubiquitous in computer science and when dealing with quantitative semantics and verification one often considers least fixpoints of (higher-dimensional) functions over the non-negative reals. We show how to approximate the least fixpoint of such functions, focusing on the case in which they are not known precisely, but represented by a sequence of approximating functions that converge to them. We concentrate on monotone and non-expansive functions, for which uniqueness of fixpoints is not guaranteed and standard fixpoint iteration schemes might get stuck at a fixpoint that is not the least. Our main contribution is the identification of an iteration scheme, a variation of Mann iteration with a dampening factor, which, under suitable conditions, is shown to guarantee convergence to the least fixpoint of the function of interest. We then argue that these results are relevant in the context of model-based reinforcement learning for Markov decision processes, showing how the proposed iteration scheme instantiates and allows us to derive convergence to the optimal expected return. More generally, we show that our results can be used to iterate to the least fixpoint almost surely for systems where the function of interest can be approximated with given probabilistic error bounds, as it happens for probabilistic systems which can be explored via sampling.
