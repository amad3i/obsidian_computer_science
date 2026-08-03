---
title: "Robust control"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Robust_control"
wikipedia_categories: ["Control theory", "Stochastic control"]
related: ["[[Optimal projection equations]]", "[[Separation principle]]", "[[Separation principle in stochastic control]]", "[[Stochastic control]]", "[[Witsenhausen's counterexample]]", "[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]"]
---

# Robust control

A central theme of control theory is feedback regulation--the design a feedback controller to achieve stability and a level of performance for a given dynamical system. Tolerance to modeling uncertainty is an essential part of any feedback control scheme, that is, the ability to maintain a satisfactory level of performance when the system dynamics deviate from the nominal value used in the design. The ability of a feedback control system to maintain stability and performance under uncertainty is referred to as robustness.
The term robust control refers to theory of feedback regulation that began taking shape in the late 1970's and onwards, where modeling uncertainty is explicitly acknowledged, modeled, and taken into account in control design. Modeling uncertainty is typically quantified, as is performance, and together are sought to be optimized by casting control design as a suitable optimization problem. 
The ability of feedback to cope with uncertainty has been the main reason behind the emergence of the field of control, from its inception in antiquity for Ctesibius' mechanisms, onto Watt's centrifugal governor, and Harold Black's negative-feedback amplifier. Robustness was too the main issue in the classical period of the development of control theory by Bode and Nyquist. Yet, the term robust control was not used until the 1980's when modern methods started being developed to optimize for parametric and non-parametric modeling uncertainty.
Parametric uncertainty refers to the case where modeling parameters or external disturbances in feedback regulation are expected to be found within some (typically compact) set of a finite dimensional space. Thence, robust control aims to achieve robust performance and stability in the presence of such bounded modeling errors. Non-parametric uncertainty refers to the case where the magnitude of expected modeling errors and disturbances is quantified via metrics on function spaces where these reside (infinite dimensional). The term robust control became almost synonymous with the term H-infinity control, since it was the techniques in the development of the latter that gave the early impetus for the new methods.
The early methods of Bode, Nyquist, and others were robust (non-robust control would indeed be a contradiction of terms); they were designed to be, and they were aimed at assessing the level of robustness as well. In contrast, state-space methods that were developed in the 1960s and 1970s did not explicitly account for modeling uncertainty, and often lacked satisfactory levels of robustness, prompting critique from the students of the earlier classical era. The start of the theory of robust control grew out of this critique, took shape in the 1980s and 1990s, and is still active today.
A somewhat different angle in addressing control problems
forms the core of what is known as adaptive control. The rationale in this is to design regulation that is not only able to tolerate uncertainty but also to adapt by refining the control mechanism. By necessity, adaptive control schemes are nonlinear, in that the values of control parameters vary as a function of the available measurements. Once again, assumptions on the range of value of system parameters is needed in order to develop a systematic design methodology.

## Related

- [[Optimal projection equations]]
- [[Separation principle]]
- [[Separation principle in stochastic control]]
- [[Stochastic control]]
- [[Witsenhausen's counterexample]]
- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]
- [[Active disturbance rejection control]]
- [[Adaptive control]]
- [[Advanced process control]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Robust_control