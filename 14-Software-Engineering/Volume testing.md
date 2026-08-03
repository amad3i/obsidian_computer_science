---
title: "Volume testing"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Volume_testing"
wikipedia_categories: ["Software testing"]
related: ["[[-dev-full]]", "[[A-B testing]]", "[[Acceptance test-driven development]]", "[[Acceptance testing]]", "[[Ad hoc testing]]", "[[Agent verification]]", "[[Agile testing]]", "[[All-pairs testing]]", "[[Analytical Performance Modeling]]", "[[API testing]]"]
---

# Volume testing

Volume testing belongs to the group of non-functional tests, which are a group of tests often misunderstood and/or used interchangeably. Volume testing refers to testing a software application with a certain amount of data to assert the system performance with a certain amount of data in the database. Volume testing is regarded by some as a type of capacity testing, and is often deemed necessary as other types of tests normally don't use large amounts of data, but rather typically use small amounts of data. It is the only type of test which checks the ability of a system to handle large pools of data. For example, the test can be used to stress the database to its maximum limit. While the amount can, in generic terms, be the database size, it could also be the size of an interface file that is the subject of volume testing. For example, if one wants to volume test an application with a specific database size, the database will be expanded to that size and the application's performance will then be tested on it. Another example could be when there is a requirement for the application to interact with an interface file (could be any file such as .dat, .xml); this interaction could be reading and/or writing on to/from the file. A sample file of an intended size can then be created and used to test the application's functionality in order to test the performance.

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

- Wikipedia: https://en.wikipedia.org/wiki/Volume_testing