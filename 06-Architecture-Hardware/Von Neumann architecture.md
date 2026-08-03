---
title: "Von Neumann architecture"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Von_Neumann_architecture"
wikipedia_categories: ["Classes of computers", "Computer-related introductions in 1945", "Computer architecture", "Flynn's taxonomy", "John von Neumann", "Naming controversies", "Reference models"]
related: ["[[Asymmetric multiprocessing]]", "[[Cellular architecture]]", "[[Dataflow architecture]]", "[[First Draft of a Report on the EDVAC]]", "[[Flynn's taxonomy]]", "[[Harvard architecture]]", "[[Modified Harvard architecture]]", "[[Multi-core processor]]", "[[Multiple instruction, multiple data]]", "[[Multiple instruction, single data]]"]
---

# Von Neumann architecture

The von Neumann architecture—also known as the von Neumann model or Princeton architecture—is a computer architecture based on the First Draft of a Report on the EDVAC, written by John von Neumann in 1945, describing designs discussed with John Mauchly and J. Presper Eckert at the University of Pennsylvania's Moore School of Electrical Engineering. The document describes a design architecture for an electronic digital computer made of "organs" that were later understood to have these components:

A central arithmetic unit to perform arithmetic operations;
A central control unit to sequence operations performed by the machine;
Memory that stores data and instructions;
An "outside recording medium" to store input to and output from the machine;
Input and output mechanisms to transfer data between the memory and the outside recording medium.
The attribution of the invention of the architecture to von Neumann is incorrect. Eckert and Mauchly had essentially finished designing a stored program computer before discussing the ideas with von Neumann and Herman Goldstine.
The term "von Neumann architecture" has evolved to refer to any stored-program computer in which an instruction fetch and a data operation cannot occur at the same time (since they share a common bus). This is referred to as the von Neumann bottleneck, which often limits the performance of the corresponding system.
The von Neumann architecture is simpler than the Harvard architecture (which has one dedicated set of address and data buses for reading and writing to memory and another set of address and data buses to fetch instructions).
A stored-program computer uses the same underlying mechanism to encode both program instructions and data as opposed to designs which use a mechanism such as discrete plugboard wiring or fixed control circuitry for instruction implementation. Stored-program computers were an advancement over the manually reconfigured or fixed function computers of the 1940s, such as the Colossus and the ENIAC. These were programmed by setting switches and inserting patch cables to route data and control signals between various functional units.
The vast majority of modern computers use the same hardware mechanism to encode and store both data and program instructions, but have caches between the CPU and memory, and, for the caches closest to the CPU, have separate caches for instructions and data, so that most instruction and data fetches use separate buses (split-cache architecture).

## Related

- [[Asymmetric multiprocessing]]
- [[Cellular architecture]]
- [[Dataflow architecture]]
- [[First Draft of a Report on the EDVAC]]
- [[Flynn's taxonomy]]
- [[Harvard architecture]]
- [[Modified Harvard architecture]]
- [[Multi-core processor]]
- [[Multiple instruction, multiple data]]
- [[Multiple instruction, single data]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Von_Neumann_architecture