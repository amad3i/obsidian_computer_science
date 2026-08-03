---
title: "COSMO-RS"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/COSMO-RS"
wikipedia_categories: ["Computational chemistry", "Thermodynamic models"]
related: ["[[1s Slater-type function]]", "[[Ab initio quantum chemistry methods]]", "[[Accessible surface area]]", "[[Activation strain model]]", "[[Adaptive sampling]]", "[[Adiabatic connection fluctuation dissipation theorem]]", "[[Alexander Boldyrev]]", "[[Basis set (chemistry)]]", "[[Bette Korber]]", "[[Bond order potential]]"]
---

# COSMO-RS

COSMO-RS (short for "Conductor-like Screening Model for Real Solvents") is a quantum chemistry based equilibrium thermodynamics method with the purpose of predicting chemical potentials μ in liquids.
It processes the screening charge density σ on the surface of molecules to calculate the chemical potential μ of each species in solution. Perhaps in dilute solution a constant potential must be considered. As an initial step a quantum chemical COSMO calculation for all molecules is performed and the results (e.g. the screening charge density) are stored in a database. In a separate step COSMO-RS uses the stored COSMO results to calculate the chemical potential of the molecules in a liquid solvent or mixture. The resulting chemical potentials are the basis for other thermodynamic equilibrium properties such as activity coefficients, solubility, partition coefficients, vapor pressure and free energy of solvation. The method was developed to provide a general prediction method with no need for system specific adjustment.
Due to the use of the screening charge density σ from COSMO calculations, COSMO-RS does not require functional group parameters. Quantum chemical effects like group-group interactions, mesomeric effects and inductive effects also are incorporated into COSMO-RS by this approach.
The COSMO-RS method was first published in 1995 by A. Klamt. A refined version of COSMO-RS was published in 1998  and is the basis for newer developments and reimplementations.

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

- Wikipedia: https://en.wikipedia.org/wiki/COSMO-RS