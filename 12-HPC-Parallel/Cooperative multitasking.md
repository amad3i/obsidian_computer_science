---
title: "Cooperative multitasking"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/Cooperative_multitasking"
wikipedia_categories: ["Concurrent computing"]
related: ["[[Actor model]]", "[[Cache coherence]]", "[[Choreographic programming]]", "[[Communicating sequential processes]]", "[[Computer cluster]]", "[[Computer multitasking]]", "[[Concurrency pattern]]", "[[Concurrent computing]]", "[[Concurrent constraint logic programming]]", "[[Concurrent hash table]]"]
---

# Cooperative multitasking

Cooperative multitasking, also known as non-preemptive multitasking, is a computer multitasking technique in which the operating system never initiates a context switch from a running process to another process. Instead, in order to run multiple applications concurrently, processes voluntarily yield control periodically or when idle or logically blocked.  This type of multitasking is called cooperative because all programs must cooperate for the scheduling scheme to work.  
In this scheme, the process scheduler of an operating system is known as a cooperative scheduler whose role is limited to starting the processes and letting them return control back to it voluntarily.
This is related to the asynchronous programming approach.

## Related

- [[Actor model]]
- [[Cache coherence]]
- [[Choreographic programming]]
- [[Communicating sequential processes]]
- [[Computer cluster]]
- [[Computer multitasking]]
- [[Concurrency pattern]]
- [[Concurrent computing]]
- [[Concurrent constraint logic programming]]
- [[Concurrent hash table]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Cooperative_multitasking