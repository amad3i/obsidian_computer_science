---
title: "Real-time Java"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Real-time_Java"
wikipedia_categories: ["Java (programming language)", "Real-time computing"]
related: ["[[AgentSheets]]", "[[AQuoSA]]", "[[Arthur Pollen]]", "[[Boxing (computer programming)]]", "[[CompactDAQ]]", "[[CompactRIO]]", "[[CPU shielding]]", "[[Earliest deadline first scheduling]]", "[[Earliest eligible virtual deadline first scheduling]]", "[[Edison Design Group]]"]
---

# Real-time Java

Real-time Java is a catch-all term for a combination of technologies that enables programmers to write programs that meet the demands of real-time systems in the Java programming language.
Java's sophisticated memory management, native support for threading and concurrency, type safety, and relative simplicity have created a demand for its use in many domains.  Its capabilities have been enhanced to support real-time computational needs:

Real-time Java supports a strict priority-based threading model,
because Java threads support priorities, Java locking mechanisms support priority inversion avoidance techniques, such as priority inheritance or the priority ceiling protocol, and
event handling.
The initial proposal for an open standard for real-time Java was put forth by Kelvin Nilsen, then serving as a research faculty member at Iowa State University.  A follow-on overview paper was published in the Communications of the ACM. The overwhelmingly positive response to these early proposals resulted in a series of meetings hosted by the National Institute of Standards and Technology in an effort to establish an open standard for real-time Java.  NIST was ultimately told that they were not the appropriate body to establish standards related to the Java language, as Java was trademarked, and the technologies were owned by Sun Microsystems. Therefore, NIST ended their efforts with publication of consensus requirements. that could be considered by future standardization efforts to be hosted by Sun Microsystems.
When the Java Community was formed, the very first effort was the specification for real-time Java, JSR001. A number of implementations of the resulting Real-time specification for Java (RTSJ) have emerged, including a reference implementation from Timesys, IBM's WebSphere Real Time, Sun Microsystems's Java SE Real-Time Systems, PTC Perc from PTC, Inc., or JamaicaVM from aicas.
The RTSJ addressed the critical issues by mandating a minimum specification for the threading model (and allowing other models to be plugged into the VM) and by providing for areas of memory that are not subject to garbage collection, along with threads that are not preemptable by the garbage collector. These areas are instead managed using region-based memory management. The latest specification, 2.0, supports direct device access and deterministic garbage collection as well.

## Related

- [[AgentSheets]]
- [[AQuoSA]]
- [[Arthur Pollen]]
- [[Boxing (computer programming)]]
- [[CompactDAQ]]
- [[CompactRIO]]
- [[CPU shielding]]
- [[Earliest deadline first scheduling]]
- [[Earliest eligible virtual deadline first scheduling]]
- [[Edison Design Group]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Real-time_Java