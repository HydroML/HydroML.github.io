---
title: "Gradient-flow SDEs have unique transient population dynamics"
collection: publications
permalink: /publication/LangevinSDEs
excerpt: ''
date: 2026-05-05
venue: 'AISTATS'
paperurl: 'https://arxiv.org/abs/2505.21770'
citation: 'Guan, V., Janssen, J., Lanzetti, N., Terpin, A., Schiebinger, G., & Robeva, E. (2026). Gradient-flow SDEs have unique transient population dynamics. arXiv preprint arXiv:2505.21770.'
---
Identifying the drift and diffusion of an SDE from its population dynamics is a notoriously challenging task. Researchers in machine learning and single-cell biology have only been able to prove a partial identifiability result: for potential-driven SDEs, the gradient-flow drift can be identified from temporal marginals if the Brownian diffusivity is already known. Existing methods therefore assume that the diffusivity is known a priori, despite it being unknown in practice. We dispel the need for this assumption by providing a complete characterization of identifiability: the gradient-flow drift and Brownian diffusivity are jointly identifiable from temporal marginals if and only if the process is observed outside of equilibrium. Given this fundamental result, we propose nn-APPEX, the first Schrodinger Bridge-based inference method that can simultaneously learn the drift and diffusion of a gradient-flow SDE solely from observed marginals. Extensive experiments show that nn-APPEX's ability to adjust its diffusion estimate enables accurate inference, while previous Schrodinger Bridge methods obtain biased drift estimates due to their assumed, and likely incorrect, diffusion.
