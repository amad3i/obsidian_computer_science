---
title: "Visual hull"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Visual_hull"
wikipedia_categories: ["3D imaging", "Computer graphics", "Convex hull algorithms", "Geometry in computer vision", "Photogrammetry", "Projective geometry"]
related: ["[[3D computer graphics]]", "[[3D projection]]", "[[3D selfie]]", "[[4D reconstruction]]", "[[Image-based modeling and rendering]]", "[[Photometric stereo]]", "[[Superellipsoid]]", "[[Superquadrics]]", "[[T-pose]]", "[[View synthesis]]"]
---

# Visual hull

A visual hull is a geometric entity created by shape-from-silhouette 3D reconstruction technique introduced by A. Laurentini. 
This technique assumes the foreground object in an image can be separated from the background. Under this assumption, the original image can be thresholded into a foreground/background binary image, which we call a silhouette image. The foreground mask, known as a silhouette, is the 2D projection of the corresponding 3D foreground object. Along with the camera viewing parameters, the silhouette defines a back-projected generalized cone that contains the actual object; this cone is called a silhouette cone. 
The intersection of the two silhouette cones defines a visual hull. which is a bounding geometry of the actual 3D object. When the reconstructed geometry is only used for rendering from a different viewpoint, the implicit reconstruction together with rendering can be done using graphics hardware.

## Related

- [[3D computer graphics]]
- [[3D projection]]
- [[3D selfie]]
- [[4D reconstruction]]
- [[Image-based modeling and rendering]]
- [[Photometric stereo]]
- [[Superellipsoid]]
- [[Superquadrics]]
- [[T-pose]]
- [[View synthesis]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Visual_hull