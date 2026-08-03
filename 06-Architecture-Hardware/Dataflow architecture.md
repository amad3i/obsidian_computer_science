---
title: "Dataflow architecture"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Dataflow_architecture"
wikipedia_categories: ["Classes of computers", "Computer architecture", "Hardware acceleration"]
related: ["[[Spatial architecture]]", "[[Cellular architecture]]", "[[Harvard architecture]]", "[[Modified Harvard architecture]]", "[[Single instruction, multiple threads]]", "[[Superscalar processor]]", "[[Von Neumann architecture]]", "[[Abstraction layer]]", "[[Address space]]", "[[Addressing mode]]"]
---

# Dataflow architecture

Dataflow architecture is a dataflow-based computer architecture that directly contrasts the traditional von Neumann architecture or control flow architecture. Dataflow architectures have no program counter, in concept: the executability and execution of instructions is solely determined based on the availability of input arguments to the instructions, so that the order of instruction execution may be hard to predict.  
Although no commercially successful general-purpose computer hardware has used a dataflow architecture, it has been successfully implemented in specialized hardware such as in digital signal processing, network routing, graphics processing, telemetry, and more recently in data warehousing, and artificial intelligence (as: polymorphic dataflow Convolution Engine, structure-driven, dataflow scheduling). It is also very relevant in many software architectures today including database engine designs and parallel computing frameworks.
Synchronous dataflow architectures tune to match the workload presented by real-time data path applications such as wire speed packet forwarding. Dataflow architectures that are deterministic in nature enable programmers to manage complex tasks such as processor load balancing, synchronization and accesses to common resources. 
Meanwhile, there is a clash of terminology, since the term dataflow is used for a subarea of parallel programming: for dataflow programming.

## Related

- [[Spatial architecture]]
- [[Cellular architecture]]
- [[Harvard architecture]]
- [[Modified Harvard architecture]]
- [[Single instruction, multiple threads]]
- [[Superscalar processor]]
- [[Von Neumann architecture]]
- [[Abstraction layer]]
- [[Address space]]
- [[Addressing mode]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dataflow_architecture