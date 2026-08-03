---
title: "PlaidML"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/PlaidML"
wikipedia_categories: ["Compilers", "Tensors"]
related: ["[[Absoft]]", "[[Accelerated Linear Algebra]]", "[[Ahead-of-time compilation]]", "[[Apple Dylan]]", "[[Arden2ByteCode]]", "[[Ark Compiler]]", "[[Banerjee test]]", "[[Binary optimizer]]", "[[Binary recompiler]]", "[[Bootstrapping (compilers)]]"]
---

# PlaidML

PlaidML is a portable tensor compiler. Tensor compilers bridge the gap between the universal mathematical descriptions of deep learning operations, such as convolution, and the platform and chip-specific code needed to perform those operations with good performance. Internally, PlaidML makes use of the Tile eDSL  to generate OpenCL, OpenGL, LLVM, or CUDA code. It enables deep learning on devices where the available computing hardware is either not well supported or the available software stack contains only proprietary components. For example, it does not require the usage of CUDA or cuDNN on Nvidia hardware, while achieving comparable performance.
PlaidML supports the machine learning libraries Keras, ONNX, and nGraph. However, Keras have dropped support of multiple backends and latest Keras version isn't compatible with PlaidML. An integration with Tensorflow-Keras is planned as a replacement for Keras.

## Related

- [[Absoft]]
- [[Accelerated Linear Algebra]]
- [[Ahead-of-time compilation]]
- [[Apple Dylan]]
- [[Arden2ByteCode]]
- [[Ark Compiler]]
- [[Banerjee test]]
- [[Binary optimizer]]
- [[Binary recompiler]]
- [[Bootstrapping (compilers)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/PlaidML