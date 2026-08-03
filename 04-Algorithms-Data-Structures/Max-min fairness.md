---
title: "Max-min fairness"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Max-min_fairness"
wikipedia_categories: ["Fairness criteria", "Network scheduling algorithms", "Routing algorithms"]
related: ["[[Credit-based fair queuing]]", "[[A- search algorithm]]", "[[ALTQ]]", "[[Arc routing]]", "[[Augmented tree-based routing]]", "[[B-]]", "[[Babel (protocol)]]", "[[Backpressure routing]]", "[[Contraction hierarchies]]", "[[Diffusing update algorithm]]"]
---

# Max-min fairness

In communication networks, multiplexing and the division of scarce resources, max-min fairness is said to be achieved by an allocation if and only if the allocation is feasible and an attempt to increase the allocation of any participant necessarily results in the decrease in the allocation of some other participant with an equal or smaller allocation. 
In best-effort statistical multiplexing, a first-come first-served (FCFS) scheduling policy is often used. The advantage with max-min fairness over FCFS is that it results in traffic shaping, meaning that an ill-behaved flow, consisting of large data packets or bursts of many packets, will only punish itself and not other flows. Network congestion is consequently to some extent avoided.
Fair queuing is an example of a max-min fair packet scheduling algorithm for statistical multiplexing and best-effort networks, since it gives scheduling priority to users that have achieved lowest data rate since they became active. In case of equally sized data packets, round-robin scheduling is max-min fair.

## Related

- [[Credit-based fair queuing]]
- [[A- search algorithm]]
- [[ALTQ]]
- [[Arc routing]]
- [[Augmented tree-based routing]]
- [[B-]]
- [[Babel (protocol)]]
- [[Backpressure routing]]
- [[Contraction hierarchies]]
- [[Diffusing update algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Max-min_fairness