---
title: "FDOA"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/FDOA"
wikipedia_categories: ["Digital signal processing", "Engineering stubs"]
related: ["[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adaptive-additive algorithm]]", "[[Adjoint filter]]", "[[Advanced process control]]", "[[Aliasing]]", "[[All-pass filter]]"]
---

# FDOA

Frequency difference of arrival (FDOA) or differential Doppler (DD), is a technique analogous to TDOA for estimating the location of a radio emitter based on observations from other points. (It can also be used for estimating one's own position based on observations of multiple emitters). TDOA and FDOA are sometimes used together to improve location accuracy and the resulting estimates are somewhat independent.  By combining TDOA and FDOA measurements, instantaneous geolocation can be performed in two dimensions.
It differs from TDOA in that the FDOA observation points must be in relative motion with respect to each other and the emitter.  This relative motion results in different doppler shifts observations of the emitter at each location in general. The relative motion can be achieved by using airborne observations in aircraft, for example.  The emitter location can then be estimated with knowledge of the observation points' location and vector velocities and the observed relative doppler shifts between pairs of locations.
A disadvantage of FDOA is that large amounts of data must be moved between observation points or to a central location to do the cross-correlation that is necessary to estimate the doppler shift.
The accuracy of the location estimate is related to the bandwidth of the emitter's signal, the signal-to-noise ratio at each observation point, and the geometry and vector velocities of the emitter and the observation points.

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

- Wikipedia: https://en.wikipedia.org/wiki/FDOA