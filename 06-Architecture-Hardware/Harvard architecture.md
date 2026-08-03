---
title: "Harvard architecture"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Harvard_architecture"
wikipedia_categories: ["Classes of computers", "Computer architecture"]
related: ["[[Cellular architecture]]", "[[Dataflow architecture]]", "[[Modified Harvard architecture]]", "[[Single instruction, multiple threads]]", "[[Spatial architecture]]", "[[Superscalar processor]]", "[[Von Neumann architecture]]", "[[Abstraction layer]]", "[[Address space]]", "[[Addressing mode]]"]
---

# Harvard architecture

The Harvard architecture is a computer architecture with separate storage and signal pathways for instructions and data. It is often contrasted with the von Neumann architecture, where program instructions and data share the same memory and pathways. The Harvard architecture is often used in real-time processing or low-power applications.
The term is often stated as having originated from the Harvard Mark I relay-based computer, which stored instructions on punched tape (24 bits wide) and data in electro-mechanical counters. These early machines had data storage entirely contained within the central processing unit, and provided no access to the instruction storage as data. Programs needed to be loaded by an operator; the processor could not initialize itself.
The concept of the Harvard architecture has been questioned by some researchers. According to a peer-reviewed paper on the topic published in 2022, 

"The term 'Harvard architecture' was coined decades later, in the context of microcontroller design" and only "retrospectively applied to the Harvard machines and subsequently applied to RISC microprocessors with separated caches";
"The so-called 'Harvard' and 'von Neumann' architectures are often portrayed as a dichotomy, but the various devices labeled as the former have far more in common with the latter than they do with each other";
"In short [the Harvard architecture] isn't an architecture and didn't derive from work at Harvard".
Modern processors appear to the user to be systems with von Neumann architectures, with the program code stored in the same main memory as the data. For performance reasons, internally and largely invisible to the user, most designs have separate processor caches for the instructions and data, with separate pathways into the processor for each. This is one form of what is known as the modified Harvard architecture.
Harvard architecture is historically, and traditionally, split into two address spaces, but having three, i.e. two extra (and all accessed in each cycle) is also done, while rare.

## Related

- [[Cellular architecture]]
- [[Dataflow architecture]]
- [[Modified Harvard architecture]]
- [[Single instruction, multiple threads]]
- [[Spatial architecture]]
- [[Superscalar processor]]
- [[Von Neumann architecture]]
- [[Abstraction layer]]
- [[Address space]]
- [[Addressing mode]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Harvard_architecture