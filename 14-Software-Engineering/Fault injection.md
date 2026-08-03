---
title: "Fault injection"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Fault_injection"
wikipedia_categories: ["Software testing"]
related: ["[[-dev-full]]", "[[A-B testing]]", "[[Acceptance test-driven development]]", "[[Acceptance testing]]", "[[Ad hoc testing]]", "[[Agent verification]]", "[[Agile testing]]", "[[All-pairs testing]]", "[[Analytical Performance Modeling]]", "[[API testing]]"]
---

# Fault injection

In computer science, fault injection is a testing technique for understanding how computing systems behave when stressed in unusual ways. This can be achieved using physical- or software-based means, or using a hybrid approach. Widely studied physical fault injections include the application of high voltages, extreme temperatures and electromagnetic pulses on electronic components, such as computer memory and central processing units. By exposing components to conditions beyond their intended operating limits, computing systems can be coerced into mis-executing instructions and corrupting critical data. 
In software testing, fault injection is a technique for improving the coverage of a test by introducing faults to test code paths; in particular error handling code paths, that might otherwise rarely be followed. It is often used with stress testing and is widely considered to be an important part of developing robust software. Robustness testing (also known as syntax testing, fuzzing or fuzz testing) is a type of fault injection commonly used to test for vulnerabilities in communication interfaces such as protocols, command line parameters, or APIs.
The propagation of a fault through to an observable failure follows a well-defined cycle. When executed, a fault may cause an error, which is an invalid state within a system boundary. An error may cause further errors within the system boundary, therefore each new error acts as a fault, or it may propagate to the system boundary and be observable. When error states are observed at the system boundary they are termed failures. This mechanism is termed the fault-error-failure cycle and is a key mechanism in dependability.

## Related

- [[-dev-full]]
- [[A-B testing]]
- [[Acceptance test-driven development]]
- [[Acceptance testing]]
- [[Ad hoc testing]]
- [[Agent verification]]
- [[Agile testing]]
- [[All-pairs testing]]
- [[Analytical Performance Modeling]]
- [[API testing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fault_injection