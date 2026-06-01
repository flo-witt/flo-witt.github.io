---
title: "Stochastic Decision Petri Nets"
collection: publications
category: conferences
permalink: /publication/2023-05-28-stochastic-decision-petri-nets
excerpt: 'Introduction of stochastic decision Petri nets, an extension of stochastic Petri nets introducing non-deterministic choices along with first complexity results and an algorithm for optimal constant strategies.'
date: 2023-05-28
venue: 'Petri Nets'
slidesurl: 'https://flo-witt.github.io/files/petri-nets-23.pdf'
paperurl: 'https://doi.org/10.1007/978-3-031-33620-1_15'
bibtexurl: 'https://flo-witt.github.io/files/petri-nets-23.bib'
citation: 'Wittbold, F., Bernemann, R., Heckel, R., Heindel, T., König, B. (2023). Stochastic Decision Petri Nets. In: Gomes, L., Lorenz, R. (eds) Application and Theory of Petri Nets and Concurrency. PETRI NETS 2023. Lecture Notes in Computer Science, vol 13929. Springer, Cham.'
---
We introduce stochastic decision Petri nets (SDPNs), which are a form of stochastic Petri nets equipped with rewards and a control mechanism via the deactivation of controllable transitions. Such nets can be translated into Markov decision processes (MDPs), potentially leading to a combinatorial explosion in the number of states due to concurrency. Hence we restrict ourselves to instances where nets are either safe, free-choice and acyclic nets (SAFC nets) or even occurrence nets and policies are defined by a constant deactivation pattern. We obtain complexity-theoretic results for such cases via a close connection to Bayesian networks, in particular we show that for SAFC nets the question whether there is a policy guaranteeing a reward above a certain threshold is NP^PP-complete. We also introduce a partial-order procedure which uses an SMT solver to address this problem.
