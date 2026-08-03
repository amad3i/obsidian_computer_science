---
title: "Mutation testing"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Mutation_testing"
wikipedia_categories: ["Software testing"]
related: ["[[-dev-full]]", "[[A-B testing]]", "[[Acceptance test-driven development]]", "[[Acceptance testing]]", "[[Ad hoc testing]]", "[[Agent verification]]", "[[Agile testing]]", "[[All-pairs testing]]", "[[Analytical Performance Modeling]]", "[[API testing]]"]
---

# Mutation testing

Mutation testing (or mutation analysis or program mutation) is used to design new software tests and evaluate the quality of existing software tests.  Mutation testing involves making small changes to the program being tested. Each changed version is called a mutant. A test detects, and therefore rejects, a mutant upon test failure –– failure indicating that the test successfully discerned that the behaviour of the mutant differs from the behaviour of the original code. Rejection is called killing the mutant. The value of a test suite is measured by the percentage of mutants that it kills. The test suite can then be improved by adding new tests designed to kill additional mutants.
Mutant creation is done using well-defined mutation operators that either mimic typical programming errors (such as using the wrong operator or variable name) or force the creation of valuable tests (such as dividing each expression by zero).
Mutation testing is a form of white-box testing. Its purpose is to help the tester develop effective regression tests by locating weaknesses in the test data used to test the program and discovering sections of the tested program's code that are seldom or never accessed during execution.

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

- Wikipedia: https://en.wikipedia.org/wiki/Mutation_testing