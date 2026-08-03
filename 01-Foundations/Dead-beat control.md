---
title: "Dead-beat control"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Dead-beat_control"
wikipedia_categories: ["Control theory", "Mathematical analysis stubs"]
related: ["[[Halanay inequality]]", "[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[American Automatic Control Council]]", "[[Anticausal system]]", "[[Artstein's theorem]]"]
---

# Dead-beat control

In discrete-time control theory, the dead-beat control problem consists of finding what input signal must be applied to a system in order to bring the output to the steady state in the smallest number of time steps.
For an Nth-order linear system it can be shown that this minimum number of steps will be at most N (depending on the initial condition), provided that the system  is null controllable (that it can be brought to state zero by some input).  The solution is to apply feedback such that all poles of the closed-loop transfer function are at the origin of the z-plane. This approach is straightforward for linear systems. However, when it comes to nonlinear systems, dead beat control is an open research problem.

## Related

- [[Halanay inequality]]
- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]
- [[Active disturbance rejection control]]
- [[Adaptive control]]
- [[Advanced process control]]
- [[Affect control theory]]
- [[American Automatic Control Council]]
- [[Anticausal system]]
- [[Artstein's theorem]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dead-beat_control