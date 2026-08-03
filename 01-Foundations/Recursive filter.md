---
title: "Recursive filter"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Recursive_filter"
wikipedia_categories: ["Signal processing", "Signal processing stubs"]
related: ["[[Adjacent channel power ratio]]", "[[Audio leveler]]", "[[Bandwidth expansion]]", "[[Constant amplitude zero autocorrelation waveform]]", "[[Cross-recurrence quantification]]", "[[Decorrelation]]", "[[Delay equalization]]", "[[Direction of arrival]]", "[[Echo removal]]", "[[Fast folding algorithm]]"]
---

# Recursive filter

In signal processing, a recursive filter (also called an infinite impulse response filter) is a type of filter which reuses one or more of its outputs as an input.
They allow a system to respond over a long period of time to a brief input signal, without needing to perform complex calculations on every past input.
This feedback typically results in an unending impulse response, characterized by either exponentially growing, decaying, or sinusoidal signal output components.
However, a recursive filter does not always have an infinite impulse response. Some implementations of moving average filter are recursive filters but with a finite impulse response.
Non-recursive Filter Example:
y[n] = 0.5x[n − 1] + 0.5x[n].
Recursive Filter Example:
y[n] = 0.5y[n − 1] + 0.5x[n].

## Related

- [[Adjacent channel power ratio]]
- [[Audio leveler]]
- [[Bandwidth expansion]]
- [[Constant amplitude zero autocorrelation waveform]]
- [[Cross-recurrence quantification]]
- [[Decorrelation]]
- [[Delay equalization]]
- [[Direction of arrival]]
- [[Echo removal]]
- [[Fast folding algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Recursive_filter