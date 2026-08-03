---
title: "Watchdog timer"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Watchdog_timer"
wikipedia_categories: ["Embedded systems"]
related: ["[[Adesto Technologies]]", "[[ADvantage Framework]]", "[[Anti-hijack system]]", "[[Apache Celix]]", "[[Assembly language]]", "[[ATM]]", "[[Automatic system recovery]]", "[[Background debug mode interface]]", "[[BasicX]]", "[[Bendix Electrojector]]"]
---

# Watchdog timer

A watchdog timer (WDT, or simply a watchdog), sometimes called a computer operating properly timer (COP timer), is an electronic or software timer that is used to detect and recover from computer malfunctions. Watchdog timers are widely used in computers to facilitate automatic correction of temporary hardware faults, and to prevent errant or malevolent software from disrupting system operation.
During normal operation, the computer regularly restarts the watchdog timer to prevent it from elapsing, or timing out. If, due to a hardware fault or program error, the computer fails to restart the watchdog, the timer will elapse and generate a timeout signal. The timeout signal is used to initiate corrective actions. The corrective actions typically include placing the computer and associated hardware in a safe state and invoking a computer reboot.
Microcontrollers often include an integrated, on-chip watchdog. In other computers the watchdog may reside in a nearby chip that connects directly to the CPU, or it may be located on an external expansion card in the computer's chassis.

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

- Wikipedia: https://en.wikipedia.org/wiki/Watchdog_timer