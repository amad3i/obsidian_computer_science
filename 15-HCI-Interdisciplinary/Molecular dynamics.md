---
title: "Molecular dynamics"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Molecular_dynamics"
wikipedia_categories: ["Computational chemistry", "Molecular dynamics", "Molecular modelling", "Simulation"]
related: ["[[Accessible surface area]]", "[[Combining rules]]", "[[Implicit solvation]]", "[[Molecular modeling on GPUs]]", "[[Shifted force method]]", "[[Activation strain model]]", "[[Adaptive sampling]]", "[[Car–Parrinello molecular dynamics]]", "[[Cell lists]]", "[[Constraint (computational chemistry)]]"]
---

# Molecular dynamics

Molecular dynamics (MD) is a computer simulation method for analyzing the physical movements of atoms and molecules. The atoms and molecules are allowed to interact for a fixed period of time, giving a view of the dynamic "evolution" of the system. In the most common version, the trajectories of atoms and molecules are determined by numerically solving Newton's equations of motion for a system of interacting particles, where forces between the particles and their potential energies are often calculated using interatomic potentials or molecular mechanical force fields. MD simulations are widely applied in chemical physics, materials science, and biophysics.
Because molecular systems typically consist of a vast number of particles, it is impossible to determine the properties of such complex systems analytically; MD simulation circumvents this problem by using numerical methods. However, long MD simulations are mathematically ill-conditioned, generating cumulative errors in numerical integration that can be minimized with proper selection of algorithms and parameters, but not eliminated.
For systems that obey the ergodic hypothesis, the evolution of one molecular dynamics simulation may be used to determine the macroscopic thermodynamic properties of the system: the time averages of an ergodic system correspond to microcanonical ensemble averages. MD has also been termed "statistical mechanics by numbers" and "Laplace's vision of Newtonian mechanics" of predicting the future by animating nature's forces and allowing insight into molecular motion on an atomic scale.

## Related

- [[Accessible surface area]]
- [[Combining rules]]
- [[Implicit solvation]]
- [[Molecular modeling on GPUs]]
- [[Shifted force method]]
- [[Activation strain model]]
- [[Adaptive sampling]]
- [[Car–Parrinello molecular dynamics]]
- [[Cell lists]]
- [[Constraint (computational chemistry)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Molecular_dynamics