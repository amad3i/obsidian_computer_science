---
title: "Approximate computing"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Approximate_computing"
wikipedia_categories: ["Approximations", "Computer architecture", "Software optimization"]
related: ["[[Abstraction layer]]", "[[Address space]]", "[[Addressing mode]]", "[[Analytical Performance Modeling]]", "[[Aperture (computer memory)]]", "[[Approximation]]", "[[Arithmetic logic unit]]", "[[Autonomous decentralized system]]", "[[Berkeley IRAM project]]", "[[Binary optimizer]]"]
---

# Approximate computing

Approximate computing is an emerging paradigm for energy-efficient and/or high-performance design. It includes a plethora of computation techniques that return a possibly inaccurate result rather than a guaranteed accurate result, and that can be used for applications where an approximate result is sufficient for its purpose. One example of such situation is for a search engine where no exact answer may exist for a certain search query and hence, many answers may be acceptable. Similarly, occasional dropping of some frames in a video application can go undetected due to perceptual limitations of humans. Approximate computing is based on the observation that in many scenarios, although performing exact computation requires large amount of resources, allowing bounded approximation can provide disproportionate gains in performance and energy, while still achieving acceptable result accuracy.  For example, in k-means clustering algorithm, allowing only 5% loss in classification accuracy can provide 50 times energy saving compared to the fully accurate classification.
The key requirement in approximate computing is that approximation can be introduced only in non-critical data, since approximating critical data (e.g., control operations) can lead to disastrous consequences, such as program crash or erroneous output.

## Related

- [[Abstraction layer]]
- [[Address space]]
- [[Addressing mode]]
- [[Analytical Performance Modeling]]
- [[Aperture (computer memory)]]
- [[Approximation]]
- [[Arithmetic logic unit]]
- [[Autonomous decentralized system]]
- [[Berkeley IRAM project]]
- [[Binary optimizer]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Approximate_computing