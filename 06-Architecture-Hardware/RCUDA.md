---
title: "RCUDA"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/RCUDA"
wikipedia_categories: ["Cloud computing", "Cloud platforms", "Computer libraries", "Distributed computing", "Distributed computing architecture", "GPGPU", "Middleware", "Parallel computing"]
related: ["[[Alibaba Cloud]]", "[[Amazon Elastic Compute Cloud]]", "[[AMD Instinct]]", "[[Apache Samza]]", "[[Apache Storm]]", "[[Availability zone]]", "[[Azure Data Lake]]", "[[Azure Maps]]", "[[Azure Stream Analytics]]", "[[Citrix Cloud]]"]
---

# RCUDA

rCUDA, which stands for Remote CUDA, is a type of middleware software framework for remote GPU virtualization. Fully compatible with the CUDA application programming interface (API), it allows the allocation of one or more CUDA-enabled GPUs to a single application. Each GPU can be part of a cluster or running inside of a virtual machine. The approach is aimed at improving performance in GPU clusters that are lacking full utilization. GPU virtualization reduces the number of GPUs needed in a cluster, and in turn, leads to a lower cost configuration – less energy, acquisition, and maintenance.
The recommended distributed acceleration architecture is a high performance computing cluster with GPUs attached to only a few of the cluster nodes. When a node without a local GPU executes an application needing GPU resources, remote execution of the kernel is supported by data and code transfers between local system memory and remote GPU memory. rCUDA is designed to accommodate this client-server architecture. On one end, clients employ a library of wrappers to the high-level CUDA Runtime API, and on the other end, there is a network listening service that receives requests on a TCP port. Several nodes running different GPU-accelerated applications can concurrently make use of the whole set of accelerators installed in the cluster. The client forwards the request to one of the servers, which accesses the GPU installed in that computer and executes the request in it. Time-multiplexing the GPU, or in other words sharing it, is accomplished by spawning different server processes for each remote GPU execution request.

## Related

- [[Alibaba Cloud]]
- [[Amazon Elastic Compute Cloud]]
- [[AMD Instinct]]
- [[Apache Samza]]
- [[Apache Storm]]
- [[Availability zone]]
- [[Azure Data Lake]]
- [[Azure Maps]]
- [[Azure Stream Analytics]]
- [[Citrix Cloud]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/RCUDA