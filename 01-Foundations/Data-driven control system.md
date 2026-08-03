---
title: "Data-driven control system"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Data-driven_control_system"
wikipedia_categories: ["Computational mathematics", "Control engineering", "Control theory", "Dynamical systems", "Robotics engineering"]
related: ["[[Rise time]]", "[[Ackermann's formula]]", "[[American Automatic Control Council]]", "[[Control reconfiguration]]", "[[Control system]]", "[[Control theory]]", "[[Hall circles]]", "[[Hierarchical control system]]", "[[Hybrid system]]", "[[Masreliez's theorem]]"]
---

# Data-driven control system

Data-driven control systems are a broad family of control systems, in which the identification of the process model and/or the design of the controller are based entirely on experimental data collected from the plant.
In many control applications, trying to write a mathematical model of the plant is considered a hard task, requiring efforts and time to the process and control engineers. This problem is overcome by data-driven methods, which fit a system model to the experimental data collected, choosing it in a specific models class. The control engineer can then exploit this model to design a proper controller for the system. However, it is still difficult to find a simple yet reliable model for a physical system, that includes only those dynamics of the system that are of interest for the control specifications. The direct data-driven methods allow to tune a controller, belonging to a given class, without the need of an identified model of the system. In this way, one can also simply weight process dynamics of interest inside the control cost function, and exclude those dynamics that are out of interest.

## Related

- [[Rise time]]
- [[Ackermann's formula]]
- [[American Automatic Control Council]]
- [[Control reconfiguration]]
- [[Control system]]
- [[Control theory]]
- [[Hall circles]]
- [[Hierarchical control system]]
- [[Hybrid system]]
- [[Masreliez's theorem]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Data-driven_control_system