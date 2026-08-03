---
title: "Fountain code"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Fountain_code"
wikipedia_categories: ["Capacity-approaching codes", "Coding theory"]
related: ["[[Expander code]]", "[[Low-density parity-check code]]", "[[Polar code (coding theory)]]", "[[Tornado code]]", "[[Algebraic geometry code]]", "[[Alternant code]]", "[[Arbitrarily varying channel]]", "[[Bar product]]", "[[Barker code]]", "[[BCH code]]"]
---

# Fountain code

In coding theory, fountain codes (also known as rateless erasure codes) are a class of erasure codes with the property that a potentially limitless sequence of encoding symbols can be generated from a given set of source symbols such that the original source symbols can ideally be recovered from any subset of the encoding symbols of size equal to or only slightly larger than the number of source symbols. The term fountain or rateless refers to the fact that these codes do not exhibit a fixed code rate.
A fountain code is optimal if the original k source symbols can be recovered from any k successfully received encoding symbols (i.e., excluding those that were erased). Fountain codes are known that have efficient encoding and decoding algorithms and that allow the recovery of the original k source symbols from any k’ of the encoding symbols with high probability, where k’ is just slightly larger than k.
LT codes were the first practical realization of fountain codes. Raptor codes and online codes were subsequently introduced, and achieve linear time encoding and decoding complexity through a pre-coding stage of the input symbols. Triangular network coding achieve linear encoding and decoding using non-linear encoding, and decoding using the back-substitution method.

## Related

- [[Expander code]]
- [[Low-density parity-check code]]
- [[Polar code (coding theory)]]
- [[Tornado code]]
- [[Algebraic geometry code]]
- [[Alternant code]]
- [[Arbitrarily varying channel]]
- [[Bar product]]
- [[Barker code]]
- [[BCH code]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fountain_code