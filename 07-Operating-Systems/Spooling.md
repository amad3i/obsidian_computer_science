---
title: "Spooling"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Spooling"
wikipedia_categories: ["Computer printing", "Job scheduling", "Operating system technology", "Unix software"]
related: ["[[Attached Support Processor]]", "[[Beowulf cluster]]", "[[ALTQ]]", "[[Application binary interface]]", "[[Apptainer]]", "[[Asynchronous system trap]]", "[[Binary Application Markup Language]]", "[[Busdma]]", "[[Chain loading]]", "[[Computer multitasking]]"]
---

# Spooling

In computing, spooling is a specialized form of multi-programming for the purpose of copying data between different devices. In contemporary systems, it is usually used for mediating between a computer application and a slow peripheral, such as a printer.  Spooling allows programs to "hand off" work to be done by the peripheral and then proceed to other tasks, or to not begin until input has been transcribed.  A dedicated program, the spooler, maintains an orderly sequence of jobs for the peripheral and feeds it data at its own rate.  Conversely, for slow input peripherals, such as a card reader, a spooler can maintain a sequence of computational jobs waiting for data, starting each job when all of the relevant input is available; see batch processing.  The spool itself refers to the sequence of jobs, or the storage area where they are held. In many cases, the spooler is able to drive devices at their full rated speed with minimal impact on other processing.
Spooling is a combination of buffering and queueing.

## Related

- [[Attached Support Processor]]
- [[Beowulf cluster]]
- [[ALTQ]]
- [[Application binary interface]]
- [[Apptainer]]
- [[Asynchronous system trap]]
- [[Binary Application Markup Language]]
- [[Busdma]]
- [[Chain loading]]
- [[Computer multitasking]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Spooling