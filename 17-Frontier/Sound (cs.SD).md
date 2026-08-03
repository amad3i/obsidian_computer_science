---
title: "Sound"
tags: [cs, frontier, arxiv]
domain: Frontier
level: frontier
source: "https://arxiv.org/list/cs.SD/recent"
---

# Sound (cs.SD)

Frontier research area. Live listing: https://arxiv.org/list/cs.SD/recent

## Recent papers (real, from arXiv)

### Stable Autoregressive Speech Generation with Low-Frame-Rate High-Dimensional Continuous Tokens

Balancing sequence length, representational capacity, and long-horizon stability is a central problem in autoregressive (AR) speech and audio generation. Representations with higher frame rates or greater capacity can preserve more signal detail, but they also make streaming generation more vulnerable to distribution drift and AR error accumulation. Conversely, shorter and more compressed representations simplify AR modeling, but their limited bandwidth may discard important components and constrain the upper bound of reconstruction fidelity and generation quality. We ask whether a low-frame-rate, high-dimensional, high-bandwidth continuous representation can be co-designed with a streaming generation framework to support robust high-fidelity reconstruction, strong single-token predictability, and superior long-horizon stability. We decompose this goal into two coupled problems: what geo

- http://arxiv.org/abs/2607.29363v1

### ParaASR: Multi-Token Prediction for Fast and Long-Context LLM-Based Speech Recognition

Audio-encoder-LLM-decoder architectures have become the dominant paradigm for modern automatic speech recognition (ASR), improving transcription quality through large-scale language modeling. However, the cost of autoregressive decoding scales with decoder size, creating a fundamental trade-off between recognition quality and serving latency. We argue this trade-off is not inherent: unlike open-ended text generation, ASR outputs are strongly anchored to the input speech signal, providing a natural inductive bias toward high-parallelism decoding. Building on this, we introduce ParaASR, an ASR system that leverages Multi-Token Prediction (MTP) to let a 4B LLM decoder emit multiple tokens per forward step. Starting from a publicly available audio-language foundation, the model first establishes a robust autoregressive recognizer and then aligns five future-token branches through a staged op

- http://arxiv.org/abs/2607.29279v1

### DoubleHelix: Structured Cross-Modal Fusion for Audio-Visual Speech Recognition with LLMs

Audio-visual speech recognition (AVSR) relies on effective fusion of audio and visual modalities, yet existing approaches treat cross-modal interaction as a single-step operation without structured iterative refinement. We present DoubleHelix, a multimodal fusion framework that reformulates fusion as an iterative cross-modal interaction process with adaptive degradation-aware enhancement. The framework comprises three components including ReverseParallelHelix for multi-turn structured interaction with learned alignment constraints, QualitySensor for learning degradation-aware gating signals, and HelixReplication for consistency-guided conditional feature enhancement. Experiments on LRS3 demonstrate that DoubleHelix achieves 0.68% WER on clean audio, outperforming previous best results by 5.6% relative improvement under matched backbone settings. Comprehensive ablation studies validate ea

- http://arxiv.org/abs/2607.29112v1

## Sources

- https://arxiv.org/list/cs.SD/recent