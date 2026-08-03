---
title: "AIXI"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/AIXI"
wikipedia_categories: ["Decision theory", "Machine learning", "Optimal decisions"]
related: ["[[Exploration–exploitation dilemma]]", "[[80 Million Tiny Images]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Accelerated Linear Algebra]]", "[[Active learning (machine learning)]]", "[[Adversarial machine learning]]", "[[AI data center]]", "[[AI observability]]", "[[AIOps]]", "[[Algorithm IMED]]"]
---

# AIXI

AIXI  is a theoretical mathematical formalism for artificial general intelligence.
It combines Solomonoff induction with sequential decision theory.
AIXI was first proposed by Marcus Hutter in 2000 and several results regarding AIXI are proved in Hutter's 2005 book Universal Artificial Intelligence.
AIXI is a reinforcement learning (RL) agent. It maximizes the expected total rewards received from the environment. Intuitively, it simultaneously considers every computable hypothesis (or environment). In each time step, it looks at every possible program and evaluates how many rewards that program generates depending on the next action taken. The promised rewards are then weighted by the subjective belief that this program constitutes the true environment. This belief is computed from the length of the program: longer programs are considered less likely, in line with Occam's razor. AIXI then selects the action that has the highest expected total reward in the weighted sum of all these programs.

## Related

- [[Exploration–exploitation dilemma]]
- [[80 Million Tiny Images]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]
- [[Accelerated Linear Algebra]]
- [[Active learning (machine learning)]]
- [[Adversarial machine learning]]
- [[AI data center]]
- [[AI observability]]
- [[AIOps]]
- [[Algorithm IMED]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/AIXI