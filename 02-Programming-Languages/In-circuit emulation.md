---
title: "In-circuit emulation"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/In-circuit_emulation"
wikipedia_categories: ["Debugging", "Embedded systems"]
related: ["[[Ceibo emulator]]", "[[Flash memory emulator]]", "[[In-target probe]]", "[[Adesto Technologies]]", "[[ADvantage Framework]]", "[[Anti-hijack system]]", "[[Apache Celix]]", "[[Assembly language]]", "[[Assertion (software development)]]", "[[ATM]]"]
---

# In-circuit emulation

In-circuit emulation (ICE) is the use of a hardware device or in-circuit emulator used to debug the software of an embedded system. It operates by using a processor with the additional ability to support debugging operations, as well as to carry out the main function of the system. Particularly for older systems, with limited processors, this usually involved replacing the processor temporarily with a hardware emulator: a more powerful although more expensive version. It was historically in the form of bond-out processor which has many internal signals brought out for the purpose of debugging. These signals provide information about the state of the processor.
More recently the term also covers JTAG-based hardware debuggers which provide equivalent access using on-chip debugging hardware with standard production chips.  Using standard chips instead of custom bond-out versions makes the technology ubiquitous and low cost, and eliminates most differences between the development and runtime environments. In this common case, the in-circuit emulator term is a misnomer, sometimes confusingly so, because emulation is no longer involved.
Embedded systems present special problems for programmers because they usually lack keyboards, monitors, disk drives and other user interfaces that are present on computers. These shortcomings make in-circuit software debugging tools essential for many common development tasks.

## Related

- [[Ceibo emulator]]
- [[Flash memory emulator]]
- [[In-target probe]]
- [[Adesto Technologies]]
- [[ADvantage Framework]]
- [[Anti-hijack system]]
- [[Apache Celix]]
- [[Assembly language]]
- [[Assertion (software development)]]
- [[ATM]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/In-circuit_emulation