---
title: "MIMO"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/MIMO"
wikipedia_categories: ["Control engineering", "IEEE 802", "Information theory", "Radio resource management"]
related: ["[[3G MIMO]]", "[[Many antennas]]", "[[MIMO-OFDM]]", "[[Per-user unitary rate control]]", "[[Spatial multiplexing]]", "[[Zero-forcing precoding]]", "[[Channel state information]]", "[[Cooperative MIMO]]", "[[Multi-user MIMO]]", "[[Spectral efficiency]]"]
---

# MIMO

Multiple-input and multiple-output (MIMO) () is a wireless technology that multiplies the capacity of a radio link using multiple transmit and receive antennas. MIMO has become a core technology for broadband wireless communications, including mobile standards—4G WiMAX (802.16 e, m), and 3GPP 4G LTE and 5G NR, as well as Wi-Fi standards, IEEE 802.11n, ac, and ax.
MIMO uses the spatial diversity to increase link capacity. The technology requires multiple antennas at both the transmitter and receiver, along with associated signal processing, to deliver data rate speedups roughly proportional to the number of antennas at each end.
MIMO starts with a high-rate data stream, which is de-multiplexed into multiple, lower-rate streams. Each of these streams is then modulated and transmitted in parallel with different coding from the transmit antennas, with all streams in the same frequency channel. These co-channel, mutually interfering streams arrive at the receiver's antenna array, each having a different spatial signature—gain phase pattern at the receiver’s antennas. These distinct array signatures allow the receiver to separate these co-channel streams, demodulate them, and re-multiplex them to reconstruct the original high-rate data stream. This process is sometimes referred to as spatial multiplexing.
The key to MIMO is the sufficient differences in the spatial signatures of the different streams to enable their separation. This is achieved through a combination of angle spread of the multipaths and sufficient spacing between antenna elements. In environments with a rich multipath and high angle spread, common in cellular and Wi-Fi deployments, an antenna element spacing at each end of just a few wavelengths can suffice. However, in the absence of significant multipath spread, larger element spacing (wider angle separation) is required at either the transmit array, the receive array, or at both.

## Related

- [[3G MIMO]]
- [[Many antennas]]
- [[MIMO-OFDM]]
- [[Per-user unitary rate control]]
- [[Spatial multiplexing]]
- [[Zero-forcing precoding]]
- [[Channel state information]]
- [[Cooperative MIMO]]
- [[Multi-user MIMO]]
- [[Spectral efficiency]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/MIMO