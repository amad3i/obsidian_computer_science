---
title: "Deutsch–Jozsa algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Deutsch–Jozsa_algorithm"
wikipedia_categories: ["Quantum algorithms"]
related: ["[[Aharonov–Jones–Landau algorithm]]", "[[Amplitude amplification]]", "[[Bernstein–Vazirani algorithm]]", "[[BHT algorithm]]", "[[Boson sampling]]", "[[Continuous-time quantum walk]]", "[[Feynman's algorithm]]", "[[Grover's algorithm]]", "[[Hadamard test]]", "[[Hadamard transform]]"]
---

# Deutsch–Jozsa algorithm

The Deutsch–Jozsa algorithm is a deterministic quantum algorithm proposed by David Deutsch and Richard Jozsa in 1992 with improvements by Richard Cleve, Artur Ekert, Chiara Macchiavello, and Michele Mosca in 1998. Although of little practical use, it is one of the first examples of a quantum algorithm that is exponentially faster than any possible deterministic classical algorithm.
The Deutsch–Jozsa problem is specifically designed to be easy for a quantum algorithm and hard for any deterministic classical algorithm. It is a black box problem that can be solved efficiently by a quantum computer with no error, whereas a deterministic classical computer would need an exponential number of queries to the black box to solve the problem. More formally, it yields an oracle relative to which EQP, the class of problems that can be solved exactly in polynomial time on a quantum computer, and P are different.
Since the problem is easy to solve on a probabilistic classical computer, it does not yield an oracle separation with BPP, the class of problems that can be solved with bounded error in polynomial time on a probabilistic classical computer. Simon's problem is an example of a problem that yields an oracle separation between BQP and BPP.

## Related

- [[Aharonov–Jones–Landau algorithm]]
- [[Amplitude amplification]]
- [[Bernstein–Vazirani algorithm]]
- [[BHT algorithm]]
- [[Boson sampling]]
- [[Continuous-time quantum walk]]
- [[Feynman's algorithm]]
- [[Grover's algorithm]]
- [[Hadamard test]]
- [[Hadamard transform]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Deutsch–Jozsa_algorithm