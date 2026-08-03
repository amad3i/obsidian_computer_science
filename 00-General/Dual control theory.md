---
title: "Dual control theory"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Dual_control_theory"
wikipedia_categories: ["Control theory"]
related: ["[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[American Automatic Control Council]]", "[[Anticausal system]]", "[[Artstein's theorem]]", "[[Asymptotic gain model]]"]
---

# Dual control theory

Dual control theory is a branch of control theory that deals with the control of systems whose characteristics are initially unknown.  It is called dual because in controlling such a system the controller's objectives are twofold: 

(1) Action: To control the system as well as possible based on current system knowledge
(2) Investigation: To experiment with the system so as to learn about its behavior and control it better in the future.
These two objectives may be partly in conflict.
In the context of reinforcement learning, this is known as the exploration-exploitation trade-off  (e.g. Multi-armed bandit#Empirical motivation).
Dual control theory was developed by Alexander Aronovich Fel'dbaum in 1960.  He showed that in principle the optimal solution can be found by dynamic programming, but this is often impractical; as a result a number of methods for designing sub-optimal dual controllers have been devised.

## Related

- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]
- [[Active disturbance rejection control]]
- [[Adaptive control]]
- [[Advanced process control]]
- [[Affect control theory]]
- [[American Automatic Control Council]]
- [[Anticausal system]]
- [[Artstein's theorem]]
- [[Asymptotic gain model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dual_control_theory