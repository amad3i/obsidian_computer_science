---
title: "Distributed, Parallel, and Cluster Computing"
tags: [cs, frontier, arxiv]
domain: Frontier
level: frontier
source: "https://arxiv.org/list/cs.DC/recent"
---

# Distributed, Parallel, and Cluster Computing (cs.DC)

Frontier research area. Live listing: https://arxiv.org/list/cs.DC/recent

## Recent papers (real, from arXiv)

### TokTier: Exact Stateful Tokenization for Agentic LLM Serving

LLM serving systems cache prompt KV state, yet most front ends still re-tokenize the full request text on every call. The cost lands on coding agents, which resubmit a long transcript after each small tool result, and reuse is hard because even a short append can change token boundaries near the end of the previous sequence. Across 153,951 calls from two agent ecosystems, the median call appends about 1.4K characters, and only 1.0-3.6% of calls start or rebuild a session with contexts of millions of characters. At a 94.1% fleet prompt-cache hit rate, tokenization reaches up to 64% of time to first token. TokTier is a stateful tokenization service with one contract: emitted token IDs are always identical to full reference tokenization of the request text. For a session continuation, it re-tokenizes a small window around the append and splices only after a per-request stable-boundary check

- http://arxiv.org/abs/2607.29678v1

### GQ-FSL: Green Quantized Federated Split Learning

Deploying state-of-the-art deep neural networks (DNNs) at the wireless edge is severely bottlenecked by the strict energy and resource constraints of mobile devices. While federated split learning (FSL) mitigates on-device computation by offloading workloads to an edge server, this may introduce systemic overheads, while the continuous exchange of cut-layer data, and submodels still incurs significant energy consumption (EC). To address this, we propose a green quantized FSL (GQ-FSL) framework that incorporates stochastic quantization for both local collaborative training and wireless transmissions. Notably, GQ-FSL supports asymmetric precision levels for the client- and server-side submodels, effectively decoupling device energy constraints from global convergence degradation. To quantify these tradeoffs, we develop parameterized energy models for the split architecture and derive a the

- http://arxiv.org/abs/2607.29659v1

### SLIM: Saturation-Aware Lightweight Performance Modeling for LLM Serving

Large language model (LLM) serving commonly increases batch size to improve throughput, but performance eventually reaches a deployment-dependent plateau beyond which larger batches provide marginal gains while increasing latency and GPU memory consumption. Previous studies have attributed this behavior to HBM/DRAM bandwidth limitations, but the underlying causes have primarily been supported by conceptual arguments or high-level performance observations. As our first contribution, we present a detailed GPU characterization using hardware profiling techniques, demonstrating that throughput saturation originates in the attention kernels during the decode phase. Specifically, we show that their nearly constant arithmetic intensity as active-context lengths increases -not merely larger batch sizes- drives DRAM-bandwidth saturation, while the achieved compute throughput remains far below the

- http://arxiv.org/abs/2607.29575v1

## Sources

- https://arxiv.org/list/cs.DC/recent