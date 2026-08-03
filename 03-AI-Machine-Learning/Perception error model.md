---
title: "Perception error model"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Perception_error_model"
wikipedia_categories: ["Machine learning", "Self-driving cars", "Simulation"]
related: ["[[Automation in construction]]", "[[80 Million Tiny Images]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Accelerated Linear Algebra]]", "[[Activation strain model]]", "[[Active learning (machine learning)]]", "[[Adversarial machine learning]]", "[[AI data center]]", "[[AI observability]]", "[[AIOps]]"]
---

# Perception error model

In autonomous vehicle testing, a perception error model (PEM) is an approach to simulating the behaviour of sensing and perception systems by modeling the errors they produce rather than simulating the underlying sensor physics. This differs from high-fidelity sensor simulation techniques, where one wishes to generate synthetic sensor signals that the actual perception algorithms would process. Perception error models are sometimes referred to as surrogate models for perception systems, because they approximate the output of computationally expensive object detectors at a fraction of the computational cost.
The primary motivation for PEMs is to enable efficient virtual testing of autonomous vehicle driving policies. Since the failure modes of perception systems have significant impact on downstream planning and control, testing these systems requires capturing the dependencies between perception errors and vehicle behaviour. PEMs provide a computationally efficient alternative to running full physics-based sensor simulations with actual perception algorithms.

## Related

- [[Automation in construction]]
- [[80 Million Tiny Images]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]
- [[Accelerated Linear Algebra]]
- [[Activation strain model]]
- [[Active learning (machine learning)]]
- [[Adversarial machine learning]]
- [[AI data center]]
- [[AI observability]]
- [[AIOps]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Perception_error_model