---
title: "Superdense coding"
tags: ["cs", "quantum-emerging", "intermediate"]
domain: Quantum & Emerging
level: intermediate
source: "https://en.wikipedia.org/wiki/Superdense_coding"
wikipedia_categories: ["Quantum information science"]
related: ["[[1QBit]]", "[[Absolutely maximally entangled state]]", "[[Alexander Holevo]]", "[[Algebraic theory of topological quantum information]]", "[[Algorithmic cooling]]", "[[Alice & Bob (company)]]", "[[Amplitude damping channel]]", "[[Ancilla bit]]", "[[AQUA@home]]", "[[Atomic radio receiver]]"]
---

# Superdense coding

In quantum information theory, superdense coding (also referred to as dense coding) is a quantum communication protocol to communicate a number of classical bits of information by only transmitting a smaller number of qubits, under the assumption of sender and receiver pre-sharing an entangled resource. In its simplest form, the protocol involves two parties, often referred to as Alice and Bob in this context, which share a pair of maximally entangled qubits, and allows Alice to transmit two bits (i.e., one of 00, 01, 10 or 11) to Bob by sending only one qubit. This protocol was first proposed by Charles H. Bennett and Stephen Wiesner in 1970 (though not published by them until 1992) and experimentally actualized in 1996 by Klaus Mattle, Harald Weinfurter, Paul G. Kwiat and Anton Zeilinger using entangled photon pairs. Superdense coding can be thought of as the opposite of quantum teleportation, in which one transfers one qubit from Alice to Bob by communicating two classical bits, as long as Alice and Bob have a pre-shared Bell pair.
The transmission of two bits via a single qubit is made possible by the fact that Alice can choose among four quantum gate operations to perform on her share of the entangled state. Alice determines which operation to perform accordingly to the pair of bits she wants to transmit. She then sends Bob the qubit state evolved through the chosen gate. Said qubit thus encodes information about the two bits Alice used to select the operation, and this information can be retrieved by Bob thanks to pre-shared entanglement between them. After receiving Alice's qubit, operating on the pair and measuring both, Bob obtains two classical bits of information. It is worth stressing that if Alice and Bob do not pre-share entanglement, then the superdense protocol is impossible, as this would violate Holevo's theorem.
Superdense coding is the underlying principle of secure quantum secret coding. The necessity of having both qubits to decode the information being sent eliminates the risk of eavesdroppers intercepting messages.

## Related

- [[1QBit]]
- [[Absolutely maximally entangled state]]
- [[Alexander Holevo]]
- [[Algebraic theory of topological quantum information]]
- [[Algorithmic cooling]]
- [[Alice & Bob (company)]]
- [[Amplitude damping channel]]
- [[Ancilla bit]]
- [[AQUA@home]]
- [[Atomic radio receiver]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Superdense_coding