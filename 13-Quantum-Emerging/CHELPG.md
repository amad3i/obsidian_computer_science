---
title: "CHELPG"
tags: ["cs", "quantum-emerging", "intermediate"]
domain: Quantum & Emerging
level: intermediate
source: "https://en.wikipedia.org/wiki/CHELPG"
wikipedia_categories: ["Computational chemistry", "Quantum chemistry", "Theoretical chemistry"]
related: ["[[Adiabatic connection fluctuation dissipation theorem]]", "[[Basis set (chemistry)]]", "[[Car–Parrinello molecular dynamics]]", "[[Coulomb operator]]", "[[Distributed multipole analysis]]", "[[Energy level]]", "[[Full configuration interaction]]", "[[Görling–Levy perturbation theory]]", "[[Hamiltonian (quantum mechanics)]]", "[[Hartree equations]]"]
---

# CHELPG

CHELPG (CHarges from ELectrostatic Potentials using a Grid-based method) is an atomic charge calculation scheme developed by Breneman and Wiberg, in which atomic charges are fitted to reproduce the molecular electrostatic potential (MESP) at a number of points around the molecule.
The charge calculation methods based on fitting of MESP (including CHELPG) are not well-suitable for the treatment of larger systems, where some of the innermost atoms are located far away from the points at which the MESP is computed. In such a situation, variations of the innermost atomic charges will not lead to significant changes of the MESP outside of the molecule, which means accurate values for the innermost atomic charges are not well-determined by the MESP outside of the molecule. This problem is solved by density derived electrostatic and chemical (DDEC) methods that partition the electron density cloud in order to provide chemically meaningful net atomic charges that approximately reproduce the electrostatic potential surrounding the material.
It should be remembered that atomic charges depend on the molecular conformation. The representative atomic charges for flexible molecules hence should be computed as average values over several molecular conformations. 
A number of alternative MESP charge schemes have been developed, such as those employing Connolly surfaces or geodesic point selection algorithms, in order to improve rotational invariance by increasing the point selection density and reducing anisotropies in the sampled points on the MESP surface. While CHELPG is restricted to non-periodic (e.g., molecular) systems, the DDEC methods can be applied to both non-periodic and periodic materials. 
CHELPG charges can be computed using the popular ab initio quantum chemical packages such as Gaussian, GAMESS-US and ORCA.

## Related

- [[Adiabatic connection fluctuation dissipation theorem]]
- [[Basis set (chemistry)]]
- [[Car–Parrinello molecular dynamics]]
- [[Coulomb operator]]
- [[Distributed multipole analysis]]
- [[Energy level]]
- [[Full configuration interaction]]
- [[Görling–Levy perturbation theory]]
- [[Hamiltonian (quantum mechanics)]]
- [[Hartree equations]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/CHELPG