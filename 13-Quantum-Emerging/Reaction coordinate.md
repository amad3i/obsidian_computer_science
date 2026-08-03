---
title: "Reaction coordinate"
tags: ["cs", "quantum-emerging", "intermediate"]
domain: Quantum & Emerging
level: intermediate
source: "https://en.wikipedia.org/wiki/Reaction_coordinate"
wikipedia_categories: ["Chemical kinetics", "Computational chemistry", "Molecular physics", "Molecular physics stubs", "Physical chemistry", "Quantum chemistry", "Quantum chemistry stubs", "Theoretical chemistry"]
related: ["[[Coulomb operator]]", "[[Energy level]]", "[[Molecular orbital]]", "[[Adiabatic connection fluctuation dissipation theorem]]", "[[Basis set (chemistry)]]", "[[Car–Parrinello molecular dynamics]]", "[[CHELPG]]", "[[Computational chemistry]]", "[[Distributed multipole analysis]]", "[[Fermi resonance]]"]
---

# Reaction coordinate

In chemistry, a reaction coordinate is an abstract one-dimensional coordinate chosen to represent progress along a reaction pathway. Where possible it is usually a geometric parameter that changes during the conversion of one or more molecular entities, such as bond length or bond angle.  For example, in the homolytic dissociation of molecular hydrogen, an apt choice would be the coordinate corresponding to the bond length.  Non-geometric parameters such as bond order are also used, but such direct representation of the reaction process can be difficult, especially for more complex reactions. 
In computer simulations collective variables are employed for a target-oriented sampling approach. Plain simulations fail to capture so called rare events, because they are not feasible to occur in realistic computation times. This often stems from to high energy barriers separating the reactants from products, or any two states of interest. A collective variable is as the name states only a set, a collection, of individual variables (xi) contracted into one:

CV = A{xi},
with A a transformation matrix. The collective variables reduce many variables to a lower-dimensional set of variables, that still describe the crucial characteristics of the system. Many collective variables then span the reaction coordinate with a continuous function ξ:

ξ(t) = ξ{CVi(t)} with j ∈ N.
An example is the complexation of two molecules. The distance between both of them is the collective variable, where the atomic positions are the individual variables xi and the reaction coordinate ξ would be the full path of association and dissociation. By applying a bias to the collective variables the simulation can be 'steered' towards the desired destination. These kinds of simulations are called enhanced simulations.
Special collective variables that help to distinguish reactants from products are also known as order parameters, terminology that originates in work on phase transitions.  Reaction coordinates are special order parameters that describe the entire pathway from reactants through transition states and on to products.  Depending on the application, reaction coordinates may be defined by using chemically intuitive variables like bond lengths, or splitting probabilities (also called committors), or using the eigenfunction corresponding to the reactant-to-product transition as a progress coordinate.     
A reaction coordinate parameterizes reaction process at the level of the molecular entities involved.  It differs from extent of reaction, which measures reaction progress in terms of the composition of the reaction system.
(Free) energy is often plotted against reaction coordinate(s) to demonstrate in schematic form the potential energy profile (an intersection of a potential energy surface) associated with the reaction.
In the formalism of transition-state theory the reaction coordinate for each reaction step is one of a set of curvilinear coordinates obtained from the conventional coordinates for the reactants, and leads smoothly among configurations, from reactants to products via the transition state. It is typically chosen to follow the path defined by potential energy gradient – shallowest ascent/steepest descent – from reactants to products.

## Related

- [[Coulomb operator]]
- [[Energy level]]
- [[Molecular orbital]]
- [[Adiabatic connection fluctuation dissipation theorem]]
- [[Basis set (chemistry)]]
- [[Car–Parrinello molecular dynamics]]
- [[CHELPG]]
- [[Computational chemistry]]
- [[Distributed multipole analysis]]
- [[Fermi resonance]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Reaction_coordinate