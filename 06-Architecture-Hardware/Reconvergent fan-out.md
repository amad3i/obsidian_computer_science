---
title: "Reconvergent fan-out"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Reconvergent_fan-out"
wikipedia_categories: ["Logic gates"]
related: ["[[AND gate]]", "[[AND-OR-invert]]", "[[Boolean function]]", "[[C-element]]", "[[Computer module]]", "[[David E. Muller]]", "[[DEC System Module]]", "[[Diode-or circuit]]", "[[Fan-in]]", "[[Fan-out]]"]
---

# Reconvergent fan-out

Reconvergent fan-out is a circuit design technique to make VLSI logic simulation less pessimistic.
Static timing analysis tries to figure out the best and worst case time estimate for each signal as they pass through an electronic device.  Whenever a signal passes through a node, a bit of uncertainty must be added to the time required for the signal to transit that device.  These uncertain delays add up so, after passing through many devices, the worst-case timing for a signal could be unreasonably pessimistic.
A reconvergent fan-out model uses two or more signals which share an identical path, branch and follow different paths for a while, then converge back to the same point to produce a result.  This reduces timing variance because the divided path can compensate for delays in each individual path. Even though each signal has an uncertain delay, because their delays were identical for part of the journey the total uncertainty can be reduced. This tightens up the worst-case estimation for the signal delay, and usually allows a small but important speedup of the overall device. Timing benchmarks designed for single-pass approaches must be adapted for use with reconvergent fan-out circuits to account for wiring differences.

## Related

- [[AND gate]]
- [[AND-OR-invert]]
- [[Boolean function]]
- [[C-element]]
- [[Computer module]]
- [[David E. Muller]]
- [[DEC System Module]]
- [[Diode-or circuit]]
- [[Fan-in]]
- [[Fan-out]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Reconvergent_fan-out