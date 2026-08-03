---
title: "Bit banging"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Bit_banging"
wikipedia_categories: ["Data transmission", "Digital circuits", "Embedded systems", "Signal processing"]
related: ["[[Time-to-digital converter]]", "[[UNI-O]]", "[[Acknowledgement (data networks)]]", "[[Adaptive beamformer]]", "[[Adaptive equalizer]]", "[[Adesto Technologies]]", "[[Adjacent channel power ratio]]", "[[ADvantage Framework]]", "[[Algebraic signal processing]]", "[[Aliasing]]"]
---

# Bit banging

Bit banging is a term of art that describes a method of digital data transmission as using general-purpose input/output (GPIO) instead of computer hardware that is intended specifically for data communication. Controlling software is responsible for satisfying protocol requirements including timing which can be challenging due to limited host system resources and competing demands on the software. 
In contrast, dedicated communication hardware (e.g., UART, SPI, I²C) satisfies protocol requirements which tends to reduce the runtime load on the controlling system – software and its host processor. In particular, some communication hardware provides data buffering to lower the runtime load of the controlling system. There are also peripheral devices dedicated to bit-banging called programmable input/output, combining the flexibility of bit-banging and the low runtime-load of dedicated hardware.
The bit banging method may allow a computer to support a protocol with limited or no hardware changes and therefore bit banging can be a lower cost option since changing software is typically less expensive than changing hardware. 
Bit banging is commonly used in embedded systems. 
Choosing between bit banging and dedicated communication hardware involves trade-offs between load, performance and reliability on one hand, and availability of hardware on the other. Bit banging consumes more processing resources than using dedicated hardware. The processor spends much of its time controlling data lines which precludes other processing. Also, unless hardware interrupt latency is uniform such as in early models of Atmel PICs, and other guarantees made that are usually found in barrel processor designs such as the CDC 6600 I/O co-processor, bit banging typically results in a lower quality signal – with more jitter and glitches – especially if the processor is performing other tasks simultaneously. However, if the software is interrupt-driven by the signal, the signal quality may be better, especially if control signals such as RTS, CTS, or DCD are available. Bit banging may be the only solution when dedicated communication hardware is not available.

## Related

- [[Time-to-digital converter]]
- [[UNI-O]]
- [[Acknowledgement (data networks)]]
- [[Adaptive beamformer]]
- [[Adaptive equalizer]]
- [[Adesto Technologies]]
- [[Adjacent channel power ratio]]
- [[ADvantage Framework]]
- [[Algebraic signal processing]]
- [[Aliasing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bit_banging