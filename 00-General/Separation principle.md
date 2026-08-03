---
title: "Separation principle"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Separation_principle"
wikipedia_categories: ["Control theory", "Stochastic control"]
related: ["[[Optimal projection equations]]", "[[Robust control]]", "[[Separation principle in stochastic control]]", "[[Stochastic control]]", "[[Witsenhausen's counterexample]]", "[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]"]
---

# Separation principle

In control theory, a separation principle, more formally known as a principle of separation of estimation and control, states that under some assumptions the problem of designing an optimal feedback controller for a stochastic system can be solved by designing an optimal observer for the state of the system, which feeds into an optimal deterministic controller for the system.  Thus the problem can be broken into two separate parts, which facilitates the design.
The first instance of such a principle is in the setting of deterministic linear systems, namely that if a stable observer and a stable state feedback are designed for a linear time-invariant system (LTI system hereafter), then the combined observer and feedback is stable. The separation principle does not hold in general for nonlinear systems.
Another instance of the separation principle arises in the setting of linear stochastic systems, namely that state estimation (possibly nonlinear) together with an optimal state feedback controller designed to minimize a quadratic cost, is optimal for the stochastic control problem with output measurements. When process and observation noise are Gaussian, the optimal solution separates into a Kalman filter and a linear-quadratic regulator. This is known as linear-quadratic-Gaussian control. More generally, under suitable conditions and when the noise is a martingale (with possible jumps), again a separation principle applies and is known as the separation principle in stochastic control.
The separation principle also holds for high gain observers used for state estimation of a class of nonlinear systems and control of quantum systems.

## Related

- [[Optimal projection equations]]
- [[Robust control]]
- [[Separation principle in stochastic control]]
- [[Stochastic control]]
- [[Witsenhausen's counterexample]]
- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]
- [[Active disturbance rejection control]]
- [[Adaptive control]]
- [[Advanced process control]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Separation_principle