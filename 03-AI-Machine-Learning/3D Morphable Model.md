---
title: "3D Morphable Model"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/3D_Morphable_Model"
wikipedia_categories: ["3D computer graphics", "Computer vision"]
related: ["[[3D reconstruction]]", "[[3D scanning]]", "[[3D body scanning]]", "[[3D city model]]", "[[3D computer graphics]]", "[[3D Content Retrieval]]", "[[3D modeling]]", "[[3D pose estimation]]", "[[3D projection]]", "[[3D selfie]]"]
---

# 3D Morphable Model

In computer vision and computer graphics, the 3D Morphable Model (3DMM) is a generative technique that uses methods of statistical shape analysis to model 3D objects. The model follows an analysis-by-synthesis approach over a dataset of 3D example shapes of a single class of objects (e.g., face, hand). The main prerequisite is that all the 3D shapes are in a dense point-to-point correspondence, namely each point has the same semantical meaning over all the shapes. In this way, we can extract meaningful statistics from the dataset and use them to represent new plausible shapes of the object's class. Given a 2D image, we can represent its 3D shape via a fitting process or generate novel shapes by directly sampling from the statistical shape distribution of that class. 
The question that initiated the research on 3DMMs was to understand how a visual system could handle the vast variety of images produced by a single class of objects and how these can be represented. The primary assumption in developing 3DMMs was that prior knowledge about object classes was crucial in vision. 3D Face Morphable Models are the most popular 3DMMs since they were the first to be developed in the field of facial recognition. It has also been applied to the whole human body, the hand, the ear, cars, and animals.

## Related

- [[3D reconstruction]]
- [[3D scanning]]
- [[3D body scanning]]
- [[3D city model]]
- [[3D computer graphics]]
- [[3D Content Retrieval]]
- [[3D modeling]]
- [[3D pose estimation]]
- [[3D projection]]
- [[3D selfie]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/3D_Morphable_Model