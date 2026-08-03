---
title: "Waveform buffer"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Waveform_buffer"
wikipedia_categories: ["Digital signal processing"]
related: ["[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adaptive-additive algorithm]]", "[[Adjoint filter]]", "[[Advanced process control]]", "[[Aliasing]]", "[[All-pass filter]]"]
---

# Waveform buffer

In computing, a waveform buffer is a technique for digital synthesis of repeating waveforms. It is common in PC sound cards.
The waveform amplitude values are stored in a buffer memory, which is addressed from a phase generator, with the retrieved value then used as the basis of the synthesized signal. In the phase generator, a value proportional to the desired signal frequence is periodically added to an accumulator. The high order bits of the accumulator form the output address, while the typically larger number of bits in the accumulator and addition value results in an arbitrarily high frequency resolution.

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

- Wikipedia: https://en.wikipedia.org/wiki/Waveform_buffer