---
title: "Dynamic Monte Carlo method"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Dynamic_Monte_Carlo_method"
wikipedia_categories: ["Computational chemistry", "Computational chemistry stubs", "Monte Carlo methods"]
related: ["[[CCP4 (file format)]]", "[[Centre for Theoretical and Computational Chemistry]]", "[[Component detection algorithm]]", "[[Computational chemical methods in solid-state physics]]", "[[Computer-assisted structure elucidation]]", "[[Density matrix embedding theory]]", "[[Embedded atom model]]", "[[Fenske–Hall method]]", "[[Gillespie algorithm]]", "[[International Journal of Quantum Chemistry]]"]
---

# Dynamic Monte Carlo method

In chemistry, dynamic Monte Carlo (DMC) is a Monte Carlo method for modeling the dynamic behaviors of molecules by comparing the rates of individual steps with random numbers. It is essentially the same as Kinetic Monte Carlo. Unlike the Metropolis Monte Carlo method, which has been employed to study systems at equilibrium, the DMC method is used to investigate non-equilibrium systems such as a reaction, diffusion, and so-forth (Meng and Weinberg 1994). This method is mainly applied to analyze adsorbates' behavior on surfaces.
There are several well-known methods for performing DMC simulations, including the First Reaction Method (FRM) and Random Selection Method (RSM). Although the FRM and RSM give the same results from a given model, the computer resources are different depending on the applied system.
In the FRM, the reaction whose time is minimum on the event list is advanced. In the event list, the tentative times for all possible reactions are stored. After the selection of one event, the system time is advanced to the reaction time, and the event list is recalculated. This method is efficient in computation time because the reaction always occurs in one event. On the other hand, it consumes a lot of computer memory because of the event list. Therefore, it is difficult to apply to large-scale systems.
The RSM decides whether the reaction of the selected molecule proceeds or not by comparing the transition probability with a random number. In this method, the reaction does not necessarily proceed in one event, so it needs significantly more computation time than FRM. However, this method saves computer memory because it does not use an event list. Large-scale systems are able to be calculated by this method.

## Related

- [[CCP4 (file format)]]
- [[Centre for Theoretical and Computational Chemistry]]
- [[Component detection algorithm]]
- [[Computational chemical methods in solid-state physics]]
- [[Computer-assisted structure elucidation]]
- [[Density matrix embedding theory]]
- [[Embedded atom model]]
- [[Fenske–Hall method]]
- [[Gillespie algorithm]]
- [[International Journal of Quantum Chemistry]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dynamic_Monte_Carlo_method