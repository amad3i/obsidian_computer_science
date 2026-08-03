---
title: "Intermittent control"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Intermittent_control"
wikipedia_categories: ["Control theory", "Cybernetics", "Feedback", "Motor control"]
related: ["[[Negative feedback]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[Control reconfiguration]]", "[[Feedback]]", "[[Fractional-order control]]", "[[Full state feedback]]", "[[Input shaping]]", "[[Internal model (motor control)]]", "[[Machine learning control]]"]
---

# Intermittent control

Intermittent control is a type of feedback control where adjustments are not made continuously, but rather in a series of distinct, separate bursts of action. It is used to model human control systems and also has applications in control engineering.
A simple analogy is steering a car. A driver does not apply a perfectly constant steering force but instead makes a series of small, corrective movements of the steering wheel, followed by brief pauses to observe the effect. This "observe-act-wait" cycle is the core of intermittent control. The concept first appeared in studies of human reaction time and motor skills, where it was observed that people act as "an intermittent correction servo."
In control theory, intermittent control is considered a hybrid between continuous control (where corrections are always being made) and discrete-time control (where corrections are made at fixed, clock-like intervals). In intermittent control, the control action is applied over a period of time, but the decision to act is event-driven—triggered by, for example, the system's state deviating too far from the desired state. This approach is useful in networked control systems, where continuous feedback may be impossible or costly, and in predictive control systems that require time for optimization calculations.

## Related

- [[Negative feedback]]
- [[Advanced process control]]
- [[Affect control theory]]
- [[Control reconfiguration]]
- [[Feedback]]
- [[Fractional-order control]]
- [[Full state feedback]]
- [[Input shaping]]
- [[Internal model (motor control)]]
- [[Machine learning control]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Intermittent_control