---
title: "Lattice delay network"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Lattice_delay_network"
wikipedia_categories: ["Digital signal processing", "Image impedance filters", "Linear filters", "Network analysis"]
related: ["[[All-pass filter]]", "[[Anti-aliasing filter]]", "[[Filter bank]]", "[[Polyphase quadrature filter]]", "[[Reconstruction filter]]", "[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]"]
---

# Lattice delay network

Lattice delay networks are an important subgroup of lattice networks. They are all-pass filters, so they have a flat amplitude response, but a phase response which varies linearly (or almost linearly) with frequency. All lattice circuits, regardless of their complexity, are based on the schematic shown below, which contains two series impedances, Za, and two shunt impedances, Zb. Although there is duplication of impedances in this arrangement, it offers great flexibility to the circuit designer so that, in addition to its use as delay network (as featured here) it can be configured to be a phase corrector,  a dispersive network, an amplitude equalizer, or a low pass (or bandpass) filter, according to the choice of components for the lattice elements .

 
It is shown in Lattice networks that when a lattice is configured as a delay network, it has a characteristic impedance which is resistive (= Ro), its impedances Za and Zb are dual impedances, i.e. Za⋅Zb = Ro2  (or Za/Ro = Ro/Zb) and Za and Zb consist of inductors and capacitors. Such a lattice is a constant resistance network and an all-pass filter, and it has a phase response determined by the properties of Za. This makes it ideal as a delay device because it can be included in a cascade of other filter sections without affecting the overall amplitude response, nor will it create mismatch problems, but it will increase the phase slope (i.e. the delay) of the overall assembly.
In order to achieve a desired delay, it is necessary to choose specific components for Za and Zb, and the design methods to do this are given in later sections. However, regardless of the method used, networks only achieve a constant delay over a finite band of frequencies, so if an increase in bandwidth and/or delay is required, more complex solutions for Za and Zb are necessary. 
Normally Za and Zb are lumped element impedances, suitable for networks operating at audio or video frequencies but operation up to v.h.f. and even u.h.f. is also possible. Sometimes, the design procedures can result in Za and Zb being highly complicated networks, but it is always possible to derive a cascade of simpler lattices with identical electrical characteristics, should that be preferred.
A lattice delay section has twice the delay of a comparable ladder filter section, and this helps to mitigate concerns over component duplication. In any case, a lattice configuration can be converted to an unbalanced equivalent, which will reduce the component count and permit some relaxation of component tolerances. Consequently, lattice delay sections, or their bridged T circuit equivalents, are able to provide substantial time delays in a compact physical form and they make efficient use of their operational bandwidth. Although there are other ways of achieving signal delays, such as by a long length of coaxial cable, or by lumped element ladder networks, such solutions have either greater physical bulk, or they make inefficient use of a frequency band, or they have poor phase linearity.

## Related

- [[All-pass filter]]
- [[Anti-aliasing filter]]
- [[Filter bank]]
- [[Polyphase quadrature filter]]
- [[Reconstruction filter]]
- [[2D adaptive filters]]
- [[2D Z-transform]]
- [[Adaptive equalizer]]
- [[Adaptive filter]]
- [[Adaptive predictive coding]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Lattice_delay_network