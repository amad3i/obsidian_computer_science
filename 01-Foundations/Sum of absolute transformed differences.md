---
title: "Sum of absolute transformed differences"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Sum_of_absolute_transformed_differences"
wikipedia_categories: ["Loss functions", "Signal processing metrics", "Video compression"]
related: ["[[Sum of absolute differences]]", "[[Discrete cosine transform]]", "[[Hinge loss]]", "[[Huber loss]]", "[[Loss function]]", "[[Mean squared error]]", "[[Mean squared prediction error]]", "[[Taguchi loss function]]", "[[Variance Adaptive Quantization]]"]
---

# Sum of absolute transformed differences

The sum of absolute transformed differences (SATD) is a block matching criterion widely used in fractional motion estimation for video compression.  It works by taking a frequency transform, usually a Hadamard transform, of the differences between the pixels in the original block and the corresponding pixels in the block being used for comparison.  The transform itself is often of a small block rather than the entire macroblock.  For example, in x264, a series of 4×4 blocks are transformed rather than doing the more processor-intensive 16×16 transform.

## Related

- [[Sum of absolute differences]]
- [[Discrete cosine transform]]
- [[Hinge loss]]
- [[Huber loss]]
- [[Loss function]]
- [[Mean squared error]]
- [[Mean squared prediction error]]
- [[Taguchi loss function]]
- [[Variance Adaptive Quantization]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sum_of_absolute_transformed_differences