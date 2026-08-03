---
title: "Rate-monotonic scheduling"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Rate-monotonic_scheduling"
wikipedia_categories: ["Processor scheduling algorithms", "Real-time computing"]
related: ["[[Earliest deadline first scheduling]]", "[[Earliest eligible virtual deadline first scheduling]]", "[[YDS algorithm]]", "[[AQuoSA]]", "[[Arthur Pollen]]", "[[CompactDAQ]]", "[[CompactRIO]]", "[[Coscheduling]]", "[[CPU shielding]]", "[[GTFS Realtime]]"]
---

# Rate-monotonic scheduling

In computer science, rate-monotonic scheduling (RMS) is a priority assignment algorithm used in real-time operating systems (RTOS) with a static-priority scheduling class. The static priorities are assigned according to the cycle duration of the job, so a shorter cycle duration results in a higher job priority.
These operating systems are generally preemptive and have deterministic guarantees with regard to response times. Rate monotonic analysis is used in conjunction with those systems to provide scheduling guarantees for a particular application.

## Related

- [[Earliest deadline first scheduling]]
- [[Earliest eligible virtual deadline first scheduling]]
- [[YDS algorithm]]
- [[AQuoSA]]
- [[Arthur Pollen]]
- [[CompactDAQ]]
- [[CompactRIO]]
- [[Coscheduling]]
- [[CPU shielding]]
- [[GTFS Realtime]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Rate-monotonic_scheduling