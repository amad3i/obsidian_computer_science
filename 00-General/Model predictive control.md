---
title: "Model predictive control"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Model_predictive_control"
wikipedia_categories: ["Control theory"]
related: ["[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[American Automatic Control Council]]", "[[Anticausal system]]", "[[Artstein's theorem]]", "[[Asymptotic gain model]]"]
---

# Model predictive control

Model predictive control (MPC) is an advanced method of process control that is used to control a process while satisfying a set of constraints.  Model predictive controllers rely on dynamic models of the process, most often linear empirical models obtained by system identification. The main advantage of MPC is the fact that it allows the current timeslot to be optimized, while keeping future timeslots in account. This is achieved by optimizing a finite time-horizon, but only implementing the current timeslot and then optimizing again, repeatedly, thus differing from a linear–quadratic regulator (LQR). Also MPC has the ability to anticipate future events and can take control actions accordingly. PID controllers do not have this predictive ability. MPC is nearly universally implemented as a digital control, although there is research into achieving faster response times with specially designed analog circuitry.
It has been in use in the process industries in chemical plants and oil refineries since the 1980s. In recent years it has also been used in power system balancing models and in power electronics.
Generalized predictive control (GPC) and dynamic matrix control (DMC) are classical examples of MPC.

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

- Wikipedia: https://en.wikipedia.org/wiki/Model_predictive_control