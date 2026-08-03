---
title: "Group testing"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Group_testing"
wikipedia_categories: ["Combinatorics", "Design of experiments"]
related: ["[[All-pairs testing]]", "[[Block design]]", "[[Orthogonal array]]", "[[Weighing matrix]]", "[[3-dimensional matching]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Addition principle]]", "[[Algorithmic Lovász local lemma]]", "[[Algorithms and Combinatorics]]", "[[Alignments of random points]]"]
---

# Group testing

In statistics and combinatorial mathematics, group testing is any procedure that breaks up the task of identifying objects into tests on groups of items, rather than testing each item individually. First studied by Robert Dorfman in 1943, group testing is a relatively new field of mathematics that can be applied to a wide range of practical applications and is an active area of research today.
A familiar example of group testing involves a string of light bulbs connected in series, where exactly one of the bulbs is known to be broken. The objective is to find the broken bulb using the smallest number of tests (where a test is when some of the bulbs are connected to a power supply). A simple approach is to test each bulb individually. However, when there are a large number of bulbs it would be much more efficient to pool the bulbs into groups. For example, by connecting the first half of the bulbs at once, it can be determined which half the broken bulb is in, ruling out half of the bulbs in just one test.
Schemes for carrying out group testing can be simple or complex and the tests involved at each stage may be different. Schemes in which the tests for the next stage depend on the results of the previous stages are called adaptive procedures, while schemes designed so that all the tests are known beforehand are called non-adaptive procedures. The structure of the scheme of the tests involved in a non-adaptive procedure is known as a pooling design.
Group testing has many applications, including statistics, biology, computer science, medicine, engineering and cyber security. Modern interest in these testing schemes has been rekindled by the Human Genome Project.

## Related

- [[All-pairs testing]]
- [[Block design]]
- [[Orthogonal array]]
- [[Weighing matrix]]
- [[3-dimensional matching]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Addition principle]]
- [[Algorithmic Lovász local lemma]]
- [[Algorithms and Combinatorics]]
- [[Alignments of random points]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Group_testing