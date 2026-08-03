---
title: "Vegeta (software)"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Vegeta_(software)"
wikipedia_categories: ["Command-line software", "Linux software", "Load testing tools", "Quality assurance", "Software testing", "Software using the MIT license"]
related: ["[[Load testing]]", "[[RadView Software]]", "[[List of software bugs]]", "[[Login VSI]]", "[[Service virtualization]]", "[[Siege (software)]]", "[[-dev-full]]", "[[A-Frame (software)]]", "[[A-B testing]]", "[[Acceptance test-driven development]]"]
---

# Vegeta (software)

Vegeta is an HTTP load testing tool written in Go that can be used as a command in a command-line interface or as a library. The program tests how an HTTP-based application behaves when multiple users access it at the same time by generating a background load of GET requests. Vegeta is used to generate a sustained, constant number of requests per second in order to discover how long a service can sustain a peak load before dropping in performance.
In addition to preemptive load testing, the program can also be used for shadow testing, where traffic from a live version of an application is mirrored onto a test version to determine how it handles the same traffic load, without causing potential disruption to the live version of the application. Shadow testing is done in this way in order to analyze anticipated server performance.
Vegeta is provided for use by web hosting services such as Scaleway to use varied and multiple requests to stress test client HTTP services. It is also used with dedicated load-testing platform services such as BlazeMeter.

## Related

- [[Load testing]]
- [[RadView Software]]
- [[List of software bugs]]
- [[Login VSI]]
- [[Service virtualization]]
- [[Siege (software)]]
- [[-dev-full]]
- [[A-Frame (software)]]
- [[A-B testing]]
- [[Acceptance test-driven development]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Vegeta_(software)