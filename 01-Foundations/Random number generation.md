---
title: "Random number generation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Random_number_generation"
wikipedia_categories: ["Information theory", "Random number generation"]
related: ["[[Entropy estimation]]", "[[3G MIMO]]", "[[A Mathematical Theory of Communication]]", "[[A Symbolic Analysis of Relay and Switching Circuits]]", "[[Adjusted mutual information]]", "[[Algorithmic information theory]]", "[[Ascendency]]", "[[Asymptotic equipartition property]]", "[[Bach's algorithm]]", "[[Bandwidth (computing)]]"]
---

# Random number generation

Random number generation is a process by which, often by means of a random number generator (RNG), a sequence of numbers or symbols is generated that cannot be reasonably predicted better than by random chance. This means that the particular outcome sequence will contain some patterns detectable in hindsight but impossible to foresee. True random number generators can be hardware random-number generators (HRNGs), wherein each generation is a function of the current value of a physical environment's attribute that is constantly changing in a manner that is practically impossible to model. This would be in contrast to so-called random number generations done by pseudorandom number generators (PRNGs), which generate pseudorandom numbers that are in fact predetermined—these numbers can be reproduced simply by knowing the initial state of the PRNG and the method it uses to generate numbers. There is also a class of non-physical true random number generators (NPTRNG) that produce true random numbers without an access to a dedicated hardware source, by scavenging entropy that is present in the computer system. See the details in True vs. pseudo-random numbers.
Various applications of randomness have led to the development of different methods for generating random data. Some of these have existed since ancient times, including well-known examples like the rolling of dice, coin flipping, the shuffling of playing cards, the use of yarrow stalks (for divination) in the I Ching, as well as countless other techniques. Because of the mechanical nature of these techniques, generating large quantities of sufficiently random numbers (important in statistics) required much work and time. Thus, results would sometimes be collected and distributed as random number tables.
Several computational methods for pseudorandom number generation exist. All fall short of the goal of true randomness, although they may meet, with varying success, some of the statistical tests for randomness intended to measure how unpredictable their results are (that is, to what degree their patterns are discernible). This generally makes them unusable for applications such as cryptography. However, carefully designed cryptographically secure pseudorandom number generators (CSPRNGS) also exist, with special features specifically designed for use in cryptography.

## Related

- [[Entropy estimation]]
- [[3G MIMO]]
- [[A Mathematical Theory of Communication]]
- [[A Symbolic Analysis of Relay and Switching Circuits]]
- [[Adjusted mutual information]]
- [[Algorithmic information theory]]
- [[Ascendency]]
- [[Asymptotic equipartition property]]
- [[Bach's algorithm]]
- [[Bandwidth (computing)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Random_number_generation