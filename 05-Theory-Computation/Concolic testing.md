---
title: "Concolic testing"
tags: ["cs", "theory-of-computation", "advanced"]
domain: Theory of Computation
level: advanced
source: "https://en.wikipedia.org/wiki/Concolic_testing"
wikipedia_categories: ["Automated theorem proving", "Software testing"]
related: ["[[-dev-full]]", "[[A-B testing]]", "[[Acceptance test-driven development]]", "[[Acceptance testing]]", "[[Ad hoc testing]]", "[[Agent verification]]", "[[Agile testing]]", "[[All-pairs testing]]", "[[Analytical Performance Modeling]]", "[[API testing]]"]
---

# Concolic testing

Concolic testing (a portmanteau of concrete and symbolic, also known as dynamic symbolic execution) is a hybrid software verification technique that performs symbolic execution, a classical technique that treats program variables as symbolic variables, along a concrete execution (testing on particular inputs) path. Symbolic execution is used in conjunction with an automated theorem prover or constraint solver based on constraint logic programming to generate new concrete inputs (test cases) with the aim of maximizing code coverage. Its main focus is finding bugs in real-world software, rather than demonstrating program correctness.
A description and discussion of the concept was introduced in "DART: Directed Automated Random Testing" by Patrice Godefroid, Nils Klarlund, and Koushik Sen. The paper "CUTE: A concolic unit testing engine for C", by Koushik Sen, Darko Marinov, and Gul Agha, further extended the idea to data structures, and first coined the term concolic testing. Another tool, called EGT (renamed to EXE and later improved and renamed to KLEE), based on similar ideas was independently developed by Cristian Cadar and Dawson Engler in 2005, and published in 2005 and 2006. PathCrawler first proposed to perform symbolic execution along a concrete execution path, but unlike concolic testing PathCrawler does not simplify complex symbolic constraints using concrete values. These tools (DART and CUTE, EXE) applied concolic testing to unit testing of C programs and concolic testing was originally conceived as a white box improvement upon established random testing methodologies. The technique was later generalized to testing multithreaded Java programs with jCUTE, and unit testing programs from their executable codes (tool OSMOSE). It was also combined with fuzz testing and extended to detect exploitable security issues in large-scale x86 binaries by Microsoft Research's SAGE.
The concolic approach is also applicable to model checking. In a concolic model checker, the model checker traverses states of the model representing the software being checked, while storing both a concrete state and a symbolic state. The symbolic state is used for checking properties on the software, while the concrete state is used to avoid reaching unreachable states. One such tool is ExpliSAT by Sharon Barner, Cindy Eisner, Ziv Glazberg, Daniel Kroening and Ishai Rabinovitz

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

- Wikipedia: https://en.wikipedia.org/wiki/Concolic_testing