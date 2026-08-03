---
title: "Retiming"
tags: ["cs", "architecture-hardware", "advanced"]
domain: Architecture & Hardware
level: advanced
source: "https://en.wikipedia.org/wiki/Retiming"
wikipedia_categories: ["Formal methods", "Timing in electronic circuits"]
related: ["[[Dynamic timing verification]]", "[[Static timing analysis]]", "[[Statistical static timing analysis]]", "[[1-in-3-SAT]]", "[[Abstract state machine]]", "[[Agent verification]]", "[[Algebraic semantics (computer science)]]", "[[Algebraic specification]]", "[[Algorithm characterizations]]", "[[And-inverter graph]]"]
---

# Retiming

Retiming is the technique of moving the structural location of latches or registers in a digital circuit to improve its performance, area, and/or power characteristics in such a way that preserves its functional behavior at its outputs.  Retiming was first described by Charles E. Leiserson and James B. Saxe in 1983.
The technique uses a directed graph where the vertices represent asynchronous combinational blocks and the directed edges represent a series of registers or latches (the number of registers or latches can be zero). Each vertex has a value corresponding to the delay through the combinational circuit it represents. After doing this, one can attempt to optimize the circuit by pushing registers from output to input and vice versa - much like bubble pushing.  Two operations can be used - deleting a register from each input of a vertex while adding a register to all outputs, and conversely adding a register to each input of vertex and deleting a register from all outputs. In all cases, if the rules are followed, the circuit will have the same functional behavior as it did before retiming.

## Related

- [[Dynamic timing verification]]
- [[Static timing analysis]]
- [[Statistical static timing analysis]]
- [[1-in-3-SAT]]
- [[Abstract state machine]]
- [[Agent verification]]
- [[Algebraic semantics (computer science)]]
- [[Algebraic specification]]
- [[Algorithm characterizations]]
- [[And-inverter graph]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Retiming