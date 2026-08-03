---
title: "Data-driven testing"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Data-driven_testing"
wikipedia_categories: ["Software testing"]
related: ["[[-dev-full]]", "[[A-B testing]]", "[[Acceptance test-driven development]]", "[[Acceptance testing]]", "[[Ad hoc testing]]", "[[Agent verification]]", "[[Agile testing]]", "[[All-pairs testing]]", "[[Analytical Performance Modeling]]", "[[API testing]]"]
---

# Data-driven testing

Data-driven testing (DDT), also known as table-driven testing or parameterized testing, is a software testing technique that uses a table of data that directs test execution by encoding input, expected output and test-environment settings. One advantage of DDT over other testing techniques is relative ease to cover an additional test case for the system under test by adding a line to a table instead of having to modify test source code.
Often, a table provides a complete set of stimulus input and expected outputs in each row of the table. Stimulus input values typically cover values that correspond to boundary or partition input spaces. 
DDT involves a framework that executes tests based on input data. The framework is a re-usable test asset that can reduce maintenance of a test codebase. DDT allows for anything that has a potential to change to be segregated from the framework and stored in an external asset. The framework might manage storage of tables and test results in a database such as data pool, DAO and ADO. An advanced framework might harvest data from a running system using a purpose-built tool (sniffer). The DDT framework can play back harvested data for regression testing.
Automated test suites contain user interactions through the system's GUI, for repeatable testing. Each test begins with a copy of the "before" image reference database. The "user interactions" are replayed through the "new" GUI version and result in the "post test" database. The reference "post test" database is compared to the "post test" database, using a tool. Differences reveal probable regression. Navigation of the system under test's  user interface, reading data sources, and logging test findings may be coded in the table.
Keyword-driven testing is similar except that the logic for the test case itself is encoded as data values in the form of a set of "action words", and not embedded or "hard-coded" in the test script. The script is simply a "driver" (or delivery mechanism) for the data that is held in the data source.

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

- Wikipedia: https://en.wikipedia.org/wiki/Data-driven_testing