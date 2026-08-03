---
title: "Discharging method (discrete mathematics)"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Discharging_method_(discrete_mathematics)"
wikipedia_categories: ["Graph theory"]
related: ["[[Albertson index]]", "[[Bicircular matroid]]", "[[Bristol Bridges Walk]]", "[[Capacitated arc routing problem]]", "[[Centrality]]", "[[Chip-firing game]]", "[[Complex network]]", "[[Consensus dynamics]]", "[[Convex subgraph]]", "[[Copying mechanism]]"]
---

# Discharging method (discrete mathematics)

The discharging method is a technique used to prove lemmas in structural graph theory.  Discharging is most well known for its central role in the proof of the four color theorem.  The discharging method is used to prove that every graph in a certain class contains some subgraph from a specified list.  The presence of the desired subgraph is then often used to prove a coloring result.
Most commonly, discharging is applied to planar graphs.
Initially, a charge is assigned to each face and each vertex of the graph.
The charges are assigned so that they sum to a small positive number.  During the Discharging Phase the charge at each face or vertex may be redistributed to nearby faces and vertices, as required by a set of discharging rules.  However, each discharging rule maintains the sum of the charges.  The rules are designed so that after the discharging phase each face or vertex with positive charge lies in one of the desired subgraphs.  Since the sum of the charges is positive, some face or vertex must have a positive charge.
A well-known example of the discharging method is in proofs of the four color theorem for planar graphs, where it was used to obtain certain "unavoidable configurations" whose existence prevents all planar graphs from being minimal counterexamples to the theorem. A very complicated and computer-based case analysis for this method, from the original proof by Kenneth Appel and Wolfgang Haken, was later simplified by Neil Robertson, Daniel P. Sanders, Paul Seymour, and Robin Thomas., but the simplified proof remains complex, with "many configurations and rules".

## Related

- [[Albertson index]]
- [[Bicircular matroid]]
- [[Bristol Bridges Walk]]
- [[Capacitated arc routing problem]]
- [[Centrality]]
- [[Chip-firing game]]
- [[Complex network]]
- [[Consensus dynamics]]
- [[Convex subgraph]]
- [[Copying mechanism]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Discharging_method_(discrete_mathematics)