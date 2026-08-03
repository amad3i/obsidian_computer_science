---
title: "Pulse transition detector"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Pulse_transition_detector"
wikipedia_categories: ["Electronics stubs", "Logic gates"]
related: ["[[Diode-or circuit]]", "[[Fan-in]]", "[[Shift register lookup table]]", "[[AND gate]]", "[[AND-OR-invert]]", "[[Boolean function]]", "[[C-element]]", "[[Channelizer]]", "[[Computer module]]", "[[Controlled reception pattern antenna]]"]
---

# Pulse transition detector

A pulse transition detector is used in flip flops in order to achieve edge triggering in the circuit. It merely converts the clock signal's rising edge to a very narrow pulse.
The PTD consists of a delay gate (which delays the clock signal) and the clock signal itself passed through a NAND gate and then inverted.
The benefit of edge triggering is that it removes the problems of zeroes and ones catching associated with pulse triggered flip-flops (e.g. master slave flip flops).

## Related

- [[Diode-or circuit]]
- [[Fan-in]]
- [[Shift register lookup table]]
- [[AND gate]]
- [[AND-OR-invert]]
- [[Boolean function]]
- [[C-element]]
- [[Channelizer]]
- [[Computer module]]
- [[Controlled reception pattern antenna]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Pulse_transition_detector