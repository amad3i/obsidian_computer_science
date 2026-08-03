---
title: "Hardware Architecture"
tags: [cs, frontier, arxiv]
domain: Frontier
level: frontier
source: "https://arxiv.org/list/cs.AR/recent"
---

# Hardware Architecture (cs.AR)

Frontier research area. Live listing: https://arxiv.org/list/cs.AR/recent

## Recent papers (real, from arXiv)

### Low-Power PLL-Based Clock Stabilization for Flexible IGZO AMS Systems

Flexible electronics (FE) platforms rely on analog and mixed-signal (AMS) circuits - biosensors, readout front-ends, and analog-to-digital converters - that dominate both functionality and energy consumption, making on-chip clock generation an essential yet power-critical function. Existing oscillator-based solutions suffer from unbounded process, voltage, and temperature (PVT) drift that degrades signal integrity, while alternative clock sources can consume up to 90% of the total system power budget, rendering them inapplicable to FE platforms and elevating clock generation to a primary power and energy-efficiency design constraint. This paper presents the first phase-locked loop (PLL) architecture designed for n-type-only amorphous indium-gallium-zinc oxide (a-IGZO) thin-film transistor (TFT) technology, addressing FE-specific constraints such as the absence of p-type devices, limited 

- http://arxiv.org/abs/2607.29357v1

### RTLCurator: Label-Efficient Data Curation for RTL Generation

Training large language models (LLMs) to write register-transfer level (RTL) requires large corpora of paired specifications and code, and such data is scarce enough that most public corpora are now synthesized. Synthesis provides scale but not correctness, and in two widely used RTL datasets only 24.4% and 53.5% of pairs pass generated functional tests. This raises the question of how much of such a corpus to keep and which part of it. Correctness alone is a poor answer. A pair that misbehaves in one corner case still shows valid syntax and interface conventions, and complex sequential designs are both harder to generate and harder to validate, so filtering by correctness leaves a corpus of short and simple modules. Correctness is also hard to obtain, since behavior leaves little trace on the surface in RTL, and validating an entire corpus only sorts pairs into passed and failed. We pre

- http://arxiv.org/abs/2607.29283v1

### Selective KV Cache Protection for Noise-Resilient LLM Inference on Analog Compute-In-Memory Systems

Analog compute-in-memory (CIM) arrays have emerged as a promising substrate for energy-efficient LLM inference, particularly for weight-stationary computations in linear layers. However, extending analog CIM to attention mechanisms introduces a fundamental challenge: KV cache operations demand repeated in-situ weight updates, and the resulting mismatch with the weight-stationary paradigm exposes dynamic computations to significant hardware noise, a critical problem that remains largely unexplored. In this paper, we present the first systematic study of dynamic attention computation on analog CIM arrays, revealing that initial and recent tokens exhibit disproportionate vulnerability to hardware noise. Motivated by this token-level insight, we propose a hierarchical token protection strategy that keeps sink tokens and a sliding recent-token window on a higher-precision digital path while p

- http://arxiv.org/abs/2607.29076v1

## Sources

- https://arxiv.org/list/cs.AR/recent