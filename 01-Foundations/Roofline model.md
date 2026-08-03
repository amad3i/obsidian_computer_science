---
title: "Roofline model"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Roofline_model"
wikipedia_categories: ["Software optimization", "Software testing"]
related: ["[[Analytical Performance Modeling]]", "[[OctoPerf]]", "[[Software performance testing]]", "[[-dev-full]]", "[[A-B testing]]", "[[Acceptance test-driven development]]", "[[Acceptance testing]]", "[[Ad hoc testing]]", "[[Agent verification]]", "[[Agile testing]]"]
---

# Roofline model

The roofline model is an intuitive visual performance model used to provide performance estimates of a given compute kernel or application running on multi-core, many-core, or accelerator processor architectures, by showing inherent hardware limitations, and potential benefit and priority of optimizations. By combining locality, bandwidth, and different parallelization paradigms into a single performance figure, the model can be an effective alternative to assess the quality of attained performance instead of using simple percent-of-peak estimates, as it provides insights on both the implementation and inherent performance limitations.
The most basic roofline model can be visualized by plotting floating-point performance as a function of machine peak performance, machine peak bandwidth, and arithmetic intensity. The resultant curve is effectively a performance bound under which kernel or application performance exists, and includes two platform-specific performance ceilings: a ceiling derived from the memory bandwidth and one derived from the processor's peak performance (see figure on the right).

## Related

- [[Analytical Performance Modeling]]
- [[OctoPerf]]
- [[Software performance testing]]
- [[-dev-full]]
- [[A-B testing]]
- [[Acceptance test-driven development]]
- [[Acceptance testing]]
- [[Ad hoc testing]]
- [[Agent verification]]
- [[Agile testing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Roofline_model