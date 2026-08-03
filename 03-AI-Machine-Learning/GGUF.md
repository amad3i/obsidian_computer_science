---
title: "GGUF"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/GGUF"
wikipedia_categories: ["Computer file formats", "Free software", "Large language models", "Machine learning"]
related: ["[[AI data center]]", "[[AI observability]]", "[[Claude (AI)]]", "[[GLM (AI)]]", "[[LLM-as-a-Judge]]", "[[Sycophancy (artificial intelligence)]]", "[[wps]]", "[[80 Million Tiny Images]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Accelerated Linear Algebra]]"]
---

# GGUF

The GGUF (GGML Universal File) file format is a binary file format that stores both tensors and metadata in a single file and is designed for fast saving and loading of model data. It was introduced in August 2023 by the llama.cpp project to better maintain backward compatibility as support was added for other model architectures. It superseded previous formats used by the project such as GGML and is typically produced by converting models developed with a different machine-learning library such as PyTorch.
GGUF has become the standard format for distributing quantized large language models for local inference and is natively supported by tools such as llama.cpp, Ollama, LM Studio, GPT4All, Jan, and koboldcpp. As of 2026, tens of thousands of GGUF checkpoints are hosted on Hugging Face, which provides first-class integration, including a metadata viewer, an inference endpoint service, and a JavaScript parser library.

## Related

- [[AI data center]]
- [[AI observability]]
- [[Claude (AI)]]
- [[GLM (AI)]]
- [[LLM-as-a-Judge]]
- [[Sycophancy (artificial intelligence)]]
- [[wps]]
- [[80 Million Tiny Images]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]
- [[Accelerated Linear Algebra]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/GGUF