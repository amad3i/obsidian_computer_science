---
title: "Stress testing (software)"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Stress_testing_(software)"
wikipedia_categories: ["Software testing"]
related: ["[[-dev-full]]", "[[A-B testing]]", "[[Acceptance test-driven development]]", "[[Acceptance testing]]", "[[Ad hoc testing]]", "[[Agent verification]]", "[[Agile testing]]", "[[All-pairs testing]]", "[[Analytical Performance Modeling]]", "[[API testing]]"]
---

# Stress testing (software)

Stress testing is a software testing activity that determines the robustness of software by testing beyond the limits of normal operation. Stress testing is particularly important for "mission critical" software, but is used for all types of software. Stress tests commonly put a greater emphasis on robustness, availability, and error handling under a heavy load, than on what would be considered correct behavior under normal circumstances.
A system stress test refers to tests that put a greater emphasis on robustness, availability, and error handling under a heavy load, rather than on what would be considered correct behavior under normal circumstances. In particular, the goals of such tests may be to ensure the software does not crash in conditions of insufficient computational resources (such as memory or disk space), unusually high concurrency, or denial of service attacks.
Examples:

A web server may be stress tested using scripts, bots, and various denial of service tools to observe the performance of a web site during peak loads. These attacks generally are under an hour long, or until a limit in the amount of data that the web server can tolerate is found.
Stress testing may be contrasted with load testing:

Load testing examines the entire environment and database, while measuring the response time, whereas stress testing focuses on identified transactions, pushing to a level so as to break transactions or systems.
During stress testing, if transactions are selectively stressed, the database may not experience much load, but the transactions are heavily stressed. On the other hand, during load testing the database experiences a heavy load, while some transactions may not be stressed.
System stress testing, also known as stress testing, is loading the concurrent users over and beyond the level that the system can handle, so it breaks at the weakest link within the entire system.

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

- Wikipedia: https://en.wikipedia.org/wiki/Stress_testing_(software)