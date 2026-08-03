---
title: "Online codes"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Online_codes"
wikipedia_categories: ["Coding theory"]
related: ["[[Algebraic geometry code]]", "[[Alternant code]]", "[[Arbitrarily varying channel]]", "[[Bar product]]", "[[Barker code]]", "[[BCH code]]", "[[Belief propagation]]", "[[Berger code]]", "[[Berlekamp switching game]]", "[[Berlekamp–Welch algorithm]]"]
---

# Online codes

In computer science, online codes are an example of rateless erasure codes. These codes can encode a message into a number of symbols such that knowledge of any fraction of them allows one to recover the original message (with high probability). Rateless codes produce an arbitrarily large number of symbols which can be broadcast until the receivers have enough symbols.

The online encoding algorithm consists of several phases. First the message is split into n fixed size message blocks. Then the outer encoding is an erasure code which produces auxiliary blocks that are appended to the message blocks to form a composite message.
From this the inner encoding generates check blocks. Upon receiving a certain number of check blocks some fraction of the composite message can be recovered. Once enough has been recovered the outer decoding can be used to recover the original message.

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

- Wikipedia: https://en.wikipedia.org/wiki/Online_codes