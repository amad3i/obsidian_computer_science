---
title: "Active disturbance rejection control"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Active_disturbance_rejection_control"
wikipedia_categories: ["Control theory"]
related: ["[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[American Automatic Control Council]]", "[[Anticausal system]]", "[[Artstein's theorem]]", "[[Asymptotic gain model]]", "[[Bartels–Stewart algorithm]]"]
---

# Active disturbance rejection control

Active disturbance rejection control (or ADRC, also known as automatic disturbance rejection control) is a model-free control technique used for designing controllers for systems with unknown dynamics and external disturbances. This approach only necessitates an estimated representation of the system's behavior to design controllers that effectively counteract disturbances without causing any overshooting.
ADRC has been successfully used as an alternative to PID control in many applications, such as the control of permanent magnet synchronous motors, thermal power plants and robotics. In particular, the precise control of brushless motors for joint motion is vital in high-speed industrial robot applications. However, flexible robot structures can introduce unwanted vibrations, challenging PID controllers. ADRC offers a solution by real-time disturbance estimation and compensation, without needing a detailed model.

## Related

- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]
- [[Adaptive control]]
- [[Advanced process control]]
- [[Affect control theory]]
- [[American Automatic Control Council]]
- [[Anticausal system]]
- [[Artstein's theorem]]
- [[Asymptotic gain model]]
- [[Bartels–Stewart algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Active_disturbance_rejection_control