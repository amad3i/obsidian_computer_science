---
title: "Gaussian process emulator"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Gaussian_process_emulator"
wikipedia_categories: ["Bayesian statistics", "Ensemble learning", "Statistical randomness"]
related: ["[[Abductive reasoning]]", "[[AdaBoost]]", "[[Alignments of random points]]", "[[Aumann's agreement theorem]]", "[[Base rate]]", "[[Bayesian efficiency]]", "[[Bayesian interpretation of kernel regularization]]", "[[Bayesian program synthesis]]", "[[Bayesian programming]]", "[[Bayesian regret]]"]
---

# Gaussian process emulator

In statistics, Gaussian process emulator is one name for a general type of statistical model that has been used in contexts where the problem is to make maximum use of the outputs of a complicated (often non-random) computer-based simulation model. Each run of the simulation model is computationally expensive and each run is based on many different controlling inputs. The variation of the outputs of the simulation model is expected to vary reasonably smoothly with the inputs, but in an unknown way.
The overall analysis involves two models: the simulation model, or "simulator", and the statistical model, or "emulator", which notionally emulates the unknown outputs from the simulator.
The Gaussian process emulator model treats the problem from the viewpoint of Bayesian statistics. In this approach, even though the output of the simulation model is fixed for any given set of inputs, the actual outputs are unknown unless the computer model is run and hence can be made the subject of a Bayesian analysis. The main element of the Gaussian process emulator model is that it models the outputs as a Gaussian process on a space that is defined by the model inputs. The model includes a description of the correlation or covariance of the outputs, which enables the model to encompass the idea that differences in the output will be small if there are only small differences in the inputs.

## Related

- [[Abductive reasoning]]
- [[AdaBoost]]
- [[Alignments of random points]]
- [[Aumann's agreement theorem]]
- [[Base rate]]
- [[Bayesian efficiency]]
- [[Bayesian interpretation of kernel regularization]]
- [[Bayesian program synthesis]]
- [[Bayesian programming]]
- [[Bayesian regret]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Gaussian_process_emulator