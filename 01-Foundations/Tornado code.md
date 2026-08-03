---
title: "Tornado code"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Tornado_code"
wikipedia_categories: ["Capacity-approaching codes", "Coding theory"]
related: ["[[Expander code]]", "[[Fountain code]]", "[[Low-density parity-check code]]", "[[Polar code (coding theory)]]", "[[Algebraic geometry code]]", "[[Alternant code]]", "[[Arbitrarily varying channel]]", "[[Bar product]]", "[[Barker code]]", "[[BCH code]]"]
---

# Tornado code

In coding theory, Tornado codes are a class of erasure codes that support error correction.  Tornado codes require a constant C more redundant blocks than the more data-efficient Reed–Solomon erasure codes, but are much faster to generate and can fix erasures faster.  Software-based implementations of tornado codes are about 100 times faster on small lengths and about 10,000 times faster on larger lengths than Reed–Solomon erasure codes. Since the introduction of Tornado codes, many other similar erasure codes have emerged, most notably Online codes, LT codes and Raptor codes.
Tornado codes use a layered approach.  All layers except the last use an LDPC error correction code, which is fast but has a chance of failure.  The final layer uses a Reed–Solomon correction code, which is slower but is optimal in terms of failure recovery.  Tornado codes dictates how many levels, how many recovery blocks in each level, and the distribution used to generate blocks for the non-final layers.

## Related

- [[Expander code]]
- [[Fountain code]]
- [[Low-density parity-check code]]
- [[Polar code (coding theory)]]
- [[Algebraic geometry code]]
- [[Alternant code]]
- [[Arbitrarily varying channel]]
- [[Bar product]]
- [[Barker code]]
- [[BCH code]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Tornado_code