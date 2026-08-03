---
title: "Tensor product model transformation"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Tensor_product_model_transformation"
wikipedia_categories: ["Control theory"]
related: ["[[4D-RCS Reference Model Architecture]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[American Automatic Control Council]]", "[[Anticausal system]]", "[[Artstein's theorem]]", "[[Asymptotic gain model]]"]
---

# Tensor product model transformation

In mathematics, the tensor product (TP) model transformation was proposed by Baranyi and Yam as key concept for higher-order singular value decomposition of functions. It transforms a function (which can be given via closed formulas or neural networks, fuzzy logic, etc.) into TP function form if such a transformation is possible. If an exact transformation is not possible, then the method determines a TP function that is an approximation of the given function. Hence, the TP model transformation can provide a trade-off between approximation accuracy and complexity.
A free MATLAB implementation of the TP model transformation can be downloaded at   or an old version of the toolbox is available at  MATLAB Central .  A key underpinning of the transformation is the higher-order singular value decomposition.
Besides being a transformation of functions, the TP model transformation is also a new concept in qLPV based control which plays a central role in the providing a valuable means of bridging between identification and polytopic systems theories. The TP model transformation is uniquely effective in manipulating the convex hull of polytopic forms, and, as a result has revealed and proved the fact that convex hull manipulation is a necessary and crucial step in achieving optimal solutions and decreasing conservativeness in modern LMI based control theory. Thus, although it is a transformation in a mathematical sense, it has established a conceptually new direction in control theory and has laid the ground for further new approaches towards optimality. Further details on the control theoretical aspects of the TP model transformation can be found here: TP model transformation in control theory.
The TP model transformation motivated the definition of the "HOSVD canonical form of TP functions", on which further information can be found here. It has been proved that the TP model transformation is capable of numerically reconstructing this HOSVD based canonical form. Thus, the TP model transformation can be viewed as a numerical method to compute the HOSVD of functions, which provides exact results if the given function has a TP function structure and approximative results otherwise.
The TP model transformation has recently been extended in order to derive various types of convex TP functions and to manipulate them. This feature has led to new optimization approaches in qLPV system analysis and design, as described at TP model transformation in control theory.

## Related

- [[4D-RCS Reference Model Architecture]]
- [[Ackermann's formula]]
- [[Active disturbance rejection control]]
- [[Adaptive control]]
- [[Advanced process control]]
- [[Affect control theory]]
- [[American Automatic Control Council]]
- [[Anticausal system]]
- [[Artstein's theorem]]
- [[Asymptotic gain model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Tensor_product_model_transformation