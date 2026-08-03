---
title: "B, C, K, W system"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/B,_C,_K,_W_system"
wikipedia_categories: ["Combinatory logic", "Lambda calculus"]
related: ["[[Applicative computing systems]]", "[[Combinatory logic]]", "[[Fixed-point combinator]]", "[[SKI combinator calculus]]", "[[Anonymous function]]", "[[Beta normal form]]", "[[Böhm tree]]", "[[Calculus of constructions]]", "[[Call-by-push-value]]", "[[Cartesian closed category]]"]
---

# B, C, K, W system

The B, C, K, W system is a variant of combinatory logic that takes as primitive the combinators B, C, K, and W. This system was discovered by Haskell Curry in his doctoral thesis Grundlagen der kombinatorischen Logik, whose results are set out in Curry (1930). 
It has expressive power equivalent to that of S, K, I system. Both systems are fully interchangeable. 
When compiling to combinators, an implementation may equally choose one system or the other, or both, as it helps shorten the encodings of functions. For example, the encodings of C exclusively in terms of S,K,I, as well as of S in B,C,W,K are long and complicated, as can be seen below, while their corresponding computational machine implementations are equally trivial. It can be worth it adding the additional interpretation rules, allowing for the resulting much shorter code which can lead to more efficient execution.

## Related

- [[Applicative computing systems]]
- [[Combinatory logic]]
- [[Fixed-point combinator]]
- [[SKI combinator calculus]]
- [[Anonymous function]]
- [[Beta normal form]]
- [[Böhm tree]]
- [[Calculus of constructions]]
- [[Call-by-push-value]]
- [[Cartesian closed category]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/B,_C,_K,_W_system