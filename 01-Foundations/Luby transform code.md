---
title: "Luby transform code"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Luby_transform_code"
wikipedia_categories: ["Coding theory"]
related: ["[[Algebraic geometry code]]", "[[Alternant code]]", "[[Arbitrarily varying channel]]", "[[Bar product]]", "[[Barker code]]", "[[BCH code]]", "[[Belief propagation]]", "[[Berger code]]", "[[Berlekamp switching game]]", "[[Berlekamp–Welch algorithm]]"]
---

# Luby transform code

In computer science, Luby transform codes (LT codes) are the first class of practical fountain codes that are near-optimal erasure correcting codes. They were invented by Michael Luby in 1998 and published in 2002. Like some other fountain codes, LT codes depend on sparse bipartite graphs to trade reception overhead for encoding and decoding speed. The distinguishing characteristic of LT codes is in employing a particularly simple algorithm based on the exclusive or operation (
  
    
      
        ⊕
      
    
    
  
) to encode and decode the message.
LT codes are rateless because the encoding algorithm can in principle produce an infinite number of message packets (i.e., the percentage of packets that must be received to decode the message can be arbitrarily small). They are erasure correcting codes because they can be used to transmit digital data reliably on an erasure channel.
The next generation beyond LT codes are Raptor codes (see for example IETF RFC 5053 or IETF RFC 6330), which have linear time encoding and decoding.  Raptor codes are fundamentally based on LT codes, i.e., encoding for Raptor codes uses two encoding stages, where the second stage is LT encoding.  Similarly, decoding with Raptor codes primarily relies upon LT decoding, but LT decoding is intermixed with more advanced decoding techniques. The RaptorQ code specified in IETF RFC 6330, which is the most advanced fountain code, has vastly superior decoding probabilities and performance compared to using only an LT code.

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

- Wikipedia: https://en.wikipedia.org/wiki/Luby_transform_code