---
title: "Channelizer"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Channelizer"
wikipedia_categories: ["Digital signal processing", "Electronics stubs"]
related: ["[[Differential nonlinearity]]", "[[DSSP (imaging)]]", "[[Integral nonlinearity]]", "[[Lapped transform]]", "[[Spurious-free dynamic range]]", "[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]"]
---

# Channelizer

In digital signal processing,  a channelizer is a device or algorithm that takes a generally wideband signal as an input and produces two or more narrowband output signals that each contains a frequency sub-band of the input signal.  The output signals are called either channels, bands, or sub-bands.  The bandwidth of each output signal is narrower than that of the input signal.  As a result, the output signals typically have lower sampling rates than the sampling rate of the input signal. 
A channelizer is a type of Filter bank.
Channelizers are often used in algorithms that process each channel in a different way and then recombine the channels to achieve a desired effect.  The resulting effect is frequency dependent.  A common example is an electronic equalizer.
One of the most common methods for selecting a channel from an input signal is to first shift the frequency by multiplying it with a complex sinusoid, then passing the signal through a low pass filter. Alternatively, a decimator (rate changer) can be used. One common type of channelizer is the polyphase channelizer.

## Related

- [[Differential nonlinearity]]
- [[DSSP (imaging)]]
- [[Integral nonlinearity]]
- [[Lapped transform]]
- [[Spurious-free dynamic range]]
- [[2D adaptive filters]]
- [[2D Z-transform]]
- [[Adaptive equalizer]]
- [[Adaptive filter]]
- [[Adaptive predictive coding]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Channelizer