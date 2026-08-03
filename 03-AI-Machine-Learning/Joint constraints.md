---
title: "Joint constraints"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Joint_constraints"
wikipedia_categories: ["3D computer graphics", "Anatomical simulation", "Computational physics", "Computational physics stubs", "Computer graphics", "Robot kinematics"]
related: ["[[Kinematic chain]]", "[[Forward kinematics]]", "[[Inverse kinematics]]", "[[3D computer graphics]]", "[[Computational chemical methods in solid-state physics]]", "[[Decorrelation]]", "[[Density matrix embedding theory]]", "[[Fiducial marker]]", "[[Function representation]]", "[[Interactive skeleton-driven simulation]]"]
---

# Joint constraints

Joint constraints are rotational constraints on the joints of an artificial system. They are used in an inverse kinematics chain, in fields including 3D animation or robotics.  Joint constraints can be implemented in a number of ways, but the most common method is to limit rotation about the X, Y and Z axis independently. An elbow, for instance, could be represented by limiting rotation on X and Z axis to 0 degrees, and constraining the Y-axis rotation to 130 degrees.
To simulate joint constraints more accurately, dot-products can be used with an independent axis to repulse the child bones orientation from the unreachable axis. Limiting the orientation of the child bone to a border of vectors tangent to the surface of the joint, repulsing the child bone away from the border, can also be useful in the precise restriction of shoulder movement.

## Related

- [[Kinematic chain]]
- [[Forward kinematics]]
- [[Inverse kinematics]]
- [[3D computer graphics]]
- [[Computational chemical methods in solid-state physics]]
- [[Decorrelation]]
- [[Density matrix embedding theory]]
- [[Fiducial marker]]
- [[Function representation]]
- [[Interactive skeleton-driven simulation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Joint_constraints