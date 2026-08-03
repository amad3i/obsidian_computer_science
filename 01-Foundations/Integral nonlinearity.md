---
title: "Integral nonlinearity"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Integral_nonlinearity"
wikipedia_categories: ["Digital signal processing", "Electronics stubs"]
related: ["[[Channelizer]]", "[[Differential nonlinearity]]", "[[DSSP (imaging)]]", "[[Lapped transform]]", "[[Spurious-free dynamic range]]", "[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]"]
---

# Integral nonlinearity

Integral nonlinearity (acronym INL) is a commonly used measure of performance in digital-to-analog (DAC) and analog-to-digital (ADC) converters. In DACs, it is a measure of the deviation between the ideal output value and the actual measured output value for a certain input code. In ADCs, it is the deviation between the ideal input threshold value and the measured threshold level of a certain output code. This measurement is performed after offset and gain errors have been compensated.
The ideal transfer function of a DAC or ADC is a straight line. The INL measurement depends on what line is chosen as ideal. One common option is the line that connects the endpoints of the transfer function, in other words, the line connecting the smallest and largest measured input/output value. An alternative is to use a best fit line, where one minimizes the average (or alternatively the mean squared) INL.
While the INL can be measured for every possible input/output code, often only the maximal error is provided when reporting the INL of a converter.

## Related

- [[Channelizer]]
- [[Differential nonlinearity]]
- [[DSSP (imaging)]]
- [[Lapped transform]]
- [[Spurious-free dynamic range]]
- [[2D adaptive filters]]
- [[2D Z-transform]]
- [[Adaptive equalizer]]
- [[Adaptive filter]]
- [[Adaptive predictive coding]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Integral_nonlinearity