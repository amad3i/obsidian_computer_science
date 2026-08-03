---
title: "One-class classification"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/One-class_classification"
wikipedia_categories: ["Classification algorithms", "Statistical classification"]
related: ["[[Calibration (statistics)]]", "[[Decision boundary]]", "[[K-nearest neighbors algorithm]]", "[[Linear classifier]]", "[[Linear discriminant analysis]]", "[[Margin classifier]]", "[[Multiclass classification]]", "[[Multiple discriminant analysis]]", "[[Quadratic classifier]]", "[[Statistical classification]]"]
---

# One-class classification

In machine learning, one-class classification (OCC), also known as unary classification or class-modelling, is an approach to the training of binary classifiers in which only examples of one of the two classes are used.
Examples include the monitoring of helicopter gearboxes, motor failure prediction, or assessing the operational status of a nuclear plant as 'normal': In such scenarios, there are few, if any, examples of the catastrophic system states – rare outliers – that comprise the second class. Alternatively, the class that is being focused on may cover a small, coherent subset of the data and the training may rely on an information bottleneck approach.
In practice, counter-examples from the second class may be used in later rounds of training to further refine the algorithm.

## Related

- [[Calibration (statistics)]]
- [[Decision boundary]]
- [[K-nearest neighbors algorithm]]
- [[Linear classifier]]
- [[Linear discriminant analysis]]
- [[Margin classifier]]
- [[Multiclass classification]]
- [[Multiple discriminant analysis]]
- [[Quadratic classifier]]
- [[Statistical classification]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/One-class_classification