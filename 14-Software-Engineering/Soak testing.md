---
title: "Soak testing"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Soak_testing"
wikipedia_categories: ["Environmental testing", "Software engineering stubs", "Software testing"]
related: ["[[Augmented reality-based testing]]", "[[Basis path testing]]", "[[Daily build]]", "[[Decision-to-decision path]]", "[[Domain testing]]", "[[Domain-to-range ratio]]", "[[Recovery testing]]", "[[Risk-based testing]]", "[[Robustness testing]]", "[[White box (software engineering)]]"]
---

# Soak testing

Soak testing is a type of system testing with a typical production load, over a continuous availability period, to validate system behavior under production use.
It may be required to extrapolate the results, if not possible to conduct such an extended test.   For example, if the system is required to process 10,000 transactions over 100 hours, it may be possible to complete processing the same 10,000 transactions in a shorter duration (say 50 hours) as representative (and conservative estimate) of the actual production use.  A good soak test would also include the ability to simulate peak loads as opposed to just average loads. If manipulating the load over specific periods of time is not possible, alternatively (and conservatively) allow the system to run at peak production loads for the duration of the test.
For example, in software testing, a system may behave exactly as expected when tested for one hour. However, when it is tested for three hours, problems such as memory leaks cause the system to fail or behave unexpectedly.
Soak tests are used primarily to check the reaction of a subject under test under a possible simulated environment for a given duration and for a given threshold.  Observations made during the soak test are used to improve the characteristics of the subject under further tests.
In electronics, soak testing may involve testing a system up to or above its maximum ratings for a long period of time. Some companies may soak test a product for a period of many months, while also applying external stresses such as elevated temperatures.
This falls under load testing.

## Related

- [[Augmented reality-based testing]]
- [[Basis path testing]]
- [[Daily build]]
- [[Decision-to-decision path]]
- [[Domain testing]]
- [[Domain-to-range ratio]]
- [[Recovery testing]]
- [[Risk-based testing]]
- [[Robustness testing]]
- [[White box (software engineering)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Soak_testing