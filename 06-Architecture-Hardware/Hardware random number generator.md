---
title: "Hardware random number generator"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Hardware_random_number_generator"
wikipedia_categories: ["Computer peripherals", "Cryptography", "Random number generation"]
related: ["[[Non-physical true random number generator]]", "[[Nothing-up-my-sleeve number]]", "[[123 Reg]]", "[[Accumulator (cryptography)]]", "[[Adaptive redaction]]", "[[Advanced Encryption Standard]]", "[[Alice and Bob]]", "[[Anonymous matching]]", "[[Anonymous remailer]]", "[[Array controller based encryption]]"]
---

# Hardware random number generator

In computing, a hardware random number generator (HRNG), true random number generator (TRNG), non-deterministic random bit generator (NRBG), or physical random number generator is a device that generates random numbers from a physical process capable of producing entropy, unlike a pseudorandom number generator (PRNG) that utilizes a deterministic algorithm and non-physical nondeterministic random bit generators that do not include hardware dedicated to generation of entropy.    
Many natural phenomena generate low-level, statistically random "noise" signals, including thermal and shot noise, jitter and metastability of electronic circuits, Brownian motion, and atmospheric noise. Researchers also used the photoelectric effect, involving a beam splitter, other quantum phenomena, and even nuclear decay (due to practical considerations the latter, as well as the atmospheric noise, is not viable except for fairly restricted applications or online distribution services). While "classical" (non-quantum) phenomena are not truly random, an unpredictable physical system is usually acceptable as a source of randomness, so the qualifiers "true" and "physical" are used interchangeably.  
A hardware random number generator is expected to output near-perfect random numbers ("full entropy"). A physical process usually does not have this property, and a practical TRNG typically includes a few blocks: 

a noise source that implements the physical process producing the entropy. Usually this process is analog, so a digitizer is used to convert the output of the analog source into a binary representation;
a conditioner (randomness extractor) that improves the quality of the random bits;
health tests. TRNGs are mostly used in cryptographical algorithms that get completely broken if the random numbers have low entropy, so the testing functionality is usually included.
Hardware random number generators generally produce only a limited number of random bits per second. In order to increase the available output data rate, they are often used to generate the "seed" for a faster PRNG. PRNG also helps with the noise source "anonymization" (whitening out the noise source identifying characteristics) and entropy extraction. With a proper PRNG algorithm selected (cryptographically secure pseudorandom number generator, CSPRNG), the combination can satisfy the requirements of Federal Information Processing Standards and Common Criteria standards.

## Related

- [[Non-physical true random number generator]]
- [[Nothing-up-my-sleeve number]]
- [[123 Reg]]
- [[Accumulator (cryptography)]]
- [[Adaptive redaction]]
- [[Advanced Encryption Standard]]
- [[Alice and Bob]]
- [[Anonymous matching]]
- [[Anonymous remailer]]
- [[Array controller based encryption]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hardware_random_number_generator