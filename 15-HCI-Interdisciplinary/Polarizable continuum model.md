---
title: "Polarizable continuum model"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Polarizable_continuum_model"
wikipedia_categories: ["Computational chemistry"]
related: ["[[1s Slater-type function]]", "[[Ab initio quantum chemistry methods]]", "[[Accessible surface area]]", "[[Activation strain model]]", "[[Adaptive sampling]]", "[[Adiabatic connection fluctuation dissipation theorem]]", "[[Alexander Boldyrev]]", "[[Basis set (chemistry)]]", "[[Bette Korber]]", "[[Bond order potential]]"]
---

# Polarizable continuum model

The polarizable continuum model (PCM) is a commonly used method in computational chemistry to model solvation effects.  When it is necessary to consider each solvent molecule as a separate molecule, the computational cost of modeling a solvent-mediated chemical reaction becomes prohibitively high.  Modeling the solvent as a polarizable continuum, rather than individual molecules, makes ab initio computation more readily achievable. Two types of PCMs have been popularly used: the dielectric PCM (D-PCM), in which the continuum is polarizable (see dielectrics), and the conductor-like PCM (C-PCM), in which the continuum is conductor-like, similar to the COSMO Solvation Model.
The molecular free energy of solvation is computed as the sum of three terms:

Gsol = Ges + Gdr + Gcav
Ges = electrostatic
Gdr = dispersion-repulsion
Gcav = cavitation
The Charge-transfer effect is also considered as a part of solvation in cases.
The PCM solvation model is available for calculating energies and gradients at the Hartree–Fock and density functional theory (DFT) levels in several quantum chemical computational packages such as Gaussian, GAMESS and JDFTx.
The authors of a 2002 paper observe that PCM has limitations where non-electrostatic effects dominate the solute-solvent interactions.  They write in the abstract: "Since only electrostatic solute-solvent interactions are included in the PCM, our results lead to the conclusion that, for the seven molecules studied, in cyclohexane, acetone, methanol, and acetonitrile electrostatic effects are dominant while in carbon tetrachloride, benzene, and chloroform other nonelectrostatic effects are more important."
There is an integral equation formalism (IEF) version of the PCM which is very commonly used.
PCM is also used to model outer solvation layers in multi-layered solvation approach.

## Related

- [[1s Slater-type function]]
- [[Ab initio quantum chemistry methods]]
- [[Accessible surface area]]
- [[Activation strain model]]
- [[Adaptive sampling]]
- [[Adiabatic connection fluctuation dissipation theorem]]
- [[Alexander Boldyrev]]
- [[Basis set (chemistry)]]
- [[Bette Korber]]
- [[Bond order potential]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Polarizable_continuum_model