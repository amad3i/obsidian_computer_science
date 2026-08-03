---
title: "Earliest deadline first scheduling"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Earliest_deadline_first_scheduling"
wikipedia_categories: ["Optimal scheduling", "Processor scheduling algorithms", "Real-time computing"]
related: ["[[YDS algorithm]]", "[[Earliest eligible virtual deadline first scheduling]]", "[[Rate-monotonic scheduling]]", "[[Time-utility function]]", "[[AQuoSA]]", "[[Arthur Pollen]]", "[[CompactDAQ]]", "[[CompactRIO]]", "[[Coscheduling]]", "[[CPU shielding]]"]
---

# Earliest deadline first scheduling

Earliest deadline first (EDF) or least time to go is a dynamic priority scheduling algorithm used in real-time operating systems to place processes in a priority queue. Whenever a scheduling event occurs (task finishes, new task released, etc.) the queue will be searched for the process closest to its deadline. This process is the next to be scheduled for execution.

## Related

- [[YDS algorithm]]
- [[Earliest eligible virtual deadline first scheduling]]
- [[Rate-monotonic scheduling]]
- [[Time-utility function]]
- [[AQuoSA]]
- [[Arthur Pollen]]
- [[CompactDAQ]]
- [[CompactRIO]]
- [[Coscheduling]]
- [[CPU shielding]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Earliest_deadline_first_scheduling