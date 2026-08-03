---
title: "March algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/March_algorithm"
wikipedia_categories: []
related: []
---

# March algorithm

The March algorithm is a widely used algorithm that tests SRAM memory by filling all its entries test patterns. It carries out several passes through an SRAM checking the patterns and writing new patterns.
The SRAM read and write operations performed on each pass are called a March element and each element is repeated for each entry. The March algorithm is often used to find functional faults in SRAM during testing such as:

Stuck-at Faults (SAFs)
Transition Faults (TFs)
Address Decoder Faults (AFs)
Coupling Faults (CFs), such as Inversion (CFin), Idempotent (CFid), and State (CFst) coupling faults
It has been suggested to test SRAM modules using the algorithm before sale using a built-in self-test mechanism.

## Related

*(no automatic links — see MOC)*

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/March_algorithm