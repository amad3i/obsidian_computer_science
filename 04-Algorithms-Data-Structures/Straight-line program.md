---
title: "Straight-line program"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Straight-line_program"
wikipedia_categories: ["Computational complexity theory", "Group theory"]
related: ["[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Absolutely convex set]]", "[[Advice (complexity)]]", "[[Analysis of algorithms]]", "[[Approximation algorithm]]", "[[Arithmetic group]]", "[[Asymptotic computational complexity]]", "[[Averaging argument]]", "[[Bernstein–Vazirani algorithm]]", "[[Best, worst and average case]]"]
---

# Straight-line program

In computer science, a straight-line program is, informally, a program that does not contain any loop or any test, and is formed by a sequence of steps that apply each an operation to previously computed elements.
This article is devoted to the case where the allowed operations are the operations of a group, that is multiplication and inversion. More specifically a straight-line program (SLP) for a finite group G = ⟨S⟩ is a finite sequence L of elements of G such that every element of L either belongs to S, is the inverse of a preceding element, or the product of two preceding elements. An SLP L is said to compute a group element g ∈ G if g ∈ L, where g is encoded by a word in S and its inverses.
Intuitively, an SLP computing some g ∈ G is  an efficient way of storing g as a group word over S; observe that if g is constructed in i steps, the word length of g may be exponential in i, but the length of the corresponding SLP is linear in i. This has important applications in computational group theory, by using SLPs to efficiently encode group elements as words over a given generating set.
Straight-line programs were introduced by Babai and Szemerédi in 1984 as a tool for studying the computational complexity of certain matrix group properties. Babai and Szemerédi prove that every element of a finite group G has an SLP of length O(log2|G|) in every generating set.
An efficient solution to the constructive membership problem is crucial to many group-theoretic algorithms. It can be stated in terms of SLPs as follows. Given a finite group G = ⟨S⟩ and g ∈ G, find a straight-line program computing g over S. The constructive membership problem is often studied in the setting of black box groups. The elements are encoded by bit strings of a fixed length.  Three oracles are provided for the group-theoretic functions of multiplication, inversion, and checking for equality with the identity. A black box algorithm is one which uses only these oracles. Hence, straight-line programs for black box groups are black box algorithms.
Explicit straight-line programs are given for a wealth of finite simple groups in the online ATLAS of Finite Groups.

## Related

- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Absolutely convex set]]
- [[Advice (complexity)]]
- [[Analysis of algorithms]]
- [[Approximation algorithm]]
- [[Arithmetic group]]
- [[Asymptotic computational complexity]]
- [[Averaging argument]]
- [[Bernstein–Vazirani algorithm]]
- [[Best, worst and average case]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Straight-line_program