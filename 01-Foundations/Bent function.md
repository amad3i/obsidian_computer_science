---
title: "Bent function"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Bent_function"
wikipedia_categories: ["Boolean algebra", "Combinatorics", "Symmetric-key cryptography", "Theory of cryptography"]
related: ["[[1-in-3-SAT]]", "[[3-dimensional matching]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Addition principle]]", "[[Algorithmic Lovász local lemma]]", "[[Algorithms and Combinatorics]]", "[[Alignments of random points]]", "[[All-pairs testing]]", "[[Analysis of Boolean functions]]", "[[AND gate]]"]
---

# Bent function

In the mathematical field of combinatorics, a bent function is a Boolean function that is maximally non-linear; it is as different as possible from the set of all linear and affine functions when measured by Hamming distance between truth tables. Concretely, this means the maximum correlation between the output of the function and a linear function is minimal. In addition, the derivatives of a bent function are balanced Boolean functions, so for any change in the input variables there is a 50 percent chance that the output value will change. 
The maximal nonlinearity means approximating a bent function by an affine (linear) function is hard, a useful property in the defence against linear cryptanalysis. In addition, detecting a change in the output of the function yields no information about what change occurred in the inputs, making the function immune to differential cryptanalysis.
Bent functions were defined and named in the 1960s by Oscar Rothaus in research not published until 1976. They have been extensively studied for their applications in cryptography, but have also been applied to spread spectrum, coding theory, and combinatorial design. The definition can be extended in several ways, leading to different classes of generalized bent functions that share many of the useful properties of the original.
It is known that V. A. Eliseev and O. P. Stepchenkov studied bent functions, which they called minimal functions, in the USSR in 1962. However, their results have still not been declassified.
Bent functions are also known as perfectly nonlinear (PN) Boolean functions. Certain functions that are as close as possible to perfect nonlinearity (e.g. for functions of an odd number of bits, or vectorial functions) are known as almost perfectly nonlinear (APN).

## Related

- [[1-in-3-SAT]]
- [[3-dimensional matching]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Addition principle]]
- [[Algorithmic Lovász local lemma]]
- [[Algorithms and Combinatorics]]
- [[Alignments of random points]]
- [[All-pairs testing]]
- [[Analysis of Boolean functions]]
- [[AND gate]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bent_function