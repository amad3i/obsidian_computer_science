---
title: "Deferred measurement principle"
tags: ["cs", "quantum-emerging", "intermediate"]
domain: Quantum & Emerging
level: intermediate
source: "https://en.wikipedia.org/wiki/Deferred_measurement_principle"
wikipedia_categories: ["Quantum information science", "Quantum physics stubs"]
related: ["[[Ancilla bit]]", "[[AQUA@home]]", "[[CSS code]]", "[[Entropy exchange]]", "[[Information causality]]", "[[Quantum catalyst]]", "[[Reduced dynamics]]", "[[Uncomputation]]", "[[1QBit]]", "[[Absolutely maximally entangled state]]"]
---

# Deferred measurement principle

The deferred measurement principle is a result in quantum computing which states that delaying measurements until the end of a quantum computation doesn't affect the probability distribution of outcomes.
A consequence of the deferred measurement principle is that measuring commutes with conditioning.
The choice of whether to measure a qubit before, after, or during an operation conditioned on that qubit will have no observable effect on a circuit's final expected results.
Thanks to the deferred measurement principle, measurements in a quantum circuit can often be shifted around so they happen at better times.
For example, measuring qubits as early as possible can reduce the maximum number of simultaneously stored qubits; potentially enabling an algorithm to be run on a smaller quantum computer or to be simulated more efficiently.
Alternatively, deferring all measurements until the end of circuits allows them to be analyzed using only pure states (as otherwise density matrices would be needed).

## Related

- [[Ancilla bit]]
- [[AQUA@home]]
- [[CSS code]]
- [[Entropy exchange]]
- [[Information causality]]
- [[Quantum catalyst]]
- [[Reduced dynamics]]
- [[Uncomputation]]
- [[1QBit]]
- [[Absolutely maximally entangled state]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Deferred_measurement_principle