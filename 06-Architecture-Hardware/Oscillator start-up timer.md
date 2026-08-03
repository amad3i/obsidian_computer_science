---
title: "Oscillator start-up timer"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Oscillator_start-up_timer"
wikipedia_categories: ["Electronics stubs", "Embedded systems"]
related: ["[[Low-voltage detect]]", "[[Adesto Technologies]]", "[[ADvantage Framework]]", "[[Anti-hijack system]]", "[[Apache Celix]]", "[[Assembly language]]", "[[ATM]]", "[[Automatic system recovery]]", "[[Background debug mode interface]]", "[[BasicX]]"]
---

# Oscillator start-up timer

An oscillator start-up timer (OST) is a module used by some microcontrollers to keep the device reset until the crystal oscillator is stable. When a crystal oscillator starts up, its frequency is not constant, which causes the clock frequency to be non-constant. This would cause timing errors, leading to many problems. An oscillator start-up timer ensures that the device only operates when the oscillator generates a stable clock frequency.
The PIC microcontroller's oscillator start-up timer holds the device's reset for a 1024-oscillator-cycle delay to allow the oscillator to stabilize.

## Related

- [[Low-voltage detect]]
- [[Adesto Technologies]]
- [[ADvantage Framework]]
- [[Anti-hijack system]]
- [[Apache Celix]]
- [[Assembly language]]
- [[ATM]]
- [[Automatic system recovery]]
- [[Background debug mode interface]]
- [[BasicX]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Oscillator_start-up_timer