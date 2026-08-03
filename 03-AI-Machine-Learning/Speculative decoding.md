---
title: "Speculative decoding"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Speculative_decoding"
wikipedia_categories: ["Deep learning", "Machine learning algorithms", "Natural language processing"]
related: ["[[AI data center]]", "[[Augmented Analytics]]", "[[Conversica]]", "[[Deep reinforcement learning]]", "[[Foundation model]]", "[[Geospatial foundation model]]", "[[Knowledge cutoff]]", "[[Large language model]]", "[[LoRA (machine learning)]]", "[[Prompt engineering]]"]
---

# Speculative decoding

Speculative decoding is an inference-time optimization for autoregressive large language models (LLMs) that generates multiple tokens per decoding step instead of one. A smaller draft model proposes a sequence of candidate tokens, and the larger target model verifies them in a single forward pass through a modified rejection sampling scheme. The verification preserves the target model's original output distribution, so the technique produces the same results as standard decoding while cutting latency by roughly two to three times. The name is an analogy to speculative execution in CPU design, where a processor runs instructions along a predicted branch before the outcome is known.

## Related

- [[AI data center]]
- [[Augmented Analytics]]
- [[Conversica]]
- [[Deep reinforcement learning]]
- [[Foundation model]]
- [[Geospatial foundation model]]
- [[Knowledge cutoff]]
- [[Large language model]]
- [[LoRA (machine learning)]]
- [[Prompt engineering]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Speculative_decoding