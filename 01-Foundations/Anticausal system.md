---
title: "Anticausal system"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Anticausal_system"
wikipedia_categories: ["Control theory", "Digital signal processing", "Systems theory"]
related: ["[[Advanced process control]]", "[[Bilinear transform]]", "[[Bistritz stability criterion]]", "[[Causal system]]", "[[Control system]]", "[[Cross Gramian]]", "[[Dynamical structure function]]", "[[First-order hold]]", "[[Gap metric]]", "[[Hybrid system]]"]
---

# Anticausal system

In systems theory, an  anticausal system is a hypothetical system with outputs and internal states that depend solely on future input values. Some textbooks and published research literature might define an anticausal system to be one that does not depend on past input values, allowing also for the dependence on present input values.
An acausal system is a system that is not a causal system, as it depends on some future input values and possibly on some input values from the past or present. This is in contrast to a causal system which depends only on current and/or past input values.  This is often a topic of control theory and digital signal processing (DSP).
Anticausal systems are also acausal, but the converse is not always true.  An acausal system that has any dependence on past input values is not anticausal.
An example of acausal signal processing is the production of an output signal that is processed from an input signal that was recorded by looking at input values both forward and backward in time (from a predefined time arbitrarily denoted as the "present" time).  In reality, that "present" time input, as well as the "future" time input values, have been recorded at some time in the past, but conceptually it can be called the "present" or "future" input values in this acausal process. This type of processing cannot be done in real time as future input values are not yet known, but is done after the input signal has been recorded and is post-processed.
Digital room correction in some sound reproduction systems rely on acausal filters.

## Related

- [[Advanced process control]]
- [[Bilinear transform]]
- [[Bistritz stability criterion]]
- [[Causal system]]
- [[Control system]]
- [[Cross Gramian]]
- [[Dynamical structure function]]
- [[First-order hold]]
- [[Gap metric]]
- [[Hybrid system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Anticausal_system