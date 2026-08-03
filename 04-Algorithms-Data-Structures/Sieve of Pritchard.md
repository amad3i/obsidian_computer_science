---
title: "Sieve of Pritchard"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Sieve_of_Pritchard"
wikipedia_categories: ["Algorithms", "Primality tests", "Sieve theory"]
related: ["[[Sieve of Eratosthenes]]", "[[Adaptive algorithm]]", "[[Algorism]]", "[[Algorithm]]", "[[Algorithm characterizations]]", "[[Algorithm engineering]]", "[[Algorithm IMED]]", "[[Algorithmic amplification]]", "[[Algorithmic logic]]", "[[Algorithmic management]]"]
---

# Sieve of Pritchard

In mathematics, the sieve of Pritchard is an algorithm for finding all prime numbers up to a specified bound.
Like the ancient sieve of Eratosthenes, it has a simple conceptual basis in number theory.
It is especially suited to quick hand computation for small bounds.
Whereas the sieve of Eratosthenes marks off each non-prime for each of its prime factors, the sieve of Pritchard avoids considering almost all non-prime numbers by building progressively larger wheels, which represent the pattern of numbers not divisible by any of the primes processed thus far.
It thereby achieves a better asymptotic complexity, and was the first sieve with a running time sublinear in the specified bound.
Its asymptotic running-time has not been improved on, and it deletes fewer composites than any other known sieve.
It was created in 1979 by Paul Pritchard.
Since Pritchard has created a number of other sieve algorithms for finding prime numbers, the sieve of Pritchard is sometimes singled out by being called the wheel sieve (by Pritchard himself) or the dynamic wheel sieve.

## Related

- [[Sieve of Eratosthenes]]
- [[Adaptive algorithm]]
- [[Algorism]]
- [[Algorithm]]
- [[Algorithm characterizations]]
- [[Algorithm engineering]]
- [[Algorithm IMED]]
- [[Algorithmic amplification]]
- [[Algorithmic logic]]
- [[Algorithmic management]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sieve_of_Pritchard