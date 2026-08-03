---
title: "Field-programmable analog array"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Field-programmable_analog_array"
wikipedia_categories: ["Analog circuits", "Gate arrays", "Integrated circuits", "Signal processing"]
related: ["[[Asymptotic gain model]]", "[[Negative feedback]]", "[[Norator]]", "[[Nullator]]", "[[Nullor]]", "[[Step response]]", "[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]"]
---

# Field-programmable analog array

A field-programmable analog array (FPAA) is an integrated circuit device containing computational analog blocks (CABs) and interconnects between these blocks offering field-programmability. Unlike their digital cousin, the FPGA, the devices tend to be more application driven than general purpose as they may be current mode or voltage mode devices. For voltage mode devices, each block usually contains an operational amplifier in combination with programmable configuration of passive components. The blocks can, for example, act as summers or integrators.
FPAAs usually operate in one of two modes: continuous time and discrete time.

Discrete-time devices possess a system sample clock. In a switched capacitor design, all blocks sample their input signals with a sample and hold circuit composed of a semiconductor switch and a capacitor. This feeds a programmable op amp section which can be routed to a number of other blocks. This design requires more complex semiconductor construction. An alternative, switched-current design, offers simpler construction and does not require the input capacitor, but can be less accurate, and has lower fan-out - it can drive only one following block. Both discrete-time device types must compensate for switching noise, aliasing at the system sample rate, and sample-rate limited bandwidth, during the design phase.
Continuous-time devices work more like an array of transistors or op amps which can operate at their full bandwidth. The components are connected in a particular arrangement through a configurable array of switches. During circuit design, the switch matrix's parasitic inductance, capacitance and noise contributions must be taken into account.
Currently there are very few manufacturers of FPAAs. On-chip resources are still very limited when compared to that of an FPGA. This resource deficit is often cited by researchers as a limiting factor in their research.

## Related

- [[Asymptotic gain model]]
- [[Negative feedback]]
- [[Norator]]
- [[Nullator]]
- [[Nullor]]
- [[Step response]]
- [[Adaptive beamformer]]
- [[Adjacent channel power ratio]]
- [[Algebraic signal processing]]
- [[Aliasing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Field-programmable_analog_array