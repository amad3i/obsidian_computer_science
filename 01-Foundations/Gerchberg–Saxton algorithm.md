---
title: "Gerchberg–Saxton algorithm"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Gerchberg–Saxton_algorithm"
wikipedia_categories: ["Digital signal processing", "Physical optics"]
related: ["[[Adaptive-additive algorithm]]", "[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adjoint filter]]", "[[Advanced process control]]", "[[Aliasing]]", "[[All-pass filter]]"]
---

# Gerchberg–Saxton algorithm

The Gerchberg–Saxton (GS) algorithm is an iterative phase retrieval algorithm for retrieving the phase of a complex-valued wavefront from two intensity measurements acquired in two different planes. Typically, the two planes are the image plane and the far field (diffraction) plane, and the wavefront propagation between these two planes is given by the Fourier transform. The original paper by Gerchberg and Saxton considered image and diffraction pattern of a sample acquired in an electron microscope.
It is often necessary to know only the phase distribution from one of the planes, since the phase distribution on the other plane can be obtained by performing a Fourier transform on the plane whose phase is known. Although often used for two-dimensional signals, the GS algorithm is also valid for one-dimensional signals.
The pseudocode below performs the GS algorithm to obtain a phase distribution for the plane "Source", such that its Fourier transform would have the amplitude distribution of the plane "Target".
The Gerchberg-Saxton algorithm is one of the most prevalent methods used to create computer-generated holograms.

## Related

- [[Adaptive-additive algorithm]]
- [[2D adaptive filters]]
- [[2D Z-transform]]
- [[Adaptive equalizer]]
- [[Adaptive filter]]
- [[Adaptive predictive coding]]
- [[Adjoint filter]]
- [[Advanced process control]]
- [[Aliasing]]
- [[All-pass filter]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Gerchberg–Saxton_algorithm