---
title: "Sentence embedding"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Sentence_embedding"
wikipedia_categories: ["Artificial neural networks", "Computational linguistics", "Language modeling", "Natural language processing"]
related: ["[[Word embedding]]", "[[Cache language model]]", "[[Foundation model]]", "[[N-gram]]", "[[ACL Data Collection Initiative]]", "[[Adversarial stylometry]]", "[[Aggregation (linguistics)]]", "[[Arabic Ontology]]", "[[Artificial intelligence content detection]]", "[[Association for Computational Linguistics]]"]
---

# Sentence embedding

In natural language processing, a sentence embedding (or document embedding) is a representation of a natural language text as a vector of numbers which encodes meaningful semantic information. The name stems from the initially limitations of the approach to embed sequences of text longer than a sentence, but this is not longer a limitation.
State of the art embeddings are based on the learned hidden layer representation of dedicated sentence transformer models. BERT pioneered an approach involving the use of a dedicated [CLS] token prepended to the beginning of each sentence inputted into the model; the final hidden state vector of this token encodes information about the sentence and can be fine-tuned for use in sentence classification tasks. In practice however, BERT's sentence embedding with the [CLS] token achieves poor performance, often worse than simply averaging non-contextual word embeddings. SBERT later achieved superior sentence embedding performance by fine tuning BERT's [CLS] token embeddings through the usage of a siamese neural network architecture on the SNLI dataset. 
Other approaches are loosely based on the idea of distributional semantics applied to sentences. Skip-Thought trains an encoder-decoder structure for the task of neighboring sentences predictions; this has been shown to achieve worse performance than approaches such as InferSent or SBERT. 
An alternative direction is to aggregate word embeddings, such as those returned by Word2vec, into sentence embeddings. The most straightforward approach is to simply compute the average of word vectors, known as continuous bag-of-words (CBOW). However, more elaborate solutions based on word vector quantization have also been proposed. One such approach is the vector of locally aggregated word embeddings (VLAWE), which demonstrated performance improvements in downstream text classification tasks.

## Related

- [[Word embedding]]
- [[Cache language model]]
- [[Foundation model]]
- [[N-gram]]
- [[ACL Data Collection Initiative]]
- [[Adversarial stylometry]]
- [[Aggregation (linguistics)]]
- [[Arabic Ontology]]
- [[Artificial intelligence content detection]]
- [[Association for Computational Linguistics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sentence_embedding