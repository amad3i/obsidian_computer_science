---
title: "Separation of mechanism and policy"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Separation_of_mechanism_and_policy"
wikipedia_categories: ["Dichotomies", "Operating system technology", "Programming principles"]
related: ["[[ALTQ]]", "[[Application binary interface]]", "[[Apptainer]]", "[[Asynchronous system trap]]", "[[Attached Support Processor]]", "[[Binary Application Markup Language]]", "[[Black box]]", "[[Busdma]]", "[[Chain loading]]", "[[Cohesion (computer science)]]"]
---

# Separation of mechanism and policy

The separation of mechanism and policy is a design principle in computer science.  It states that mechanisms (those parts of a system implementation that control the authorization of operations and the allocation of resources) should not dictate (or overly restrict) the policies according to which decisions are made about which operations to authorize, and which resources to allocate.
While most commonly discussed in the context of security mechanisms (authentication and authorization), separation of mechanism and policy is applicable to a range of resource allocation
problems (e.g. CPU scheduling, memory allocation, quality of service) as well as the design of software abstractions.
Per Brinch Hansen introduced the concept of separation of policy and mechanism in operating systems in the RC 4000 multiprogramming system. Artsy and Livny, in a 1987 paper, discussed an approach for an operating system design having an "extreme separation of mechanism and policy". In a 2000 article, Chervenak et al. described the principles of mechanism neutrality and policy neutrality.

## Related

- [[ALTQ]]
- [[Application binary interface]]
- [[Apptainer]]
- [[Asynchronous system trap]]
- [[Attached Support Processor]]
- [[Binary Application Markup Language]]
- [[Black box]]
- [[Busdma]]
- [[Chain loading]]
- [[Cohesion (computer science)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Separation_of_mechanism_and_policy