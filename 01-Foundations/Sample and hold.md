---
title: "Sample and hold"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Sample_and_hold"
wikipedia_categories: ["Digital signal processing", "Electronic circuits"]
related: ["[[Analog-to-digital converter]]", "[[Digital-to-analog converter]]", "[[Time-interleaved ADC]]", "[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adaptive-additive algorithm]]", "[[Adjoint filter]]"]
---

# Sample and hold

In electronics, a sample and hold (also known as sample and follow) circuit is an analog device that samples (captures, takes) the voltage of a continuously varying analog signal and holds (locks, freezes) its value at a constant level for a specified minimum period of time. Sample and hold circuits and related peak detectors are the elementary analog memory devices. They are typically used in analog-to-digital converters to eliminate variations in input signal that can corrupt the conversion process. They are also used in electronic music, for instance to impart a random quality to successively-played notes.
A typical sample and hold circuit stores electric charge in a capacitor and contains at least one switching device such as a FET (field effect transistor) switch and normally one operational amplifier. To sample the input signal, the switch connects the capacitor to the output of a buffer amplifier. The buffer amplifier charges or discharges the capacitor so that the voltage across the capacitor is practically equal, or proportional to, input voltage. In hold mode, the switch disconnects the capacitor from the buffer. The capacitor is invariably discharged by its own leakage currents and useful load currents, which makes the circuit inherently volatile, but the loss of voltage (voltage drop) within a specified hold time remains within an acceptable error margin for all but the most demanding applications.

## Related

- [[Analog-to-digital converter]]
- [[Digital-to-analog converter]]
- [[Time-interleaved ADC]]
- [[2D adaptive filters]]
- [[2D Z-transform]]
- [[Adaptive equalizer]]
- [[Adaptive filter]]
- [[Adaptive predictive coding]]
- [[Adaptive-additive algorithm]]
- [[Adjoint filter]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sample_and_hold