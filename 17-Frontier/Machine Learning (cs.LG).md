---
title: "Machine Learning"
tags: [cs, frontier, arxiv]
domain: Frontier
level: frontier
source: "https://arxiv.org/list/cs.LG/recent"
---

# Machine Learning (cs.LG)

Frontier research area. Live listing: https://arxiv.org/list/cs.LG/recent

## Recent papers (real, from arXiv)

### Differentially Private Nonparametric Modal Learning with Applications to Regression and Clustering

Density modes provide a localized and interpretable summary of multimodal distributions, but their estimation under rigorous differential privacy constraints remains largely unexplored. We study differentially private recovery of density modes for multivariate distributions under local smoothness, curvature, and separation conditions. We propose DP-GRAMS, a mean-shift inspired method that performs noisy ascent on a differentially private score estimator. Assuming the density belongs locally to a Hölder class with smoothness parameter $β> 2$, our score estimator uses bias-reducing higher-order kernels, and then enforces privacy in the gradient ascent steps via gradient clipping and calibrated Gaussian noise. A private initialization scheme combines a density-aware utility with a suppression rule and, with $k\asymp M\log n$ draws over a public $h_{\mathrm{DAP}}$-grid and suppression radius

- http://arxiv.org/abs/2607.29675v1

### Sign compression for Muon: SignMuon, MuonSign, and the Limits of Error Feedback

SignMuon compresses the Muon update to one bit per parameter by taking its elementwise sign, providing the most direct way to run a matrix-aware optimizer under an extremely low communication budget. It outperforms SignSGD in practice, yet it can ascend even on a linear function. Signing the gradient before the Linear Minimization Oracle (LMO), rather than after, does not repair this: we construct a small explicit instance on which sign-before (MuonUSign) and sign-on-both-sides (MuonSign) ascend as well, so no placement of the sign around the oracle descends in general. Error feedback, the standard remedy for a biased compressor, does not rescue SignMuon: when applied to Muon's output, error feedback can fail for every smoothness constant, step size, and momentum. Applied to the gradient, error feedback does work, and EF21-MuonUSign and EF21-MuonSign attain the standard $\mathcal{O}(T^{-

- http://arxiv.org/abs/2607.29674v1

### Freeze, Then Select: Structured Field Adapters and Stability-Validated Weak Selection for PDE Discovery from Sparse Observations

PDE discovery from sparse observations requires reconstructing a continuous field and selecting the correct differential terms. Our analysis of optimization paths in coupled neural PDE discovery reveals three behaviors: the exact support can persist to the end of training, appear only transiently, or fail to emerge. To decouple equation selection from neural optimization, we develop a freeze-then-select method combining a structured field adapter with Stability-Validated Weak Selection (SVWS). Trained from observations without a PDE residual, the adapter factorizes the field into learned spatial features and temporal coefficients represented by cubic splines. After freezing the field, SVWS identifies recurrent terms across independent weak-form systems, refits candidate supports, and selects the final equation on held-out weak-form systems. Beyond fixed libraries, we apply the same princ

- http://arxiv.org/abs/2607.29665v1

## Sources

- https://arxiv.org/list/cs.LG/recent