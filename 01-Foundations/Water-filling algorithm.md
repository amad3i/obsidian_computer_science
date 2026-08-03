---
title: "Water-filling algorithm"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Water-filling_algorithm"
wikipedia_categories: ["Error detection and correction", "Information theory", "Telecommunication theory", "Telecommunications", "Telecommunications stubs"]
related: ["[[Interference channel]]", "[[Shaping codes]]", "[[WSSUS model]]", "[[Channel capacity]]", "[[Channel state information]]", "[[Channel use]]", "[[Communication channel]]", "[[Communication source]]", "[[Constant-weight code]]", "[[EXIT chart]]"]
---

# Water-filling algorithm

The water-filling algorithm is a technique used in digital communications systems for allocating power among different channels in multicarrier schemes. It was described by R. C. Gallager in 1968 along with the water-filling theorem which proves its optimality for channels having Additive White Gaussian Noise (AWGN) and intersymbol interference (ISI).
For this reason, it is a standard baseline algorithm for various digital communications systems, such as MIMO wireless systems.
The intuition that gives the algorithm its name is to think of the communication medium as if it was some kind of water container with an uneven bottom. Each of the available channels is then a section of the container having its own depth, given by the reciprocal of the frequency-dependent SNR for the channel.
To allocate power, imagine pouring water into this container (the amount depends on the desired maximum average transmit power). After the water level settles, the largest amount of water is in the deepest sections of the container. This implies allocating more power to the channels with the most favourable SNR. Note, however, that the ratio allocation to each channel is not a fixed proportion but varies nonlinearly with the maximum average transmit power.

## Related

- [[Interference channel]]
- [[Shaping codes]]
- [[WSSUS model]]
- [[Channel capacity]]
- [[Channel state information]]
- [[Channel use]]
- [[Communication channel]]
- [[Communication source]]
- [[Constant-weight code]]
- [[EXIT chart]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Water-filling_algorithm