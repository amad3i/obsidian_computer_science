---
title: "Cascading classifiers"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Cascading_classifiers"
wikipedia_categories: ["Classification algorithms", "Ensemble learning"]
related: ["[[AdaBoost]]", "[[Boosting (machine learning)]]", "[[BrownBoost]]", "[[Gradient boosting]]", "[[LogitBoost]]", "[[Random subspace method]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[ALOPEX]]", "[[Alternating decision tree]]", "[[Analogical modeling]]"]
---

# Cascading classifiers

Cascading is a particular case of ensemble learning based on the concatenation of several classifiers, using all information collected from the output from a given classifier as additional information for the next classifier in the cascade. Unlike voting or stacking ensembles, which are multiexpert systems, cascading is a multistage one.
Cascading classifiers are trained with several hundred "positive" sample views of a particular object and arbitrary "negative" images of the same size. After the classifier is trained it can be applied to a region of an image and detect the object in question. To search for the object in the entire frame, the search window can be moved across the image and check every location with the classifier. This process is most commonly used in image processing for object detection and tracking, primarily facial detection and recognition.
The first cascading classifier was the face detector of Viola and Jones (2001). The requirement for this classifier was to be fast in order to be implemented on low-power CPUs, such as cameras and phones.

## Related

- [[AdaBoost]]
- [[Boosting (machine learning)]]
- [[BrownBoost]]
- [[Gradient boosting]]
- [[LogitBoost]]
- [[Random subspace method]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[ALOPEX]]
- [[Alternating decision tree]]
- [[Analogical modeling]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Cascading_classifiers