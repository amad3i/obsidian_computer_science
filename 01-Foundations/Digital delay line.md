---
title: "Digital delay line"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Digital_delay_line"
wikipedia_categories: ["Audio effects", "Digital signal processing"]
related: ["[[Audio normalization]]", "[[Dattorro industry scheme]]", "[[Dereverberation]]", "[[Outboard gear]]", "[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adaptive-additive algorithm]]"]
---

# Digital delay line

A digital delay line (or simply delay line, also called delay filter) is a discrete element in a digital filter that allows a signal to be delayed by a number of samples. Delay lines are commonly used to delay audio signals feeding loudspeakers to compensate for the speed of sound in air, and to align video signals with accompanying audio, called audio-to-video synchronization. Delay lines may compensate for electronic processing latency so that multiple signals leave a device simultaneously despite having different pathways. 
Digital delay lines are widely used building blocks in methods to simulate room acoustics, musical instruments and effects units. Digital waveguide synthesis shows how digital delay lines can be used as sound synthesis methods for various musical instruments such as string instruments and wind instruments. 
If a delay line holds a non-integer value smaller than one, it results in a fractional delay line (also called interpolated delay line or fractional delay filter). A series of an integer delay line and a fractional delay filter is commonly used for modelling arbitrary delay filters in digital signal processing. The Dattorro scheme is an industry standard implementation of digital filters using fractional delay lines.

## Related

- [[Audio normalization]]
- [[Dattorro industry scheme]]
- [[Dereverberation]]
- [[Outboard gear]]
- [[2D adaptive filters]]
- [[2D Z-transform]]
- [[Adaptive equalizer]]
- [[Adaptive filter]]
- [[Adaptive predictive coding]]
- [[Adaptive-additive algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Digital_delay_line