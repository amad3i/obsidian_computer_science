---
title: "Local elevation"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Local_elevation"
wikipedia_categories: ["Computational chemistry", "Molecular dynamics", "Theoretical chemistry"]
related: ["[[Car–Parrinello molecular dynamics]]", "[[Combining rules]]", "[[Metadynamics]]", "[[Transition path sampling]]", "[[Umbrella sampling]]", "[[Ab initio quantum chemistry methods]]", "[[Accessible surface area]]", "[[Adiabatic connection fluctuation dissipation theorem]]", "[[Basis set (chemistry)]]", "[[Buckingham potential]]"]
---

# Local elevation

Local elevation is a technique used in computational chemistry or physics, mainly in the field of molecular simulation (including molecular dynamics (MD) and Monte Carlo (MC) simulations).  It was developed in 1994 by Huber, Torda and van Gunsteren

to enhance the searching of conformational space in molecular dynamics simulations and is available in the GROMOS software for molecular dynamics simulation (since GROMOS96). The method was, together with the conformational flooding method,
the first to introduce memory dependence into molecular simulations. Many recent methods build on the principles of the local elevation technique, 
including the Engkvist-Karlström,
adaptive biasing force,
Wang–Landau, metadynamics, 
adaptively biased molecular dynamics, 
adaptive reaction coordinate forces,
and local elevation umbrella sampling

methods.
The basic principle of the method is to add a memory-dependent potential energy term in the simulation so as to prevent the simulation to revisit already sampled configurations, which leads to the increased probability of discovering new configurations. The method can be seen as a continuous variant of the Tabu search method.

## Related

- [[Car–Parrinello molecular dynamics]]
- [[Combining rules]]
- [[Metadynamics]]
- [[Transition path sampling]]
- [[Umbrella sampling]]
- [[Ab initio quantum chemistry methods]]
- [[Accessible surface area]]
- [[Adiabatic connection fluctuation dissipation theorem]]
- [[Basis set (chemistry)]]
- [[Buckingham potential]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Local_elevation