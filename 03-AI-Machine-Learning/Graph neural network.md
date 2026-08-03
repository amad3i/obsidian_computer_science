---
title: "Graph neural network"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Graph_neural_network"
wikipedia_categories: ["2009 in artificial intelligence", "Artificial neural networks", "Graph algorithms", "Neural network architectures", "Semisupervised learning", "Supervised learning", "Unsupervised learning"]
related: ["[[Hierarchical temporal memory]]", "[[Restricted Boltzmann machine]]", "[[Competitive learning]]", "[[Generative adversarial network]]", "[[Neural field]]", "[[Self-organizing map]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[A- search algorithm]]", "[[Activation function]]", "[[ADALINE]]"]
---

# Graph neural network

Graph neural networks (GNNs) are artificial neural networks designed for tasks whose inputs are graphs. 
Because graphs usually do not have a canonical ordering of their nodes, GNN architectures are commonly designed to be permutation equivariant: reordering the nodes in the input reorders the corresponding node representations in the same way. For graph-level prediction tasks, GNNs typically use a permutation-invariant readout function, whose output is unchanged by the ordering of the nodes.
A prominent example is molecular drug design.  Molecules can be represented as graphs, with nodes for atoms and edges for atomic bonds, often including known chemical properties as features.  Inputs may thus differ in size, due to varying number of atoms and bonds. A graph-level task may be to predict the efficacy of a given molecule for a specific medical application, such as eliminating E. coli bacteria.
The key design element of GNNs is the use of pairwise message passing, such that graph nodes iteratively update their representations by exchanging information with their neighbors. Several GNN architectures have been proposed, which implement different flavors of message passing,  started by recursive or convolutional constructive approaches. A 2022 position paper argued that many architectures described as going "beyond" message passing can instead be interpreted as message passing over suitably modified graphs, and proposed the term "augmented message passing" for such approaches.

In the more general subject of "geometric deep learning", certain existing neural network architectures can be interpreted as GNNs operating on suitably defined graphs. A convolutional neural network layer, in the context of computer vision, can be considered a GNN applied to graphs whose nodes are pixels, and only adjacent pixels are connected by edges in the graph. A transformer layer, in natural language processing, can be considered a GNN applied to complete graphs whose nodes are words or tokens in a passage of natural language text.
Relevant application domains for GNNs include natural language processing, social networks, citation networks, molecular biology, chemistry, physics and NP-hard combinatorial optimization problems.
Open source libraries implementing GNNs include PyTorch Geometric (PyTorch), TensorFlow GNN (TensorFlow), Deep Graph Library (framework agnostic), jraph (Google JAX), and GraphNeuralNetworks.jl/GeometricFlux.jl (Julia, Flux).

## Related

- [[Hierarchical temporal memory]]
- [[Restricted Boltzmann machine]]
- [[Competitive learning]]
- [[Generative adversarial network]]
- [[Neural field]]
- [[Self-organizing map]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]
- [[A- search algorithm]]
- [[Activation function]]
- [[ADALINE]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Graph_neural_network