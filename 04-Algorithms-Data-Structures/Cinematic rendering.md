---
title: "Cinematic rendering"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Cinematic_rendering"
wikipedia_categories: ["3D computer graphics", "3D rendering", "Computer graphic techniques", "Computer graphics algorithms", "DICOM software", "Medical diagnosis", "Medical imaging", "Medical imaging stubs"]
related: ["[[Computed Corpuscle Sectioning]]", "[[Diagnostically acceptable irreversible compression]]", "[[Fiducial marker]]", "[[Gaussian splatting]]", "[[Image-based meshing]]", "[[Isosurface]]", "[[Marching cubes]]", "[[Newell's algorithm]]", "[[Painter's algorithm]]", "[[Reflection (computer graphics)]]"]
---

# Cinematic rendering

In medical diagnostics, cinematic rendering is an image processing technique applied to create three-dimensional, photorealistic images of cross-sectional data, such as computed-tomography, or magnetic resonance imaging (MRI)/ Cinematic rendering is an alternative to the volume rendering, the name was inspired by the modern computer animation techniques that allow studios, like Pixar, to create realistically looking objects.
The steps used to produce the cinematic rendering are similar to the ones for the volume rendering:

the magnitude (gray) value of each voxel (3-dimensional pixel) produced during the scan is mapped into the color and opacity pair based on what structures need to be highlighted or hidden;
ray casting used for volume rendering, where each pixel in the 2D image is formed by a single ray of light, is replaced by path tracing with a global illumination model that integrates over all the illuminance arriving to every single point on the surface of an object.
Since the number of light paths in this technique is nearly unlimited, a finite randomized selection of the paths and importance sampling are used to imitate the real-life propagation of light, scattering, and reflection using models build on real-life data. The result is a photorealistic image.

## Related

- [[Computed Corpuscle Sectioning]]
- [[Diagnostically acceptable irreversible compression]]
- [[Fiducial marker]]
- [[Gaussian splatting]]
- [[Image-based meshing]]
- [[Isosurface]]
- [[Marching cubes]]
- [[Newell's algorithm]]
- [[Painter's algorithm]]
- [[Reflection (computer graphics)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Cinematic_rendering