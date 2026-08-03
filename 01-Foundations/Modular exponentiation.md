---
title: "Modular exponentiation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Modular_exponentiation"
wikipedia_categories: ["Cryptographic algorithms", "Modular arithmetic", "Number theoretic algorithms"]
related: ["[[Generation of primes]]", "[[Kochanski multiplication]]", "[[Montgomery modular multiplication]]", "[[Automorphic number]]", "[[B92 protocol]]", "[[Bach's algorithm]]", "[[BB84]]", "[[Beaufort cipher]]", "[[Berlekamp–Rabin algorithm]]", "[[Block cipher mode of operation]]"]
---

# Modular exponentiation

Modular exponentiation is exponentiation performed over a modulus. It is useful in computer science, especially in the field of public-key cryptography, where it is used in both Diffie–Hellman key exchange and RSA public/private keys.
Modular exponentiation is the remainder c when an integer b (the base) is raised to the power e (the exponent), and divided by a positive integer m (the modulus); that is, c = be mod m. From the definition of division, it follows that 0 ≤ c < m.
For example, given b = 5, e = 3 and m = 13, dividing 53 = 125 by 13 leaves a remainder of c = 8.
When b and m are relatively prime, one can also allow the exponent e to be negative by finding the multiplicative inverse d of b modulo m (for instance by using extended Euclidean algorithm). More precisely:

c = be mod m = d−e mod m, where e < 0 and b ⋅ d ≡ 1 (mod m).
Modular exponentiation is efficient to compute, even for very large integers.  On the other hand, computing the modular discrete logarithm – that is, finding the exponent e when given b, c, and m – is believed to be difficult. This one-way function behavior makes modular exponentiation a candidate for use in cryptographic algorithms.

## Related

- [[Generation of primes]]
- [[Kochanski multiplication]]
- [[Montgomery modular multiplication]]
- [[Automorphic number]]
- [[B92 protocol]]
- [[Bach's algorithm]]
- [[BB84]]
- [[Beaufort cipher]]
- [[Berlekamp–Rabin algorithm]]
- [[Block cipher mode of operation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Modular_exponentiation