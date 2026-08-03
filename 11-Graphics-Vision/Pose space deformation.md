---
title: "Pose space deformation"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Pose_space_deformation"
wikipedia_categories: ["Animation stubs", "Animation techniques", "Computer animation", "Computer graphics", "Computer graphics stubs"]
related: ["[[Computer animation]]", "[[4D reconstruction]]", "[[Avar (animation variable)]]", "[[Cel shading]]", "[[Color clock]]", "[[Color cycling]]", "[[Colour banding]]", "[[Computer Animation and Social Agents]]", "[[Czekanowski distance]]", "[[Depth peeling]]"]
---

# Pose space deformation

Pose space deformation is a computer animation technique which is used to deform a mesh on skeleton-driven animation. Common use of this technique is to deform the shape of a mesh (for example, an arm) according to the angle of the joint (in this case, the elbow) bent. Although the name is commonly called Pose space deformation on many scholarly articles, 3D animation software rarely uses that name. On Autodesk Maya, it's implemented under the name Pose Deformer, and on Blender, it's implemented as Corrective Shape Keys. The first famous application of this technique was the cloth's movement on the first episode of the animated film The Animatrix. Industrial Light & Magic used a linear variant of this approach as one of the tools to animate the Hulk for The Avengers movie.
Fundamentally, pose space deformation (PSD) poses animation as an alternative class of interpolation. Rather than interpolate in time, as with animation curves, or over space, as with meshes, PSD views animation as interpolation over the domain of the character's pose.  PSD was an early use of machine learning and neural networks in computer graphics: the radial basis interpolation that is often used to implement PSD is equivalent to a neural network with a radial nonlinearity.

## Related

- [[Computer animation]]
- [[4D reconstruction]]
- [[Avar (animation variable)]]
- [[Cel shading]]
- [[Color clock]]
- [[Color cycling]]
- [[Colour banding]]
- [[Computer Animation and Social Agents]]
- [[Czekanowski distance]]
- [[Depth peeling]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Pose_space_deformation