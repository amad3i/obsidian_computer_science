---
title: "Implicit solvation"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Implicit_solvation"
wikipedia_categories: ["Computational chemistry", "Molecular dynamics", "Molecular modelling", "Protein structure"]
related: ["[[Accessible surface area]]", "[[Combining rules]]", "[[Docking (molecular)]]", "[[Folding@home]]", "[[Molecular dynamics]]", "[[Molecular modeling on GPUs]]", "[[Scoring functions for docking]]", "[[Shifted force method]]", "[[Adaptive sampling]]", "[[Backbone-dependent rotamer library]]"]
---

# Implicit solvation

Implicit solvation (sometimes termed continuum solvation) is a method to represent solvent as a continuous medium instead of individual "explicit" solvent molecules, most often used in molecular dynamics simulations and in other applications of molecular mechanics.  The method is often applied to estimate free energy of solute-solvent interactions in structural and chemical processes, such as folding or conformational transitions of proteins, DNA, RNA, and polysaccharides, association of biological macromolecules with ligands, or transport of drugs across biological membranes.
The implicit solvation model is justified in liquids, where the potential of mean force can be applied to approximate the averaged behavior of many highly dynamic solvent molecules.  However, the interfaces and the interiors of biological membranes or proteins can also be considered as media with specific solvation or dielectric properties. These media are not necessarily uniform, since their properties can be described by different analytical functions, such as "polarity profiles" of lipid bilayers. 
There are two basic types of implicit solvent methods: models based on accessible surface areas (ASA) that were historically the first, and more recent continuum electrostatics models, although various modifications and combinations of the different methods are possible.   
The accessible surface area (ASA) method is based on experimental linear relations between Gibbs free energy of transfer and the surface area of a solute molecule. This method operates directly with free energy of solvation, unlike molecular mechanics or electrostatic methods that include only the enthalpic component of free energy. The continuum representation of solvent also significantly improves the computational speed and reduces errors in statistical averaging that arise from incomplete sampling of solvent conformations, so that the energy landscapes obtained with  implicit and explicit solvent are different. Although the implicit solvent model is useful for simulations of biomolecules, this is an approximate method with certain limitations and problems related to parameterization and treatment of ionization effects.

## Related

- [[Accessible surface area]]
- [[Combining rules]]
- [[Docking (molecular)]]
- [[Folding@home]]
- [[Molecular dynamics]]
- [[Molecular modeling on GPUs]]
- [[Scoring functions for docking]]
- [[Shifted force method]]
- [[Adaptive sampling]]
- [[Backbone-dependent rotamer library]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Implicit_solvation