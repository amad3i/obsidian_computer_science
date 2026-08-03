---
title: "Root mean square deviation of atomic positions"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Root_mean_square_deviation_of_atomic_positions"
wikipedia_categories: ["Bioinformatics", "Protein methods", "Statistical deviation and dispersion"]
related: ["[[CAFASP]]", "[[ChIP-exo]]", "[[ChIP-on-chip]]", "[[Chou–Fasman method]]", "[[De novo protein structure prediction]]", "[[EVA (benchmark)]]", "[[GOR method]]", "[[Homology modeling]]", "[[LiveBench]]", "[[Loop modeling]]"]
---

# Root mean square deviation of atomic positions

In bioinformatics, the root mean square deviation of atomic positions, or simply root mean square deviation (RMSD), is the measure of the average distance between the atoms (usually the backbone atoms) of superimposed molecules. In the study of globular protein conformations, one customarily measures the similarity in three-dimensional structure by the RMSD of the Cα atomic coordinates after optimal rigid body superposition.
When a dynamical system fluctuates about some well-defined average position, the RMSD from the average over time can be referred to as the RMSF or root mean square fluctuation. The size of this fluctuation can be measured, for example using Mössbauer spectroscopy or nuclear magnetic resonance, and can provide important physical information. The Lindemann index is a method of placing the RMSF in the context of the parameters of the system.
A widely used way to compare the structures of biomolecules or solid bodies is to translate and rotate one structure with respect to the other to minimize the RMSD. Coutsias, et al. presented a simple derivation, based on quaternions, for the optimal solid body transformation (rotation-translation) that minimizes the RMSD between two sets of vectors. They proved that the quaternion method is equivalent to the well-known Kabsch algorithm. The solution given by Kabsch is an instance of the solution of the d-dimensional problem, introduced by Hurley and Cattell. The quaternion solution to compute the optimal rotation was published in the appendix of a paper of Petitjean. This quaternion solution and the calculation of the optimal isometry in the d-dimensional case were both extended to infinite sets and to the continuous case in the appendix A of another paper of Petitjean.

## Related

- [[CAFASP]]
- [[ChIP-exo]]
- [[ChIP-on-chip]]
- [[Chou–Fasman method]]
- [[De novo protein structure prediction]]
- [[EVA (benchmark)]]
- [[GOR method]]
- [[Homology modeling]]
- [[LiveBench]]
- [[Loop modeling]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Root_mean_square_deviation_of_atomic_positions