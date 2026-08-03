---
title: "Cepstral mean and variance normalization"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Cepstral_mean_and_variance_normalization"
wikipedia_categories: ["Computer science stubs", "Speech recognition"]
related: ["[[ACL Data Collection Initiative]]", "[[Acoustic model]]", "[[Alewife (multiprocessor)]]", "[[ALF (proof assistant)]]", "[[Analog image processing]]", "[[Apptek]]", "[[AQUA@home]]", "[[Articulatory speech recognition]]", "[[Artificial intelligence content detection]]", "[[Asynchrony (computer programming)]]"]
---

# Cepstral mean and variance normalization

Cepstral mean and variance normalization (CMVN) is a computationally efficient normalization technique for robust speech recognition. The performance of CMVN is known to degrade for short utterances. This is due to insufficient data for parameter estimation and loss of discriminable information as all utterances are forced to have zero mean and unit variance. 
CMVN minimizes distortion by noise contamination for robust feature extraction by linearly transforming the cepstral coefficients to have the same segmental statistics.  Cepstral Normalization has been effective in the CMU Sphinx for maintaining a high level of recognition accuracy over a wide variety of acoustical environments.

## Related

- [[ACL Data Collection Initiative]]
- [[Acoustic model]]
- [[Alewife (multiprocessor)]]
- [[ALF (proof assistant)]]
- [[Analog image processing]]
- [[Apptek]]
- [[AQUA@home]]
- [[Articulatory speech recognition]]
- [[Artificial intelligence content detection]]
- [[Asynchrony (computer programming)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Cepstral_mean_and_variance_normalization