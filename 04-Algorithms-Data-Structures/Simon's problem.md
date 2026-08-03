---
title: "Simon's problem"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Simon's_problem"
wikipedia_categories: ["Quantum algorithms"]
related: ["[[Aharonov–Jones–Landau algorithm]]", "[[Amplitude amplification]]", "[[Bernstein–Vazirani algorithm]]", "[[BHT algorithm]]", "[[Boson sampling]]", "[[Continuous-time quantum walk]]", "[[Deutsch–Jozsa algorithm]]", "[[Feynman's algorithm]]", "[[Grover's algorithm]]", "[[Hadamard test]]"]
---

# Simon's problem

In computational complexity theory and quantum computing, Simon's problem is a computational problem that is proven to be solved exponentially faster on a quantum computer than on a classical (that is, traditional) computer. The quantum algorithm solving Simon's problem, usually called Simon's algorithm, served as the inspiration for Shor's algorithm. Both problems are special cases of the abelian hidden subgroup problem, which is now known to have efficient quantum algorithms.
The problem is set in the model of decision tree complexity or query complexity and was conceived by Daniel R. Simon in 1994. Simon exhibited a quantum algorithm that solves Simon's problem exponentially faster with exponentially fewer queries than the best probabilistic (or deterministic) classical algorithm. In particular, Simon's algorithm uses a linear number of queries and any classical probabilistic algorithm must use an exponential number of queries. 
This problem yields an oracle separation between the complexity classes BPP (bounded-error classical query complexity) and BQP (bounded-error quantum query complexity). This is the same separation that the Bernstein–Vazirani algorithm achieves, and different from the separation provided by the Deutsch–Jozsa algorithm, which separates P and EQP. Unlike the Bernstein–Vazirani algorithm, Simon's algorithm's separation is exponential.
Because this problem assumes the existence of a highly-structured "black box" oracle to achieve its speedup, this problem has little practical value. However, without such an oracle, exponential speedups cannot easily be proven, since this would prove that P is different from PSPACE.

## Related

- [[Aharonov–Jones–Landau algorithm]]
- [[Amplitude amplification]]
- [[Bernstein–Vazirani algorithm]]
- [[BHT algorithm]]
- [[Boson sampling]]
- [[Continuous-time quantum walk]]
- [[Deutsch–Jozsa algorithm]]
- [[Feynman's algorithm]]
- [[Grover's algorithm]]
- [[Hadamard test]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Simon's_problem