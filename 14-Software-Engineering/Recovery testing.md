---
title: "Recovery testing"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Recovery_testing"
wikipedia_categories: ["Software engineering stubs", "Software testing"]
related: ["[[Augmented reality-based testing]]", "[[Basis path testing]]", "[[Daily build]]", "[[Decision-to-decision path]]", "[[Domain testing]]", "[[Domain-to-range ratio]]", "[[Risk-based testing]]", "[[Robustness testing]]", "[[Soak testing]]", "[[White box (software engineering)]]"]
---

# Recovery testing

In software testing, recovery testing is the activity of testing how well an application is able to recover from crashes, hardware failures and other similar problems.
Recovery testing is the forced failure of the software in a variety of ways to verify that recovery is
properly performed. Recovery testing should not be confused with reliability testing, which tries to discover the specific point at which failure occurs. Recovery testing is basically done in order to check how fast and better the application can recover against any type of crash or hardware failure etc. Recovery testing is simulating failure modes or actually causing failures in a controlled environment. Following a failure, the failover mechanism is tested to ensure that data is not lost or corrupted and that any agreed service levels are maintained (e.g., function availability or response times). Type or extent of recovery is specified in the requirement specifications. It is basically testing how well a system recovers from crashes, hardware failures, or other catastrophic problems.
Examples of recovery testing:

While an application is running, suddenly restart the computer, and afterwards check the validness of the application's data integrity.
While an application is receiving data from a network, unplug the connecting cable. After some time, plug the cable back in and analyze the application's ability to continue receiving data from the point at which the network connection disappeared.

## Related

- [[Augmented reality-based testing]]
- [[Basis path testing]]
- [[Daily build]]
- [[Decision-to-decision path]]
- [[Domain testing]]
- [[Domain-to-range ratio]]
- [[Risk-based testing]]
- [[Robustness testing]]
- [[Soak testing]]
- [[White box (software engineering)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Recovery_testing