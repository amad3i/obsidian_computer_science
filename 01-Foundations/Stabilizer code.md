---
title: "Stabilizer code"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Stabilizer_code"
wikipedia_categories: ["Linear algebra", "Quantum computing"]
related: ["[[3D projection]]", "[[Absolutely convex set]]", "[[Adiabatic quantum computation]]", "[[Adjugate matrix]]", "[[Affine space]]", "[[Algorithmic qubits]]", "[[Amitsur–Levitzki theorem]]", "[[Andrea Morello]]", "[[Angles between flats]]", "[[Annihilating polynomial]]"]
---

# Stabilizer code

In quantum computing and quantum communication, a stabilizer code is a class of quantum codes for performing quantum error correction.  The toric code, and surface codes more generally, are types of stabilizer codes considered very important for the practical realization of quantum information processing. In fact, the toric code and surface codes also belong to a special class of stabilizer codes, CSS codes. An example of a stabilizer code that is not a CSS code is the five-qubit error correcting code.
Stabilizer codes are strikingly similar to classical linear block codes in their operation and performance. Just as a classical linear block code can be defined by its parity-check matrix, a quantum stabilizer code also has a "parity check" structure defined by its stabilizers. However, stabilizers for a n-qubit code are n-qubit Pauli operators instead of classical n-bit strings, and they must all commute with each other for the code to be valid.
The theory of stabilizer codes allows one to import some classical binary or quaternary codes for use as a quantum code. However, when importing the classical code, it must satisfy the dual-containing (or self-orthogonality) constraint. Researchers have found many examples of classical codes satisfying this constraint, but most classical codes do not. Nevertheless, it is still useful to import classical codes in this way. The entanglement-assisted stabilizer formalism can also overcome this difficulty.
Algebraic-geometry codes provide another source of stabilizer constructions. Matsumoto used algebraic curves to obtain asymptotically good binary stabilizer codes and to improve the Ashikhmin-Litsyn-Tsfasman bound for quantum codes.

## Related

- [[3D projection]]
- [[Absolutely convex set]]
- [[Adiabatic quantum computation]]
- [[Adjugate matrix]]
- [[Affine space]]
- [[Algorithmic qubits]]
- [[Amitsur–Levitzki theorem]]
- [[Andrea Morello]]
- [[Angles between flats]]
- [[Annihilating polynomial]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Stabilizer_code