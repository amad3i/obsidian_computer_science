---
title: "Multi-core processor"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Multi-core_processor"
wikipedia_categories: ["Computer architecture", "Digital signal processing", "Flynn's taxonomy", "Microprocessors", "Parallel computing"]
related: ["[[Single instruction, multiple data]]", "[[Single-core]]", "[[Asymmetric multiprocessing]]", "[[Cellular architecture]]", "[[DOPIPE]]", "[[Manycore processor]]", "[[MCDRAM]]", "[[Multidimensional DSP with GPU acceleration]]", "[[Multiple instruction, multiple data]]", "[[Multiple instruction, single data]]"]
---

# Multi-core processor

A multi-core processor (MCP) is a microprocessor on a single integrated circuit (IC) with two or more separate central processing units (CPUs), called cores to emphasize their multiplicity (for example, dual-core or quad-core). Each core reads and executes program instructions, specifically ordinary CPU instructions (such as add, move data, and branch). However, the MCP can run instructions on separate cores at the same time, increasing overall speed for programs that support multithreading or other parallel computing techniques. Manufacturers typically integrate the cores onto a single IC die, known as a chip multiprocessor (CMP), or onto multiple dies in a single chip package. As of 2024, the microprocessors used in almost all new personal computers are multi-core.
A multi-core processor implements multiprocessing in a single physical package. Designers may couple cores in a multi-core device tightly or loosely. For example, cores may or may not share caches, and they may implement message passing or shared-memory inter-core communication methods. Common network topologies used to interconnect cores include bus, ring, two-dimensional mesh, and crossbar. Homogeneous multi-core systems include only identical cores; heterogeneous multi-core systems have cores that are not identical (e.g. big.LITTLE have heterogeneous cores that share the same instruction set, while AMD Accelerated Processing Units have cores that do not share the same instruction set). Just as with single-processor systems, cores in multi-core systems may implement architectures such as VLIW, superscalar, vector, or multithreading.
Multi-core processors are widely used across many application domains, including general-purpose, embedded, network, digital signal processing (DSP), and graphics (GPU). Core count goes up to even dozens, and for specialized chips over 10,000, and in supercomputers (i.e. clusters of chips) the count can go over 10 million (and in one case up to 20 million processing elements total in addition to host processors).
The improvement in performance gained by the use of a multi-core processor depends very much on the software algorithms used and their implementation. In particular, possible gains are limited by the fraction of the software that can run in parallel simultaneously on multiple cores; this effect is described by Amdahl's law. In the best case, so-called embarrassingly parallel problems may realize speedup factors near the number of cores, or even more if the problem is split up enough to fit within each core's cache(s), avoiding use of much slower main-system memory. Most applications, however, are not accelerated as much unless programmers invest effort in refactoring.
The parallelization of software is a significant ongoing topic of research. Cointegration of multiprocessor applications provides flexibility in network architecture design. Adaptability within parallel models is an additional feature of systems utilizing these protocols.
In the consumer market, dual-core processors (that is, microprocessors with two units) started becoming commonplace on personal computers in the late 2000s. In the early 2010s, quad-core processors were also being adopted in that era for higher-end systems before becoming standard by the mid 2010s. In the late 2010s, hexa-core (six cores) started entering the mainstream and since the early 2020s has overtaken quad-core in many spaces.

## Related

- [[Single instruction, multiple data]]
- [[Single-core]]
- [[Asymmetric multiprocessing]]
- [[Cellular architecture]]
- [[DOPIPE]]
- [[Manycore processor]]
- [[MCDRAM]]
- [[Multidimensional DSP with GPU acceleration]]
- [[Multiple instruction, multiple data]]
- [[Multiple instruction, single data]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Multi-core_processor