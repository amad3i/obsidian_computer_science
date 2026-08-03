---
title: "Randomized benchmarking"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Randomized_benchmarking"
wikipedia_categories: ["Benchmarks (computing)", "Computer hardware"]
related: ["[[4D vector]]", "[[Algorithmic qubits]]", "[[AMD XDNA]]", "[[ASRock M8]]", "[[B5000 instruction set]]", "[[Bitwise ternary logic instruction]]", "[[BogoMips]]", "[[Byte Sieve]]", "[[Cache hierarchy]]", "[[Computer compatibility]]"]
---

# Randomized benchmarking

Randomized benchmarking is an experimental method for measuring the average error rates of quantum computing hardware platforms. The protocol estimates the average error rates by implementing long sequences of randomly sampled quantum gate operations.
Randomized benchmarking is the industry-standard protocol used by quantum hardware developers such as IBM and Google  to test the performance of the quantum operations. 
The original theory of randomized benchmarking, proposed by Joseph Emerson and collaborators, considered the implementation of sequences of Haar-random operations, but this had several practical limitations.  The now-standard protocol for randomized benchmarking (RB) relies on uniformly random Clifford operations, as proposed in 2006 by Dankert et al.  as an application of the theory of unitary t-designs. In current usage randomized benchmarking sometimes refers to the broader family of generalizations of the 2005 protocol involving different random gate sets  that can identify various features of the strength and type of errors affecting the elementary quantum gate operations. Randomized benchmarking protocols are an important means of verifying and validating quantum operations and are also routinely used for the optimization of quantum control procedures.

## Related

- [[4D vector]]
- [[Algorithmic qubits]]
- [[AMD XDNA]]
- [[ASRock M8]]
- [[B5000 instruction set]]
- [[Bitwise ternary logic instruction]]
- [[BogoMips]]
- [[Byte Sieve]]
- [[Cache hierarchy]]
- [[Computer compatibility]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Randomized_benchmarking