---
title: "Dynamic single-frequency networks"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Dynamic_single-frequency_networks"
wikipedia_categories: ["Radio resource management", "Telecommunications techniques", "Wireless networking"]
related: ["[[Cognitive radio]]", "[[Open spectrum]]", "[[Radio Link Protocol]]", "[[Reconfigurability]]", "[[Smartphone ad hoc network]]", "[[Spatial capacity]]", "[[Spectral efficiency]]", "[[Spectrum commons theory]]", "[[2016 United States wireless spectrum auction]]", "[[3G MIMO]]"]
---

# Dynamic single-frequency networks

Dynamic single-frequency networks (DSFN) is a technique of using several transmitter antennas to transfer the same signal (macrodiversity) in orthogonal frequency-division multiplexing cellular networks.
DSFN is based on the idea of single frequency networks, which is a group of radio transmitters that send the same signal simultaneously over the same frequency. The term originates from the broadcasting world, where a broadcast network is a group of transmitters that send the same TV or radio program. Digital wireless communication systems based on the OFDM modulation scheme are well-suited to SFN operation, since OFDM in combination with some forward error correction scheme can eliminate intersymbol interference and fading caused by multipath propagation without the use of complex equalization.
The concept of DSFN implies the SFN grouping is changed dynamically over time, from timeslot to timeslot. The aim is to achieve efficient spectrum utilization for downlink unicast or multicast communication services in centrally controlled cellular systems based on for example the OFDM modulation scheme. A centralized scheduling algorithm assigns each data packet to a certain timeslot, frequency channel and group of base station transmitters. DSFN can be considered as a combination of packet scheduling, macro-diversity and dynamic channel allocation (DCA). The scheduling algorithm can be further extended to dynamically assign other radio resource management parameters to each timeslot and transmitter, such as modulation scheme and error correction scheme, in view to optimize the efficiency.
DSFN makes it possible to increase the received signal strength to a mobile terminal in between several base station transmitters in comparison to non-macrodiversity communication schemes. Thus, DSFN can improve the coverage area and lessen the outage probability. Alternatively, DSFN may allow the same outage probability with a less robust but more efficient modulation and error coding scheme, and thus improve the spectral efficiency in bit/s/Hz/base station transmitter in comparison to a non-macrodiversity communication scheme.
DSFN resembles the CDMA downlink soft handover. A difference is that in the CDMA case, co-channel interference from transmissions to other users are more efficiently avoided by giving the other users other spreading codes.
A special form of DSFN is Continuous Transmission DSFN, where all base station transmitters always transmit at full power, without blocking of non-utilized transmitters, and without power control. This concept is very similar to so called Virtual cellular networks (VCNs), where a virtual cell is a group of base stations sending using the same spreading code, or a group of OFDM transmitters form a Single Frequency Network.

## Related

- [[Cognitive radio]]
- [[Open spectrum]]
- [[Radio Link Protocol]]
- [[Reconfigurability]]
- [[Smartphone ad hoc network]]
- [[Spatial capacity]]
- [[Spectral efficiency]]
- [[Spectrum commons theory]]
- [[2016 United States wireless spectrum auction]]
- [[3G MIMO]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dynamic_single-frequency_networks