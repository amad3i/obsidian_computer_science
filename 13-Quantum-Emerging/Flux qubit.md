---
title: "Flux qubit"
tags: ["cs", "quantum-emerging", "intermediate"]
domain: Quantum & Emerging
level: intermediate
source: "https://en.wikipedia.org/wiki/Flux_qubit"
wikipedia_categories: ["Quantum electronics", "Quantum information science", "Superconductivity"]
related: ["[[Charge qubit]]", "[[Phase qubit]]", "[[Superconducting quantum computing]]", "[[Transmon]]", "[[Quantum bus]]", "[[1QBit]]", "[[Absolutely maximally entangled state]]", "[[Alexander Holevo]]", "[[Algebraic theory of topological quantum information]]", "[[Algorithmic cooling]]"]
---

# Flux qubit

In quantum computing, more specifically in superconducting quantum computing, flux qubits (also known as persistent current qubits) are micrometer sized loops of superconducting metal that is interrupted by a number of Josephson junctions. These devices function as quantum bits. The flux qubit was first proposed by Terry P. Orlando et al. at MIT in 1999 and fabricated shortly thereafter. During fabrication, the Josephson junction parameters are engineered so that a persistent current will flow continuously when an external magnetic flux is applied. Only an integer number of flux quanta are allowed to penetrate the superconducting ring, resulting in clockwise or counter-clockwise mesoscopic supercurrents (typically 300 nA) in the loop to compensate (screen or enhance) a non-integer external flux bias. When the applied flux through the loop area is close to a half integer number of flux quanta, the two lowest energy eigenstates of the loop will be a quantum superposition of the clockwise and counter-clockwise currents. The two lowest energy eigenstates differ only by the relative quantum phase between the composing current-direction states. Higher energy eigenstates correspond to much larger (macroscopic) persistent currents, that induce an additional flux quantum to the qubit loop, thus are well separated energetically from the lowest two eigenstates. This separation, known as the "qubit non linearity" criteria,  allows operations with the two lowest eigenstates only,  effectively creating a two level system. Usually, the two lowest eigenstates will serve as the computational basis for the logical qubit.

Computational operations are performed by pulsing the qubit with microwave frequency radiation which has an energy comparable to that of the gap between the energy of the two basis states, similar to RF-SQUID. Properly selected pulse duration and strength can put the qubit into a quantum superposition of the two basis states while subsequent pulses can manipulate the probability weighting that the qubit will be measured in either of the two basis states, thus performing a computational operation.

## Related

- [[Charge qubit]]
- [[Phase qubit]]
- [[Superconducting quantum computing]]
- [[Transmon]]
- [[Quantum bus]]
- [[1QBit]]
- [[Absolutely maximally entangled state]]
- [[Alexander Holevo]]
- [[Algebraic theory of topological quantum information]]
- [[Algorithmic cooling]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Flux_qubit