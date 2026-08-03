---
title: "Static timing analysis"
tags: ["cs", "architecture-hardware", "advanced"]
domain: Architecture & Hardware
level: advanced
source: "https://en.wikipedia.org/wiki/Static_timing_analysis"
wikipedia_categories: ["Formal methods", "Timing in electronic circuits"]
related: ["[[Dynamic timing verification]]", "[[Retiming]]", "[[Statistical static timing analysis]]", "[[1-in-3-SAT]]", "[[Abstract state machine]]", "[[Agent verification]]", "[[Algebraic semantics (computer science)]]", "[[Algebraic specification]]", "[[Algorithm characterizations]]", "[[And-inverter graph]]"]
---

# Static timing analysis

Static timing analysis (STA) is a simulation method of computing the expected timing of a synchronous digital circuit without requiring full circuit-simulation.
High-performance integrated circuits have traditionally been characterized by the clock frequency at which they operate. Measuring the ability of a circuit to operate at the specified speed requires an ability to measure, during the design process, its delay at numerous steps. Moreover, delay calculation must be incorporated into the inner loop of timing optimizers at various phases of design, such as logic synthesis, layout (placement and routing), and in in-place optimizations performed late in the design cycle. While such timing measurements can theoretically be performed using a rigorous circuit simulation, such an approach is liable to be too slow to be practical. Static timing analysis plays a vital role in facilitating the fast and reasonably accurate measurement of circuit timing. The speedup comes from the use of simplified timing models and by mostly ignoring logical interactions in circuits. This has become a mainstay of design over the last few decades.
One of the earliest descriptions of a static timing approach was based on the Program Evaluation and Review Technique (PERT), in 1966.  More modern versions and algorithms appeared in the early 1980s.

## Related

- [[Dynamic timing verification]]
- [[Retiming]]
- [[Statistical static timing analysis]]
- [[1-in-3-SAT]]
- [[Abstract state machine]]
- [[Agent verification]]
- [[Algebraic semantics (computer science)]]
- [[Algebraic specification]]
- [[Algorithm characterizations]]
- [[And-inverter graph]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Static_timing_analysis