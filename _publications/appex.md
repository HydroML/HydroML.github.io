---
title: "Identifying Drift, Diffusion, and Causal Structure from Temporal Snapshots"
collection: publications
permalink: /publication/appex
excerpt: ''
date: 2024-10-30
venue: 'arxiv'
paperurl: 'https://arxiv.org/abs/2410.22729'
citation: 'Guan, V., Janssen, J., Rahmani, H., Warren, A., Zhang, S., Robeva, E., & Schiebinger, G. (2024). Identifying Drift, Diffusion, and Causal Structure from Temporal Snapshots. arXiv preprint arXiv:2410.22729.'
---
Stochastic differential equations (SDEs) are a fundamental tool for modelling dynamic processes, including gene regulatory networks (GRNs), contaminant transport, financial markets, and image generation. However, learning the underlying SDE from observational data is a challenging task, especially when individual trajectories are not observable. Motivated by burgeoning research in single-cell datasets, we present the first comprehensive approach for jointly estimating the drift and diffusion of an SDE from its temporal marginals. Assuming linear drift and additive diffusion, we prove that these parameters are identifiable from marginals if and only if the initial distribution is not invariant to a class of generalized rotations, a condition that is satisfied by most distributions. We further prove that the causal graph of any SDE with additive diffusion can be recovered from the SDE parameters. To complement this theory, we adapt entropy-regularized optimal transport to handle anisotropic diffusion, and introduce APPEX (Alternating Projection Parameter Estimation from X0), an iterative algorithm designed to estimate the drift, diffusion, and causal graph of an additive noise SDE, solely from temporal marginals. We show that each of these steps are asymptotically optimal with respect to the Kullback-Leibler divergence, and demonstrate APPEX's effectiveness on simulated data from linear additive noise SDEs.
