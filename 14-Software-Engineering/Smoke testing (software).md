---
title: "Smoke testing (software)"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Smoke_testing_(software)"
wikipedia_categories: ["Software testing", "Tests"]
related: ["[[Component-based usability testing]]", "[[Dry run (testing)]]", "[[Load testing]]", "[[-dev-full]]", "[[A-B testing]]", "[[Acceptance test-driven development]]", "[[Acceptance testing]]", "[[Ad hoc testing]]", "[[Agent verification]]", "[[Agile testing]]"]
---

# Smoke testing (software)

In computer programming and software testing, smoke testing (also confidence testing, sanity testing, build verification test (BVT) and build acceptance test) is preliminary testing or sanity testing to reveal simple failures severe enough to, for example, reject a prospective software release. Smoke tests are a subset of test cases that cover the most important functionality of a component or system, used to aid assessment of whether main functions of the software appear to work correctly. When used to determine if a computer program should be subjected to further, more fine-grained testing, a smoke test may be called a pretest or an intake test. Alternatively, it is a set of tests run on each new build of a product to verify that the build is testable before the build is released into the hands of the test team. In the DevOps paradigm, use of a build verification test step is one hallmark of the continuous integration maturity stage.
For example, a smoke test may address basic questions like "does the program run?", "does the user interface open?", or "does clicking the main button do anything?" The process of smoke testing aims to determine whether the application is so badly broken as to make further immediate testing unnecessary. As the book Lessons Learned in Software Testing puts it, "smoke tests broadly cover product features in a limited time [...] if key features don't work or if key bugs haven't yet been fixed, your team won't waste further time installing or testing".
Smoke tests frequently run quickly, giving benefits of faster feedback, rather than running more extensive test suites, which would naturally take longer.
Frequent reintegration with smoke testing is among industry best practices. Ideally, every commit to a source code repository should trigger a Continuous Integration build, to identify regressions as soon as possible. If builds take too long, you might batch up several commits into one build, or very large systems might be rebuilt once a day. Overall, rebuild and retest as often as you can.
Smoke testing is also done by testers before accepting a build for further testing. Microsoft claims that after code reviews, "smoke testing is the most cost-effective method for identifying and fixing defects in software".
One can perform smoke tests either manually or using an automated tool. In the case of automated tools, the process that generates the build will often initiate the testing.
Smoke tests can be functional tests or unit tests. Functional tests exercise the complete program with various inputs. Unit tests exercise individual functions, subroutines, or object methods. Functional tests may comprise a scripted series of program inputs, possibly even with an automated mechanism for controlling mouse movements. Unit tests can be implemented either as separate functions within the code itself, or else as a driver layer that links to the code without altering the code being tested.

## Related

- [[Component-based usability testing]]
- [[Dry run (testing)]]
- [[Load testing]]
- [[-dev-full]]
- [[A-B testing]]
- [[Acceptance test-driven development]]
- [[Acceptance testing]]
- [[Ad hoc testing]]
- [[Agent verification]]
- [[Agile testing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Smoke_testing_(software)