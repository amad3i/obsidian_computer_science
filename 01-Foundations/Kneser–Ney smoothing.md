---
title: "Kneser–Ney smoothing"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Kneser–Ney_smoothing"
wikipedia_categories: ["Language modeling", "Statistical methods"]
related: ["[[Brown clustering]]", "[[Cache language model]]", "[[Distributional–relational database]]", "[[EleutherAI]]", "[[Factored language model]]", "[[Foundation model]]", "[[Geospatial foundation model]]", "[[Hallucination (artificial intelligence)]]", "[[Katz's back-off model]]", "[[Lancichinetti–Fortunato–Radicchi benchmark]]"]
---

# Kneser–Ney smoothing

Kneser–Ney smoothing, also known as Kneser–Essen–Ney smoothing, is a method primarily used to calculate the probability distribution of n-grams in a document based on their histories. It is widely considered the most effective method of smoothing due to its use of absolute discounting by subtracting a fixed value from the probability's lower order terms to omit n-grams with lower frequencies. This approach has been considered equally effective for both higher and lower order n-grams. The method was proposed in a 1994 paper by Reinhard Kneser, Ute Essen and Hermann Ney.
A common example that illustrates the concept behind this method is the frequency of the bigram "San Francisco". If it appears several times in a training corpus, the frequency of the unigram "Francisco" will also be high. Relying on only the unigram frequency to predict the frequencies of n-grams leads to skewed results; however, Kneser–Ney smoothing corrects this by considering the frequency of the unigram in relation to possible words preceding it.

## Related

- [[Brown clustering]]
- [[Cache language model]]
- [[Distributional–relational database]]
- [[EleutherAI]]
- [[Factored language model]]
- [[Foundation model]]
- [[Geospatial foundation model]]
- [[Hallucination (artificial intelligence)]]
- [[Katz's back-off model]]
- [[Lancichinetti–Fortunato–Radicchi benchmark]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Kneser–Ney_smoothing