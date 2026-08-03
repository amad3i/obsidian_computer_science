---
title: "Carrier frequency offset"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Carrier_frequency_offset"
wikipedia_categories: ["Signal processing"]
related: ["[[Adaptive beamformer]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]", "[[Analog signal processing]]", "[[Analytic signal]]", "[[Angle of arrival]]", "[[Apodization]]", "[[Argument (complex analysis)]]"]
---

# Carrier frequency offset

Carrier frequency offset (CFO) is one of many non-ideal conditions that may affect in baseband receiver design. In designing a baseband receiver, we should notice not only the degradation invoked by non-ideal channel and noise, we should also regard RF and analog parts as the main consideration. Those non-idealities include sampling clock offset, IQ imbalance, power amplifier, phase noise and carrier frequency offset nonlinearity.
Carrier frequency offset often occurs when the local oscillator signal for down-conversion in the receiver does not synchronize with the carrier signal contained in the received signal. This phenomenon can be attributed to two important  factors: frequency mismatch in the transmitter and the receiver oscillators; and the Doppler effect as the transmitter or the receiver is moving.
When this occurs, the received signal will be shifted in frequency. For an OFDM system, the orthogonality among sub carriers is maintained only if the receiver uses a local oscillation signal that is synchronous with the carrier signal contained in the received signal. Otherwise, mismatch in carrier frequency can result in inter-carrier interference (ICI). The oscillators in the transmitter and the receiver can never be oscillating at identical frequency. Hence, carrier frequency offset always exists even if there is no Doppler effect.
A standard-compliant communication system usually requires oscillators to have a small enough tolerance and thus bounds CFO. For example, IEEE 802.11 WLAN specifies the oscillator precision tolerance to be less than ±20 ppm, so that CFO is in the range from -40 ppm to +40 ppm.

## Related

- [[Adaptive beamformer]]
- [[Adjacent channel power ratio]]
- [[Algebraic signal processing]]
- [[Aliasing]]
- [[Ambiguity function]]
- [[Analog signal processing]]
- [[Analytic signal]]
- [[Angle of arrival]]
- [[Apodization]]
- [[Argument (complex analysis)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Carrier_frequency_offset