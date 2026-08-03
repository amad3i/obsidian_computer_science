---
title: "Bond-out processor"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Bond-out_processor"
wikipedia_categories: ["Embedded systems"]
related: ["[[Adesto Technologies]]", "[[ADvantage Framework]]", "[[Anti-hijack system]]", "[[Apache Celix]]", "[[Assembly language]]", "[[ATM]]", "[[Automatic system recovery]]", "[[Background debug mode interface]]", "[[BasicX]]", "[[Bendix Electrojector]]"]
---

# Bond-out processor

A bond-out processor is an emulation processor that takes the place of the microcontroller or microprocessor in the target board while an application is being developed and/or debugged.
Bond-out processors have internal signals and bus brought out to external pins. The term bond-out derives from connecting (or bonding) the emulation circuitry to these external pins. These devices are designed to be used within an in-circuit emulator and are not typically used in any other kind of system.
Bond-out pins were marked as no-connects in the first devices produced by Intel, and were usually not connected to anything on the ordinary production silicon. Later bond-out versions of the microprocessor were produced in a bigger package to provide more signals and functionality.
Bond-out processors provides capabilities far beyond those of a simple ROM monitor. A ROM monitor is a firmware program that runs instead of the application code and provides a connection to a host computer to carry out debugging functions. In general the ROM monitor uses part of the processor resources and shares the memory with the user code. 
Bond-out processors  can handle complex breakpoints (even in ROM), real-time traces of processor activity, and no use of target resources. But this extra functionality comes at a high cost, as bond-outs have to be produced for in-circuit emulators only.
Therefore, sometimes solutions similar to bond-outs are implemented with an ASIC or FPGA or a faster RISC processor that imitates the core processor code execution and peripherals.

## Related

- [[Adesto Technologies]]
- [[ADvantage Framework]]
- [[Anti-hijack system]]
- [[Apache Celix]]
- [[Assembly language]]
- [[ATM]]
- [[Automatic system recovery]]
- [[Background debug mode interface]]
- [[BasicX]]
- [[Bendix Electrojector]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bond-out_processor