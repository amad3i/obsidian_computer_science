---
title: "Bidomain model"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Bidomain_model"
wikipedia_categories: ["Cardiac electrophysiology", "Electrophysiology", "Mathematical modeling", "Numerical analysis", "Partial differential equations"]
related: ["[[Forward problem of electrocardiology]]", "[[Bueno-Orovio–Cherry–Fenton model]]", "[[Calderón projector]]", "[[Integrable algorithm]]", "[[Iterative rational Krylov algorithm]]", "[[Model order reduction]]", "[[Movable cellular automaton]]", "[[Multigrid method]]", "[[Partial differential algebraic equation]]", "[[Proper generalized decomposition]]"]
---

# Bidomain model

The bidomain model is a mathematical model to define the electrical activity of the heart. It consists in a continuum (volume-average) approach in which the cardiac microstructure is defined in terms of muscle fibers grouped in sheets, creating a complex three-dimensional structure with anisotropical properties. Then, to define the electrical activity, two interpenetrating domains are considered, which are the intracellular and extracellular domains, representing respectively the space inside the cells and the region between them.
The bidomain model was first proposed by Schmitt in 1969 before being formulated mathematically in the late 1970s.
Since it is a continuum model, rather than describing each cell individually, it represents the average properties and behaviour of group of cells organized in complex structure. Thus, the model results to be a complex one and can be seen as a generalization of the cable theory to higher dimensions and, going to define the so-called bidomain equations.
Many of the interesting properties of the bidomain model arise from the condition of unequal anisotropy ratios. The electrical conductivity in anisotropic tissues is not unique in all directions, but it is different in parallel and perpendicular direction with respect to the fiber one.
Moreover, in tissues with unequal anisotropy ratios, the ratio of conductivities parallel and perpendicular to the fibers are different in the intracellular and extracellular spaces. For instance, in cardiac tissue, the anisotropy ratio in the intracellular space is about 10:1, while in the extracellular space it is about 5:2.
Mathematically, unequal anisotropy ratios means that the effect of anisotropy cannot be removed by a change in the distance scale in one direction.
Instead, the anisotropy has a more profound influence on the electrical behavior.
Three examples of the impact of unequal anisotropy ratios are

the distribution of transmembrane potential during unipolar stimulation of a sheet of cardiac tissue,
the magnetic field produced by an action potential wave front propagating through cardiac tissue,
the effect of fiber curvature on the transmembrane potential distribution during an electric shock.

## Related

- [[Forward problem of electrocardiology]]
- [[Bueno-Orovio–Cherry–Fenton model]]
- [[Calderón projector]]
- [[Integrable algorithm]]
- [[Iterative rational Krylov algorithm]]
- [[Model order reduction]]
- [[Movable cellular automaton]]
- [[Multigrid method]]
- [[Partial differential algebraic equation]]
- [[Proper generalized decomposition]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bidomain_model