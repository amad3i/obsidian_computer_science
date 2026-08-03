---
title: "Register renaming"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Register_renaming"
wikipedia_categories: ["Computer architecture"]
related: ["[[Abstraction layer]]", "[[Address space]]", "[[Addressing mode]]", "[[Aperture (computer memory)]]", "[[Approximate computing]]", "[[Arithmetic logic unit]]", "[[Autonomous decentralized system]]", "[[Berkeley IRAM project]]", "[[Branch queue]]", "[[Bridging model]]"]
---

# Register renaming

In computer architecture, register renaming is a technique that abstracts logical registers from physical registers.
Every logical register has a set of physical registers associated with it.
When a machine language instruction refers to a particular logical register, the processor transposes this name to one specific physical register on the fly.
The physical registers are opaque and cannot be referenced directly but only via the canonical names.
This technique is used to eliminate false data dependencies arising from the reuse of registers by successive instructions that do not have any real data dependencies between them.
The elimination of these false data dependencies reveals more  instruction-level parallelism in an instruction stream, which can be exploited by various and complementary techniques such as superscalar and out-of-order execution for better performance.

## Related

- [[Abstraction layer]]
- [[Address space]]
- [[Addressing mode]]
- [[Aperture (computer memory)]]
- [[Approximate computing]]
- [[Arithmetic logic unit]]
- [[Autonomous decentralized system]]
- [[Berkeley IRAM project]]
- [[Branch queue]]
- [[Bridging model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Register_renaming