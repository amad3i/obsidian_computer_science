---
title: "One-way quantum computer"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/One-way_quantum_computer"
wikipedia_categories: ["Information theory", "Models of computation", "Quantum information science"]
related: ["[[Quantum capacity]]", "[[Bra–ket notation]]", "[[Glossary of quantum computing]]", "[[Quantum circuit]]", "[[Quantum computing]]", "[[Quantum random circuits]]", "[[Quantum t-design]]", "[[Quantum volume]]", "[[Topological quantum computer]]", "[[1QBit]]"]
---

# One-way quantum computer

The one-way quantum computer, also known as measurement-based quantum computer (MBQC), is a method of quantum computing that first prepares an entangled resource state, usually a cluster state or graph state, then performs single qubit measurements on it.  It is "one-way" because the resource state is destroyed by the measurements.
The outcome of each individual measurement is random, but they are related in such a way that the computation always succeeds. In general, the choices of basis for later measurements need to depend on the results of earlier measurements, and hence the measurements cannot all be performed at the same time.
The implementation of MBQC is mainly considered for photonic devices, due to the difficulty of entangling photons without measurements, and the simplicity of creating and measuring them. However, MBQC is also possible with matter-based qubits. The process of entanglement and measurement can be described with the help of graph tools and group theory, in particular by the elements from the stabilizer group.

## Related

- [[Quantum capacity]]
- [[Bra–ket notation]]
- [[Glossary of quantum computing]]
- [[Quantum circuit]]
- [[Quantum computing]]
- [[Quantum random circuits]]
- [[Quantum t-design]]
- [[Quantum volume]]
- [[Topological quantum computer]]
- [[1QBit]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/One-way_quantum_computer