---
title: "Fluctuation loss"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Fluctuation_loss"
wikipedia_categories: ["Radar", "Signal processing"]
related: ["[[Array factor]]", "[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Air traffic control]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]", "[[Analog signal processing]]", "[[Analytic signal]]", "[[Angle of arrival]]"]
---

# Fluctuation loss

Fluctuation loss is an effect seen in radar systems as the target object moves or changes its orientation relative to the radar system. It was extensively studied during the 1950s by Peter Swerling, who introduced the Swerling models to allow the effect to be simulated. For this reason, it is sometimes known as Swerling loss or similar names.
The effect occurs when the target's physical size is within a key range of values relative to the wavelength of the radar signal. As the signal reflects off various parts of the target, they may interfere as they return to the radar receiver. At any single distance from the station, this will cause the signal to be amplified or diminished compared to the baseline signal one calculates from the radar equation. As the target moves, these patterns change. This causes the signal to fluctuate in strength and may cause it to disappear entirely at certain times.
The effect can be reduced or eliminated by operating on more than one frequency or using modulation techniques like pulse compression that change the frequency over the period of a pulse. In these cases, it is unlikely that the pattern of reflections from the target causes the same destructive interference at two different frequencies.
Swerling modeled these effects in a famous 1954 paper introduced while working at RAND Corporation. Swerling's models considered the contribution of multiple small reflectors, or many small reflectors and a single large one. This offered the ability to model real-world objects like aircraft to understand the expected fluctuation loss effects.

## Related

- [[Array factor]]
- [[Adaptive beamformer]]
- [[Adjacent channel power ratio]]
- [[Air traffic control]]
- [[Algebraic signal processing]]
- [[Aliasing]]
- [[Ambiguity function]]
- [[Analog signal processing]]
- [[Analytic signal]]
- [[Angle of arrival]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fluctuation_loss