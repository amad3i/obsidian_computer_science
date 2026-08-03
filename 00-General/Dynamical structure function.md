---
title: "Dynamical structure function"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Dynamical_structure_function"
wikipedia_categories: ["Control theory", "Systems theory"]
related: ["[[Anticausal system]]", "[[Control system]]", "[[Cross Gramian]]", "[[Gap metric]]", "[[Hybrid system]]", "[[Internal environment]]", "[[Positive systems]]", "[[Sampled data system]]", "[[Steady state]]", "[[Transfer function matrix]]"]
---

# Dynamical structure function

In control theory and systems theory, a dynamical structure function (DSF) is a representation of a linear time-invariant system that preserves the system's transfer function while also describing signal dependencies among a chosen set of measured, or manifest, variables. It is commonly used to represent the signal structure of a dynamic network: the directed dynamical dependencies among measured variables and the direct influence of external inputs on those variables.
The representation was introduced by Jorge Gonçalves and Sean Warnick in work on reconstructing LTI networks from input-output data and additional structural assumptions. A related formulation by Gonçalves and Warnick gave necessary and sufficient conditions for reconstructing an LTI network's dynamical structure from input-output data together with additional structural assumptions.
A DSF may be regarded as intermediate between a full state-space representation and an input-output transfer function. A transfer function records the behavior from external inputs to measured outputs but, by itself, does not generally determine the internal signal dependencies among measured variables. A state-space realization contains internal variables, but different realizations of the same transfer function may have different state coordinates and different apparent internal structures. A DSF fixes a set of manifest variables and describes how these variables dynamically influence one another after hidden variables have been algebraically or dynamically eliminated.

## Related

- [[Anticausal system]]
- [[Control system]]
- [[Cross Gramian]]
- [[Gap metric]]
- [[Hybrid system]]
- [[Internal environment]]
- [[Positive systems]]
- [[Sampled data system]]
- [[Steady state]]
- [[Transfer function matrix]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dynamical_structure_function