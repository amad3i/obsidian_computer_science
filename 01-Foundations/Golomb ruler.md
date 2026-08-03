---
title: "Golomb ruler"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Golomb_ruler"
wikipedia_categories: ["Antennas (radio)", "Distributed computing projects", "Length, distance, or range measuring devices", "Number theory"]
related: ["[[Sparse ruler]]", "[[3x + 1 semigroup]]", "[[Abc conjecture]]", "[[Abel's summation formula]]", "[[Algebraic number theory]]", "[[Amenable number]]", "[[Amicable triple]]", "[[An Introduction to the Theory of Numbers]]", "[[Arithmetic derivative]]", "[[Arithmetic group]]"]
---

# Golomb ruler

In mathematics, a Golomb ruler is a set of marks at integer positions along a ruler such that no two pairs of marks are the same distance apart. The number of marks on the ruler is its order, and the largest distance between two of its marks is its length. Translation and reflection of a Golomb ruler are considered trivial, so the smallest mark is customarily put at 0 and the next mark at the smaller of its two possible values. Golomb rulers can be viewed as a one-dimensional special case of Costas arrays.
The Golomb ruler was named for Solomon W. Golomb and discovered independently by Sidon (1932) and Babcock (1953). Sophie Piccard also published early research on these sets, in 1939, stating as a theorem the claim that two Golomb rulers with the same distance set must be congruent. This turned out to be false for six-point rulers, but true otherwise.
There is no requirement that a Golomb ruler be able to measure all distances up to its length, but if it does, it is called a perfect Golomb ruler. It has been proved that no perfect Golomb ruler exists for five or more marks. A Golomb ruler is optimal if no shorter Golomb ruler of the same order exists. Creating Golomb rulers is easy, but proving the optimal Golomb ruler (or rulers) for a specified order is computationally very challenging.
Distributed.net has completed distributed massively parallel searches for optimal order-24 through order-28 Golomb rulers, each time confirming the suspected candidate ruler.
Currently, the complexity of finding optimal Golomb rulers (OGRs) of arbitrary order n (where n is given in unary) is unknown. In the past there was some speculation that it is an NP-hard problem. Problems related to the construction of Golomb rulers are provably shown to be NP-hard, where it is also noted that no known NP-complete problem has similar flavor to finding Golomb rulers.
Golomb rulers have practical applications in information theory and error correction, radio frequency selection and antenna placement, as well as current transformers.

## Related

- [[Sparse ruler]]
- [[3x + 1 semigroup]]
- [[Abc conjecture]]
- [[Abel's summation formula]]
- [[Algebraic number theory]]
- [[Amenable number]]
- [[Amicable triple]]
- [[An Introduction to the Theory of Numbers]]
- [[Arithmetic derivative]]
- [[Arithmetic group]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Golomb_ruler