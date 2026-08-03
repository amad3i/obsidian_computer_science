---
title: "Fan-in"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Fan-in"
wikipedia_categories: ["Electronics stubs", "Logic gates"]
related: ["[[Diode-or circuit]]", "[[Pulse transition detector]]", "[[Shift register lookup table]]", "[[AND gate]]", "[[AND-OR-invert]]", "[[Boolean function]]", "[[C-element]]", "[[Channelizer]]", "[[Computer module]]", "[[Controlled reception pattern antenna]]"]
---

# Fan-in

Fan-in is the number of inputs a logic gate can handle. For instance the fan-in for the AND gate shown in the figure is 3.  Physical logic gates with a large fan-in tend to be slower than those with a small fan-in. This is because the complexity of the input circuitry increases the input capacitance of the device. Using logic gates with higher fan-in will help in reducing the depth of a logic circuit; this is because circuit design is realized by the target logic family at a digital level, meaning any large fan-in logic gates are simply the smaller fan-in gates chained together in series at a given depth to widen the circuit instead.
Fan-in tree of a node refers to a collection of signals that contribute to the input signal of that node.
In quantum logic gates the fan-in always has to be equal to the number of outputs, the fan-out. Gates for which the numbers of inputs and outputs differ would not be reversible (unitary) and are therefore not allowed.

## Related

- [[Diode-or circuit]]
- [[Pulse transition detector]]
- [[Shift register lookup table]]
- [[AND gate]]
- [[AND-OR-invert]]
- [[Boolean function]]
- [[C-element]]
- [[Channelizer]]
- [[Computer module]]
- [[Controlled reception pattern antenna]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fan-in