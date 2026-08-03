---
title: "Cascaded integrator–comb filter"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Cascaded_integrator–comb_filter"
wikipedia_categories: ["Digital signal processing"]
related: ["[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adaptive-additive algorithm]]", "[[Adjoint filter]]", "[[Advanced process control]]", "[[Aliasing]]", "[[All-pass filter]]"]
---

# Cascaded integrator–comb filter

In digital signal processing, a cascaded integrator–comb (CIC) is a computationally efficient class of low-pass finite impulse response (FIR) filter that chains N number of integrator and comb filter pairs (where N is the filter's order) to form a decimator or interpolator. In a decimating CIC, the input signal is first fed through N integrator stages, followed by a down-sampler, and then N comb stages. An interpolating CIC (e.g. Figure 1) has the reverse order of this architecture, but with the down-sampler replaced with a zero-stuffer (up-sampler).

## Related

- [[2D adaptive filters]]
- [[2D Z-transform]]
- [[Adaptive equalizer]]
- [[Adaptive filter]]
- [[Adaptive predictive coding]]
- [[Adaptive-additive algorithm]]
- [[Adjoint filter]]
- [[Advanced process control]]
- [[Aliasing]]
- [[All-pass filter]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Cascaded_integrator–comb_filter