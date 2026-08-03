---
title: "Constraint (computational chemistry)"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Constraint_(computational_chemistry)"
wikipedia_categories: ["Computational chemistry", "Computational physics", "Molecular dynamics", "Molecular physics", "Numerical differential equations"]
related: ["[[Cell lists]]", "[[Car–Parrinello molecular dynamics]]", "[[Umbrella sampling]]", "[[Accessible surface area]]", "[[Bond order potential]]", "[[CCPForge]]", "[[Combining rules]]", "[[Computational chemical methods in solid-state physics]]", "[[Computational chemistry]]", "[[Density matrix embedding theory]]"]
---

# Constraint (computational chemistry)

In computational chemistry, a constraint algorithm is a method for satisfying the  Newtonian motion of a rigid body which consists of mass points. A restraint algorithm is used to ensure that the distance between mass points is maintained. The general steps involved are: (i) choose novel unconstrained coordinates (internal coordinates), (ii) introduce explicit constraint forces, (iii) minimize constraint forces implicitly by the technique of Lagrange multipliers or projection methods.
Constraint algorithms are often applied to molecular dynamics simulations. Although such simulations are sometimes performed using internal coordinates that automatically satisfy the bond-length, bond-angle and torsion-angle constraints, simulations may also be performed using explicit or implicit constraint forces for these three constraints. However, explicit constraint forces give rise to inefficiency; more computational power is required to get a trajectory of a given length. Therefore, internal coordinates and implicit-force constraint solvers are generally preferred.
Constraint algorithms achieve computational efficiency by neglecting motion along some degrees of freedom. For instance, in atomistic molecular dynamics, typically the length of covalent bonds to hydrogen are constrained; however, constraint algorithms should not be used if vibrations along these degrees of freedom are important for the phenomenon being studied.

## Related

- [[Cell lists]]
- [[Car–Parrinello molecular dynamics]]
- [[Umbrella sampling]]
- [[Accessible surface area]]
- [[Bond order potential]]
- [[CCPForge]]
- [[Combining rules]]
- [[Computational chemical methods in solid-state physics]]
- [[Computational chemistry]]
- [[Density matrix embedding theory]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Constraint_(computational_chemistry)