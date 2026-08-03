---
title: "Computation and Language"
tags: [cs, frontier, arxiv]
domain: Frontier
level: frontier
source: "https://arxiv.org/list/cs.CL/recent"
---

# Computation and Language (cs.CL)

Frontier research area. Live listing: https://arxiv.org/list/cs.CL/recent

## Recent papers (real, from arXiv)

### TokTier: Exact Stateful Tokenization for Agentic LLM Serving

LLM serving systems cache prompt KV state, yet most front ends still re-tokenize the full request text on every call. The cost lands on coding agents, which resubmit a long transcript after each small tool result, and reuse is hard because even a short append can change token boundaries near the end of the previous sequence. Across 153,951 calls from two agent ecosystems, the median call appends about 1.4K characters, and only 1.0-3.6% of calls start or rebuild a session with contexts of millions of characters. At a 94.1% fleet prompt-cache hit rate, tokenization reaches up to 64% of time to first token. TokTier is a stateful tokenization service with one contract: emitted token IDs are always identical to full reference tokenization of the request text. For a session continuation, it re-tokenizes a small window around the append and splices only after a per-request stable-boundary check

- http://arxiv.org/abs/2607.29678v1

### Evolving language compositionality in a frequency-structured meaning space

The iterated learning model was introduced to investigate language evolution: the way in which the characteristic properties of human languages have been shaped, at least partly, by repeated transmission from one language user to another. The key finding is that language compositionality can arise spontaneously as a consequence of language being passed repeatedly through a language learning bottleneck. Here we explore how changing the frequency of different meanings, so that some meanings occur much more frequently than others, affects the character of its compositionality. We find that, as observed in natural languages, high-frequency meanings can escape the pressure to conform to the grammar that characterizes lower-frequency meanings. However, when the frequency structure is instead imposed on parts rather than on whole meaning vectors, the language fails to transmit across generation

- http://arxiv.org/abs/2607.29642v1

### WCM: A World Critic Model for Vision-Language-Action Reinforcement Learning

Reinforcement learning (RL) post-training of Vision-Language-Action (VLA) models has shown strong promise for robotic manipulation. Among RL methods, critic-based approaches rely on a value estimator that predominantly operates on single-frame observations or single-frame VLM backbone latents, which is a fundamental mismatch with the partially observable nature of robot control. A naive approach to incorporate observation history into the critic incurs exponential complexity with high-dimensional visual space, and still fails because pure scalar-return regression provides insufficient supervision for learning cross-temporal dynamics. We identify the root cause as a state approximation problem: without an explicit world modeling objective, the critic's representation cannot capture the temporal structure needed for accurate value estimation. To address this, we propose the World Critic Mo

- http://arxiv.org/abs/2607.29613v1

## Sources

- https://arxiv.org/list/cs.CL/recent