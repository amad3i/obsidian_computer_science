---
title: "Databases"
tags: [cs, frontier, arxiv]
domain: Frontier
level: frontier
source: "https://arxiv.org/list/cs.DB/recent"
---

# Databases (cs.DB)

Frontier research area. Live listing: https://arxiv.org/list/cs.DB/recent

## Recent papers (real, from arXiv)

### MERIT: Efficient In-Place Deletion for Dynamic Graph-Based Approximate Nearest Neighbor Indexes

Graph-based indexes have become the dominant approach to approximate nearest neighbor search (ANNS) over high-dimensional data and play a crucial role in real-world applications such as retrieval-augmented generation, recommendation systems, and vector databases. Despite extensive progress in static graph construction and search, efficient in-place deletion remains challenging because obsolete vectors must be removed without allowing stale incoming edges to consume search capacity or expensive graph-wide maintenance to interrupt online services, e.g., retrieval-augmented generation (RAG) and recommendation platforms. To address this problem, we propose MERIT (MST-based Efficient Repair with In-place updaTes), an in-place update framework with three core techniques: (1) bounded search-based recovery that combines a deleted vertex's outgoing neighbors with its readily searchable in-neighbo

- http://arxiv.org/abs/2607.29173v1

### InferQ: A Database-Oriented Benchmark for Quantum Circuits Simulation

Recent work suggests that relational database management systems (RDBMSs) can execute quantum circuit simulation by compiling the simulation into SQL workloads (primarily join-and-aggregate tensor contractions). While early results are promising, they largely focus on a narrow set of highly structured circuits and offer limited support for systematic database research, such as query optimization, physical design, and engine-level evaluation across a broad range of circuits. We present InferQ, a database-oriented benchmark for quantum circuit simulation. InferQ generates general, compositional circuits by assembling subcircuits from a set of circuit templates, emits each simulation task as an RDBMS-ready SQL workload, and extracts circuit and query features (static, graph, SQL, and dynamic) for workload characterization. InferQ also releases a large dataset of 202,975 circuits online, wit

- http://arxiv.org/abs/2607.29134v1

### Curriculum Matters: Data-Efficient Relational PFN Pretraining with Synthetic Data

Relational Prior-Data Fitted Networks (PFNs) such as RDB-PFN approximate Bayesian inference over multi-table relational databases by pretraining on millions of synthetic tasks. We investigate three intertwined questions about this paradigm. First, can a structurally different synthetic generator PluRel substitute for RDB-PFN's prior? Second, how much does the order in which synthetic data is presented to the PFN affect downstream performance? Third, how much relational reasoning can a PFN acquire from single-table synthetic pretraining alone, before any relational data is introduced? Using PluRel as the sole synthetic data source across all experiments, we find: (i) a progressive single-table curriculum that gradually widens schema complexity from 7 to 17 columns reaches 0.703 average ROC-AUC on the 23-task tabular benchmark using only approximately 13,300 synthetic tables (approximately

- http://arxiv.org/abs/2607.29120v1

## Sources

- https://arxiv.org/list/cs.DB/recent