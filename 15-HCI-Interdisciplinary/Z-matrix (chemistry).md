---
title: "Z-matrix (chemistry)"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Z-matrix_(chemistry)"
wikipedia_categories: ["Computational chemistry", "Molecular modelling"]
related: ["[[Accessible surface area]]", "[[Adaptive sampling]]", "[[Combining rules]]", "[[Docking (molecular)]]", "[[Folding@home]]", "[[Implicit solvation]]", "[[Katchalski-Katzir algorithm]]", "[[Molecular dynamics]]", "[[Molecular mechanics]]", "[[Molecular modeling on GPUs]]"]
---

# Z-matrix (chemistry)

In chemistry, the Z-matrix is a way to represent a system built of atoms. A Z-matrix is also known as an internal coordinate representation. It provides a description of each atom in a molecule in terms of its atomic number, bond length, bond angle, and dihedral angle, the so-called internal coordinates, although it is not always the case that a Z-matrix will give information regarding bonding since the matrix itself is based on a series of vectors describing atomic orientations in space. However, it is convenient to write a Z-matrix in terms of bond lengths, angles, and dihedrals since this will preserve the actual bonding characteristics. The name arises because the Z-matrix assigns the second atom along the Z axis from the first atom, which is at the origin.
Z-matrices can be converted to Cartesian coordinates and back, as the structural information content is identical, the position and orientation in space, however is not meaning the Cartesian coordinates recovered will be accurate in terms of relative positions of atoms, but will not necessarily be the same as an original set of Cartesian coordinates if you convert Cartesian coordinates to a Z matrix and back again. While the transform is conceptually straightforward,  algorithms of doing the conversion vary significantly in speed, numerical precision and parallelism. These matter because macromolecular chains, such as polymers, proteins, and DNA, can have thousands of connected atoms and atoms consecutively distant along the chain that may be close in Cartesian space (and thus small round-off errors can accumulate to large force-field errors.) The optimally fastest and most numerically accurate algorithm for conversion from torsion-space to cartesian-space is the Natural Extension Reference Frame method.  Back-conversion from Cartesian to torsion angles is simple trigonometry and has no risk of cumulative errors.
They are used for creating input geometries for molecular systems in many molecular modelling and computational chemistry programs.  A skillful choice of internal coordinates can make the interpretation of results straightforward. Also, since Z-matrices can contain molecular connectivity information (but do not always contain this information), quantum chemical calculations such as geometry optimization may be performed faster, because an educated guess is available for an initial Hessian matrix, and more natural internal coordinates are used rather than Cartesian coordinates.
The Z-matrix representation is often preferred, because this allows symmetry to be enforced upon the molecule (or parts thereof) by setting certain angles as constant. The Z-matrix simply is a representation for placing atomic positions in a relative way with the obvious convenience that the vectors it uses easily correspond to bonds. A conceptual pitfall is to assume all bonds appear as a line in the Z-matrix which is not true. For example: in ringed molecules like benzene, a z-matrix will not include all six bonds in the ring, because all of the atoms are uniquely positioned after just 5 bonds making the 6th redundant.

## Related

- [[Accessible surface area]]
- [[Adaptive sampling]]
- [[Combining rules]]
- [[Docking (molecular)]]
- [[Folding@home]]
- [[Implicit solvation]]
- [[Katchalski-Katzir algorithm]]
- [[Molecular dynamics]]
- [[Molecular mechanics]]
- [[Molecular modeling on GPUs]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Z-matrix_(chemistry)