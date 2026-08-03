---
title: "Masreliez's theorem"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Masreliez's_theorem"
wikipedia_categories: ["Control engineering", "Control theory", "Signal processing"]
related: ["[[Transfer function matrix]]", "[[Ackermann's formula]]", "[[American Automatic Control Council]]", "[[Asymptotic gain model]]", "[[Blackman's theorem]]", "[[Control reconfiguration]]", "[[Control system]]", "[[Control theory]]", "[[Data-driven control system]]", "[[Derivation of the Routh array]]"]
---

# Masreliez's theorem

Masreliez theorem describes a recursive algorithm within the technology of extended Kalman filter, named after the Swedish-American physicist John Masreliez, who is its author.  The algorithm estimates the state of a dynamic system with the help of often incomplete measurements marred by distortion.
Masreliez's theorem produces estimates that are quite good approximations to the exact conditional mean in non-Gaussian additive outlier (AO) situations.  Some evidence for this can be had by Monte Carlo simulations.
The key approximation property used to construct these filters is that the state prediction density is approximately Gaussian. Masreliez discovered in 1975 that this approximation yields an intuitively appealing non-Gaussian filter recursions, with data dependent covariance (unlike the Gaussian case) this derivation also provides one of the nicest ways of establishing the standard Kalman filter recursions.  Some theoretical justification for use of the Masreliez approximation is provided by the "continuity of state prediction densities" theorem in Martin (1979).

## Related

- [[Transfer function matrix]]
- [[Ackermann's formula]]
- [[American Automatic Control Council]]
- [[Asymptotic gain model]]
- [[Blackman's theorem]]
- [[Control reconfiguration]]
- [[Control system]]
- [[Control theory]]
- [[Data-driven control system]]
- [[Derivation of the Routh array]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Masreliez's_theorem