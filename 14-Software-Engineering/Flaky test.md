---
title: "Flaky test"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Flaky_test"
wikipedia_categories: ["Software anomalies", "Software maintenance", "Software quality", "Software stubs", "Software testing"]
related: ["[[Software map]]", "[[Business process validation]]", "[[List of software bugs]]", "[[Process validation]]", "[[Reverse semantic traceability]]", "[[Self-healing test automation]]", "[[Software quality]]", "[[Software testability]]", "[[Software visualization]]", "[[Sourcetrail]]"]
---

# Flaky test

Flaky test (or flaky test case) is a software test that exhibits non-deterministic behavior, i.e., it may pass or fail inconsistently without any changes in the underlying code. This flakiness can arise from a number of causes, including concurrency issues, timing dependencies, reliance on external systems, or lack of sufficient isolation between tests. Flaky tests are problematic in continuous integration environments because they decrease trust in automated test suites and can hide real defects, leading to wasted debugging effort and decreased productivity.
Flaky tests can be mitigated by improving test isolation, controlling sources of nondeterminism (e.g., time and randomness), mocking of external dependencies, and rerunning of tests to confirm failures. Flakiness is a well-known issue in large-scale software development, and there are many techniques to tackle it, such as test retries, quarantine mechanisms, or better test design practices. Nevertheless, flaky tests remain an active research area in software engineering, especially for distributed systems and large code bases where nondeterminism is more prevalent.

## Related

- [[Software map]]
- [[Business process validation]]
- [[List of software bugs]]
- [[Process validation]]
- [[Reverse semantic traceability]]
- [[Self-healing test automation]]
- [[Software quality]]
- [[Software testability]]
- [[Software visualization]]
- [[Sourcetrail]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Flaky_test