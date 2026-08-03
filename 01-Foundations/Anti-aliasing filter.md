---
title: "Anti-aliasing filter"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Anti-aliasing_filter"
wikipedia_categories: ["Anti-aliasing", "Digital signal processing", "Electronic filter applications", "Linear filters"]
related: ["[[Reconstruction filter]]", "[[All-pass filter]]", "[[Filter bank]]", "[[Lattice delay network]]", "[[Polyphase quadrature filter]]", "[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]"]
---

# Anti-aliasing filter

An anti-aliasing filter (AAF) is a filter used before a signal sampler to restrict the bandwidth of a signal to satisfy the Nyquist–Shannon sampling theorem over the band of interest. Since the theorem states that unambiguous reconstruction of the signal from its samples is possible when the power of frequencies above the Nyquist frequency is zero, a brick wall filter is an idealized but impractical AAF. A practical AAF makes a trade off between reduced bandwidth and increased aliasing. A practical anti-aliasing filter will typically permit some aliasing to occur or attenuate or otherwise distort some in-band frequencies close to the Nyquist limit. For this reason, many practical systems sample higher than would be theoretically required by a perfect AAF in order to ensure that all frequencies of interest can be reconstructed, a practice called oversampling.

## Related

- [[Reconstruction filter]]
- [[All-pass filter]]
- [[Filter bank]]
- [[Lattice delay network]]
- [[Polyphase quadrature filter]]
- [[2D adaptive filters]]
- [[2D Z-transform]]
- [[Adaptive equalizer]]
- [[Adaptive filter]]
- [[Adaptive predictive coding]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Anti-aliasing_filter