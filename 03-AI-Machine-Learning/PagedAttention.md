---
title: "PagedAttention"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/PagedAttention"
wikipedia_categories: ["Algorithms", "Artificial intelligence", "Large language models"]
related: ["[[Agent harness]]", "[[AI data center]]", "[[AI observability]]", "[[Competition in artificial intelligence]]", "[[Emergent algorithm]]", "[[Feedback neural network]]", "[[GPT-5.6]]", "[[List of artificial intelligence algorithms]]", "[[LLM-as-a-Judge]]", "[[Muse Spark]]"]
---

# PagedAttention

PagedAttention is an attention algorithm for efficient serving of large language models (LLMs). It was introduced in 2023 by Woosuk Kwon and colleagues in the paper Efficient Memory Management for Large Language Model Serving with PagedAttention, alongside the vLLM serving engine. The method stores the key–value cache used during autoregressive decoding in fixed-size blocks that can be mapped to non-contiguous physical memory, borrowing ideas from virtual memory, paging, and operating system design.

## Related

- [[Agent harness]]
- [[AI data center]]
- [[AI observability]]
- [[Competition in artificial intelligence]]
- [[Emergent algorithm]]
- [[Feedback neural network]]
- [[GPT-5.6]]
- [[List of artificial intelligence algorithms]]
- [[LLM-as-a-Judge]]
- [[Muse Spark]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/PagedAttention