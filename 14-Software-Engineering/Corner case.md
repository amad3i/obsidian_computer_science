---
title: "Corner case"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Corner_case"
wikipedia_categories: ["Engineering concepts", "Software testing"]
related: ["[[Edge case]]", "[[-dev-full]]", "[[A-B testing]]", "[[Acceptance test-driven development]]", "[[Acceptance testing]]", "[[Ackermann's formula]]", "[[Ad hoc testing]]", "[[Agent verification]]", "[[Agile testing]]", "[[All-pairs testing]]"]
---

# Corner case

In engineering, a corner case (or pathological case) refers to a rare or unusual situation that lies at the margins of a system’s expected operation and may expose limitations or unexpected behaviors. Such cases do not necessarily involve parameters exceeding their specified ranges, but instead represent low-probability scenarios that are difficult to anticipate and handle reliably.
For example, a loudspeaker might distort audio, but only when played at maximum volume, maximum bass, and in a high-humidity environment. Or a computer server may be unreliable, but only with the maximum complement of 64 processors, 512 GB of memory, and 10,000 signed-on users. The investigation of corner cases is of extreme importance as it can provide engineers with valuable insight into how corner case effects can be mitigated.
Corner cases form part of an engineer's lexicon—especially an engineer involved in testing or debugging a complex system. Corner cases are often harder and more expensive to reproduce, test, and optimize because they require maximal configurations in multiple dimensions. They are frequently less-tested, given the belief that few product users will, in practice, exercise the product at multiple simultaneous maximum settings. Expert users of systems therefore routinely find corner case anomalies, and in many of these, errors.
The term "corner case" comes about by physical analogy with "edge case" as an extension of the "flight envelope" metaphor to a set of testing conditions whose boundaries are determined by the 2n combinations of extreme (minimum and maximum) values for the number n of variables being tested, i.e., the total parameter space for those variables. Where an edge case involves pushing one variable to a minimum or maximum, putting users at the "edge" of the configuration space, a corner case involves doing so with multiple variables, which would put users at a "corner" of a multidimensional configuration space.

## Related

- [[Edge case]]
- [[-dev-full]]
- [[A-B testing]]
- [[Acceptance test-driven development]]
- [[Acceptance testing]]
- [[Ackermann's formula]]
- [[Ad hoc testing]]
- [[Agent verification]]
- [[Agile testing]]
- [[All-pairs testing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Corner_case