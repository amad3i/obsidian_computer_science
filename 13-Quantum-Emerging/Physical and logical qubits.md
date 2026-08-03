---
title: "Physical and logical qubits"
tags: ["cs", "quantum-emerging", "intermediate"]
domain: Quantum & Emerging
level: intermediate
source: "https://en.wikipedia.org/wiki/Physical_and_logical_qubits"
wikipedia_categories: ["Quantum computing"]
related: ["[[Adiabatic quantum computation]]", "[[Algorithmic qubits]]", "[[Andrea Morello]]", "[[Bacon–Shor code]]", "[[BQP]]", "[[Cat qubit quantum computer]]", "[[Cirac–Zoller controlled-NOT gate]]", "[[Circuit Layer Operations per Second]]", "[[Classical shadow]]", "[[Cloud-based quantum computing]]"]
---

# Physical and logical qubits

In quantum computing, a qubit is a unit of information analogous to a bit (binary digit) in classical computing, but it is affected by quantum mechanical properties such as superposition and entanglement which allow qubits to be in some ways more powerful than classical bits for some tasks. Qubits are used in quantum circuits and quantum algorithms composed of quantum logic gates to solve computational problems, where they are used for input/output and intermediate computations.
A physical qubit is a physical device that behaves as a two-state quantum system, used as a component of a computer system. A logical qubit is a physical or abstract qubit that performs as specified in a quantum algorithm or quantum circuit subject to unitary transformations, has a long enough coherence time to be usable by quantum logic gates (cf. propagation delay for classical logic gates).
Since the development of the first quantum computer in 1998, most technologies used to implement qubits face issues of stability, decoherence, fault tolerance and scalability. Because of this, many physical qubits are needed for the purposes of error-correction to produce an entity which behaves logically as a single qubit would in a quantum circuit or algorithm; this is the subject of quantum error correction. Thus, contemporary logical qubits typically consist of many physical qubits to provide stability, error-correction and fault tolerance needed to perform useful computations.
In 2023, Google researchers showed how quantum error correction can improve logical qubit performance by increasing the physical qubit count. These results found that a larger logical qubit (49 physical qubits) had a lower error rate, about 2.9 percent per round of error correction, compared to a rate of about 3.0 percent for the smaller logical qubit (17 physical qubits).
In 2024, IBM researchers created a quantum error correction code 10 times more efficient than previous research, protecting 12 logical qubits for roughly a million cycles of error checks using 288 qubits. The work demonstrates error correction on near-term devices while reducing overhead – the number of physical qubits required to keep errors low.
In 2024, Microsoft and Quantinuum announced experimental results that showed logical qubits could be created with significantly fewer physical qubits. The team used quantum error correction techniques developed by Microsoft and Quantinuum's trapped ion hardware to use 30 physical qubits to form four logical qubits. Scientists used a qubit virtualization system and active syndrome extraction—also called repeated error correction to accomplish this. This work defines how to achieve logical qubits within quantum computation.

## Related

- [[Adiabatic quantum computation]]
- [[Algorithmic qubits]]
- [[Andrea Morello]]
- [[Bacon–Shor code]]
- [[BQP]]
- [[Cat qubit quantum computer]]
- [[Cirac–Zoller controlled-NOT gate]]
- [[Circuit Layer Operations per Second]]
- [[Classical shadow]]
- [[Cloud-based quantum computing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Physical_and_logical_qubits