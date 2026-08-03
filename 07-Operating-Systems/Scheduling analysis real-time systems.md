---
title: "Scheduling analysis real-time systems"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Scheduling_analysis_real-time_systems"
wikipedia_categories: ["Scheduling (computing)"]
related: ["[[Blocking (computing)]]", "[[Idle (CPU)]]", "[[Kernel preemption]]", "[[Light-weight process]]", "[[Makespan]]", "[[Resource allocation (computing)]]", "[[Run queue]]", "[[Schedule]]", "[[Scheduling (computing)]]", "[[Server hog]]"]
---

# Scheduling analysis real-time systems

The term scheduling analysis in real-time computing includes the analysis and testing of the scheduler system and the algorithms used in real-time applications. In computer science, real-time scheduling analysis is the evaluation, testing and verification of the scheduling system and the algorithms used in real-time operations. For critical operations, a real-time system must be tested and verified for performance.
A real-time scheduling system is composed of the scheduler, clock and the processing hardware elements. In a real-time system, a process or task has schedulability; tasks are accepted by a real-time system and completed as specified by the task deadline depending on the characteristic of the scheduling algorithm. Modeling and evaluation of a real-time scheduling system concern is on the analysis of the algorithm capability to meet a process deadline. A deadline is defined as the time required for a task to be processed.
For example, in a real-time scheduling algorithm a deadline could be set to five nano-seconds. In a critical operation the task must be processed in the time specified by the deadline (i.e. five nano-seconds). A task in a real-time system must be completed "neither too early nor too late;..". A system is said to be unschedulable when tasks can not meet the specified deadlines. A task can be classified as either a periodic or aperiodic process.

## Related

- [[Blocking (computing)]]
- [[Idle (CPU)]]
- [[Kernel preemption]]
- [[Light-weight process]]
- [[Makespan]]
- [[Resource allocation (computing)]]
- [[Run queue]]
- [[Schedule]]
- [[Scheduling (computing)]]
- [[Server hog]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Scheduling_analysis_real-time_systems