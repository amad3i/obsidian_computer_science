---
title: "Raptor code"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Raptor_code"
wikipedia_categories: ["Coding theory"]
related: ["[[Algebraic geometry code]]", "[[Alternant code]]", "[[Arbitrarily varying channel]]", "[[Bar product]]", "[[Barker code]]", "[[BCH code]]", "[[Belief propagation]]", "[[Berger code]]", "[[Berlekamp switching game]]", "[[Berlekamp–Welch algorithm]]"]
---

# Raptor code

In computer science, Raptor codes (rapid tornado; see Tornado codes) are the first known class of fountain codes with linear time encoding and decoding. They were invented by Amin Shokrollahi in 2000/2001 and were first published in 2004 as an extended abstract. Raptor codes are a significant theoretical and practical improvement over LT codes, which were the first practical class of fountain codes.
Raptor codes, as with fountain codes in general, encode a given source block of data consisting of a number k of equal size source symbols into a potentially limitless sequence of encoding symbols such that reception of any k or more encoding symbols allows the source block to be recovered with some non-zero probability. The probability that the source block can be recovered increases with the number of encoding symbols received above k becoming very close to 1, once the number of received encoding symbols is only very slightly larger than k. For example, with the latest generation of Raptor codes, the RaptorQ codes, the chance of decoding failure when k encoding symbols have been received is less than 1%, and the chance of decoding failure when k+2 encoding symbols have been received is less than one in a million. A symbol can be any size, from a single byte to hundreds or thousands of bytes.
Raptor codes may be systematic or non-systematic. In the systematic case, the symbols of the original source block, i.e. the source symbols, are included within the set of encoding symbols. Some examples of a systematic Raptor code is the use by the 3rd Generation Partnership Project in mobile cellular wireless broadcasting and multicasting, and also by DVB-H standards for IP datacast to handheld devices. The Raptor codes used in these standards is also defined in IETF RFC 5053.
Online codes are an example of a non-systematic fountain code.

## Related

- [[Algebraic geometry code]]
- [[Alternant code]]
- [[Arbitrarily varying channel]]
- [[Bar product]]
- [[Barker code]]
- [[BCH code]]
- [[Belief propagation]]
- [[Berger code]]
- [[Berlekamp switching game]]
- [[Berlekamp–Welch algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Raptor_code