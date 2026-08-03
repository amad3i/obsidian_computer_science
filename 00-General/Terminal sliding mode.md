---
title: "Terminal sliding mode"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Terminal_sliding_mode"
wikipedia_categories: ["Control theory"]
related: ["[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[American Automatic Control Council]]", "[[Anticausal system]]", "[[Artstein's theorem]]", "[[Asymptotic gain model]]"]
---

# Terminal sliding mode

In the early 1990s, a new type of sliding mode control, named terminal sliding modes (TSM) was invented at the Jet Propulsion Laboratory (JPL) by Venkataraman and Gulati. TSM is robust non-linear control approach.
The main idea of terminal sliding mode control evolved out of seminal work on terminal attractors done by Zak in the JPL, and is evoked by the concept of terminal attractors which guarantee finite time convergence of the states. While, in normal sliding mode, asymptotic stability is promised which leads to the convergence of the states to the origin.
But this convergence may only be guaranteed within infinite time. In TSM, a nonlinear term is introduced in the sliding surface design so that the manifold is formulated as an attractor. After the sliding surface is intercepted, the trajectory is attracted within the manifold and converges to the origin following a power rule.
There are some variations of the TSM including: Non-singular TSM, Fast TSM,
Terminal sliding mode also has been widely applied to nonlinear process control, for example, rigid robot control etc.. Several open questions still remain on the mathematical treatment of the system's behavior at the origin since it is non-Lipschitz.

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

- Wikipedia: https://en.wikipedia.org/wiki/Terminal_sliding_mode