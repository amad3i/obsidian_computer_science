---
title: "Complementary code keying"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Complementary_code_keying"
wikipedia_categories: ["IEEE 802.11", "Quantized radio modulation modes", "Wireless networking"]
related: ["[[Direct-sequence spread spectrum]]", "[[CCMP (cryptography)]]", "[[Control and Provisioning of Wireless Access Points protocol]]", "[[Exposed node problem]]", "[[Hidden node problem]]", "[[IEEE 802.11ad]]", "[[IEEE 802.11af]]", "[[Morse Micro]]", "[[Temporal Key Integrity Protocol]]", "[[Wired Equivalent Privacy]]"]
---

# Complementary code keying

Complementary code keying (CCK) is a modulation scheme used with wireless networks (WLANs) that employ the IEEE 802.11b specification. In 1999, CCK was adopted to supplement the Barker code in wireless digital networks to achieve data rate higher than 2 Mbit/s at the expense of shorter distance. This is due to the shorter chipping sequence in CCK (8 bits versus 11 bits in Barker code) that means less spreading to obtain higher data rate but more susceptible to narrowband interference resulting in shorter radio transmission range. Beside shorter chipping sequence, CCK also has more chipping sequences to encode more bits (4 chipping sequences at 5.5 Mbit/s and 8 chipping sequences at 11 Mbit/s) increasing the data rate even further. The Barker code, however, only has a single chipping sequence.
The complementary codes first discussed by Golay were pairs of binary complementary codes and he noted that when the elements of a code of length N were either [−1 or 1] it followed immediately from their definition that the sum of their respective autocorrelation sequences was zero at all points except for the zero shift where it is equal to K×N. (K being the number of code words in the set).
CCK is a variation and improvement on M-ary Orthogonal Keying and uses 'polyphase complementary codes'. They were developed by Lucent Technologies and Harris Semiconductor and were adopted by the 802.11 working group in 1998. CCK is the form of modulation used when 802.11b operates at either 5.5 or 11 Mbit/s. CCK was selected over competing modulation techniques as it used approximately the same bandwidth and could use the same preamble and header as pre-existing 1 and 2 Mbit/s wireless networks and thus facilitated interoperability.
Polyphase complementary codes, first proposed by Sivaswamy, 1978, are codes where each element is a complex number of unit magnitude and arbitrary phase, or more specifically for 802.11b is one of [1, −1, j, −j].
Networks using the 802.11g specification employ CCK when operating at 802.11b speeds.

## Related

- [[Direct-sequence spread spectrum]]
- [[CCMP (cryptography)]]
- [[Control and Provisioning of Wireless Access Points protocol]]
- [[Exposed node problem]]
- [[Hidden node problem]]
- [[IEEE 802.11ad]]
- [[IEEE 802.11af]]
- [[Morse Micro]]
- [[Temporal Key Integrity Protocol]]
- [[Wired Equivalent Privacy]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Complementary_code_keying