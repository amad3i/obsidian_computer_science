---
title: "Feature recognition"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Feature_recognition"
wikipedia_categories: ["Computer-aided design"]
related: ["[[2D geometric model]]", "[[3D Content Retrieval]]", "[[3D floor plan]]", "[[3D Systems]]", "[[AgcXML]]", "[[Algorithms-Aided Design]]", "[[Architectural animation]]", "[[Architectural geometry]]", "[[Architectural illustration]]", "[[ASME Y14.41]]"]
---

# Feature recognition

The term "feature" implies different meanings in different engineering disciplines. This has resulted in many ambiguous definitions for feature. A feature, in computer-aided design (CAD), usually refers to a region of a part with some interesting geometric or topological properties. These are more precisely called form features. Form features contain both shape information and parametric information of a region of interest. They are now ubiquitous in most current CAD software, where they are used as the primary means of creating 3D geometric models. Examples of form features are extruded boss, loft, etc. Form feature is not the only type of feature that is discussed in CAD literature. Sometimes a part's functional or manufacturing features of the subject of attention. Although it is quite possible to see form features and manufacturing features are called by the same name, they are not exactly the same concepts. For example, one may either use the name "pocket" to refer to a swept cut on the boundary of a part model, or to refer to a trace left on the part boundary by a specific machining operation. The former is exclusively concerned with a geometric shape whereas the latter is concerned with both the geometric shape and a manufacturing operation, needing more parameters in its definition. As such, a manufacturing feature can be minimally defined as a form feature (if it has a form that can uniquely represent it), but not necessarily vice versa (forms can be interpreted differently in different manufacturing domains). Machining features are an important subset of manufacturing features. A machining feature can be regarded as the volume swept by a "cutting" tool, which is always a negative (subtracted) volume. Finally, there is also the concept of assembly feature, which encodes the assembly method between connected components.
Feature data in CAD can be specified either as a collection of surfaces or as volumes. Surface features can be used to describe manufacturing tolerances or locating surfaces in assembly design. Volumetric features on the other hand, can be used in tool path generation, etc. Manufacturing information (particularly in machining) is better portrayed by using volumetric features.
The first published work on features was for the original boundary representation modelling system, BUILD, and was performed by Lyc Kyprianou. Soon other work followed based on different solid representations. Overviews on the work on features can be found in Shah et al.; Subrahmanyam and Wozny; Salomons et al.

## Related

- [[2D geometric model]]
- [[3D Content Retrieval]]
- [[3D floor plan]]
- [[3D Systems]]
- [[AgcXML]]
- [[Algorithms-Aided Design]]
- [[Architectural animation]]
- [[Architectural geometry]]
- [[Architectural illustration]]
- [[ASME Y14.41]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Feature_recognition