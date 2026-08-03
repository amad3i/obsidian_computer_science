---
title: "Self-avoiding walk"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Self-avoiding_walk"
wikipedia_categories: ["Computational chemistry", "Computational physics", "Discrete geometry", "Polygons", "Variants of random walks"]
related: ["[[Bond order potential]]", "[[Car–Parrinello molecular dynamics]]", "[[CCPForge]]", "[[Cell lists]]", "[[Computational chemical methods in solid-state physics]]", "[[Computational chemistry]]", "[[Constraint (computational chemistry)]]", "[[Density matrix embedding theory]]", "[[Hartree–Fock method]]", "[[Intracule]]"]
---

# Self-avoiding walk

In mathematics, a self-avoiding walk (SAW) is a sequence of moves on a lattice (a lattice path) that does not visit the same point more than once. This is a special case of the graph theoretical notion of a path. A self-avoiding polygon (SAP) is a closed self-avoiding walk on a lattice. Very little is known rigorously about the self-avoiding walk from a mathematical perspective, although physicists have provided numerous conjectures that are believed to be true and are strongly supported by numerical simulations.
In computational physics, a self-avoiding walk is a chain-like path in R2 or R3 with a certain number of nodes, typically a fixed step length and has the property that it doesn't cross itself or another walk. A system of SAWs satisfies the so-called excluded volume condition. In higher dimensions, the SAW is believed to behave much like the ordinary random walk.
SAWs and SAPs play a central role in the modeling of the topological and knot-theoretic behavior of thread- and loop-like molecules such as proteins. Indeed, SAWs may have first been introduced by the chemist Paul Flory  in order to model the real-life behavior of chain-like entities such as solvents and polymers, whose physical volume prohibits multiple occupation of the same spatial point.
SAWs are fractals. For example, in d = 2 the fractal dimension is 4/3, for d = 3 it is close to 5/3 while for d ≥ 4 the fractal dimension is 2. The dimension is called the upper critical dimension above which excluded volume is negligible. A SAW that does not satisfy the excluded volume condition was recently studied to model explicit surface geometry resulting from expansion of a SAW. The average size of a self-avoiding walk increases with respect to its length according to an exponent that is the reciprocal of the fractal dimension. The radius of gyration of a SAW depends on the 3/4 power of length in two dimensions, and approximately the 3/5th power in three dimensions.
The properties of SAWs cannot be calculated analytically, so numerical simulations are employed. The pivot algorithm is a common method for Markov chain Monte Carlo simulations for the uniform measure on n-step self-avoiding walks. The pivot algorithm works by taking a self-avoiding walk and randomly choosing a point on this walk, and then applying symmetrical transformations (rotations and reflections) on the walk after the nth step to create a new walk.
Calculating the number of self-avoiding walks in any given lattice is a common computational problem. There is currently no known formula, although there are rigorous methods of approximation.

## Related

- [[Bond order potential]]
- [[Car–Parrinello molecular dynamics]]
- [[CCPForge]]
- [[Cell lists]]
- [[Computational chemical methods in solid-state physics]]
- [[Computational chemistry]]
- [[Constraint (computational chemistry)]]
- [[Density matrix embedding theory]]
- [[Hartree–Fock method]]
- [[Intracule]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Self-avoiding_walk