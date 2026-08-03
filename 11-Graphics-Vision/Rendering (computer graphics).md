---
title: "Rendering (computer graphics)"
tags: ["cs", "graphics-vision", "core"]
domain: Graphics & Vision
level: core
source: "https://en.wikipedia.org/wiki/Rendering_(computer_graphics)"
wikipedia_categories: ["3D rendering"]
related: ["[[Cinematic rendering]]", "[[Floating origin]]", "[[Gaussian splatting]]", "[[Graphics pipeline]]", "[[Non-photorealistic rendering]]", "[[Path tracing]]", "[[Spatiotemporal reservoir resampling]]", "[[Stencil buffer]]", "[[Texture atlas]]", "[[Volumetric lighting]]"]
---

# Rendering (computer graphics)

Rendering is the process of generating an image from input data such as 3D models. The word "rendering" (in one of its senses) originally meant the task performed by an artist when depicting a real or imaginary thing (the finished artwork is also called a "rendering"). Today, to "render" commonly means to use a computer to generate an image from a precise specification, often created by an artist (or multiple artists) via interactive 3D modeling software. Types of images rendered include both still images and frames for films and video games.
In a computer graphics context, in standard usage, the word "rendering" by itself means rendering 3D scenes, but it is sometimes used with a broader meaning. A modifier such as "2D" or "3D" is used when there is potential ambiguity (e.g. 3D rendering).
A software application or component that performs rendering is called a rendering engine, render engine, rendering system, graphics engine, or simply a renderer.
A distinction is made between real-time rendering, in which images are generated and displayed immediately (ideally fast enough to give the impression of motion or animation), and offline rendering (sometimes called pre-rendering) in which images or film frames, are generated for later viewing. Offline rendering can use a slower and higher-quality renderer. Interactive applications such as games must primarily use real-time rendering, although they may incorporate pre-rendered content.
Rendering produces images of scenes or objects defined using coordinates in 3D space, seen from a particular viewpoint. It uses knowledge and ideas from optics, the study of visual perception, mathematics, and software engineering, and it has applications such as video games, simulators, visual effects for films and television, design visualization, and medical diagnosis. Realistic rendering requires modeling the propagation of light in an environment, e.g. by applying the rendering equation.
Real-time rendering uses high-performance rasterization algorithms that process a list of shapes and determine which pixels are covered by each shape. When more realism is required (e.g. for architectural visualization or visual effects) slower pixel-by-pixel algorithms such as ray tracing are used instead. (Ray tracing can also be used selectively during rasterized rendering to improve the realism of lighting and reflections.) A type of ray tracing called path tracing is currently the most common technique for photorealistic rendering. Path tracing is also popular for generating high-quality non-photorealistic images, such as frames for 3D animated films. Both rasterization and ray tracing can be sped up ("accelerated") by specially designed microprocessors called GPUs.
Rasterization algorithms are also used to produce images containing only 2D shapes such as polygons and text. This type of rendering is sometimes called 2D rendering, and its applications include digital illustration, graphic design, 2D animation, desktop publishing and the display of user interfaces.
Historically, rendering was called image synthesis but today this term is likely to mean AI image generation. The term "neural rendering" is sometimes used when a neural network is the primary means of generating an image but some degree of control over the output image is provided. Neural networks can also assist rendering without replacing traditional algorithms, e.g. by removing noise from path traced images.

Notes

== Features ==

=== Photorealistic rendering ===
A large proportion of computer graphics research has worked towards producing images that resemble photographs. Fundamental techniques that make this possible were invented in the 1980s, but at the end of the decade, photorealism for complex scenes was still considered a distant goal. Today, photorealism is routinely achievable for offline rendering, but remains difficult for real-time rendering.
In order to produce realistic images, rendering must simulate how light travels from light sources, is reflected, refracted, and scattered (often many times) by objects in the scene, passes through a camera lens, and finally reaches the film or sensor of the camera. The physics used in these simulations is primarily geometrical optics, in which particles of light follow (usually straight) lines called rays, but in some situations (such as when rendering thin films, like the surface of soap bubbles) the wave nature of light must be taken into account.
Effects that may need to be simulated include:

Shadows, including both shadows with sharp edges and soft shadows with umbra and penumbra
Reflections in mirrors and smooth surfaces, as well as rough or rippled reflective surfaces
Refraction –  the bending of light when it crosses a boundary between two transparent materials such as air and glass. The amount of bending varies with the wavelength of the light, which may cause colored fringes or "rainbows" to appear.
Volumetric effects –  absorption and scattering when light travels through partially transparent or translucent substances (called participating media because they modify the light rather than simply allow rays to pass through)
Caustics –  bright patches, sometimes with distinct filaments and a folded or twisted appearance, resulting when light is reflected or refracted before illuminating an object.
In realistic scenes, objects are illuminated both by light that arrives directly from a light source (after passing mostly unimpeded through air), and light that has bounced off other objects in the scene. The simulation of this complex lighting is called global illumination. In the past, indirect lighting was often faked (especially when rendering animated films) by placing additional hidden lights in the scene, but today path tracing is used to render it accurately.
For true photorealism, the camera used to take the photograph must be simulated. The thin lens approximation allows combining perspective projection with depth of field (and bokeh) emulation. Camera lens simulations can be made more realistic by modeling the way light is refracted by the components of the lens. Motion blur is often simulated if film or video frames are being rendered. Simulated lens flare and bloom are sometimes added to make the image appear subjectively brighter (although the design of real cameras tries to reduce these effects).
Realistic rendering uses mathematical descriptions of how different surface materials reflect light, called reflectance models or (when physically plausible) bidirectional reflectance distribution functions (BRDFs). Rendering materials such as marble, plant leaves, and human skin requires simulating an effect called subsurface scattering, in which a portion of the light travels into the material, is scattered, and then travels back out again. The way color, and properties such as roughness, vary over a surface can be represented efficiently using texture mapping.

=== Other styles of 3D rendering ===
For some applications (including early stages of 3D modeling), simplified rendering styles such as wireframe rendering may be appropriate, particularly when the material and surface details have not been defined and only the shape of an object is known. Games and other real-time applications may use simpler and less realistic rendering techniques as an artistic or design choice, or to allow higher frame rates on lower-end hardware.
Orthographic and isometric projections can be used for a stylized effect or to ensure that parallel lines are depicted as parallel in CAD rendering.
Non-photorealistic rendering (NPR) uses techniques like edge detection and posterization to produce 3D images that resemble technical illustrations, cartoons, or other styles of drawing or painting.

=== 2D rendering ===
In 2D computer graphics the positions and sizes of shapes are specified using 2D coordinates (x and y) instead of 3D coordinates (x, y, and z). 2D rendering APIs often use a resolution-independent coordinate system, with a viewport determining how to convert coordinates to pixel indexes called device coordinates. Transformations such as scaling, translation, and rotation may be applied before rendering the shapes. These affine transformations are often represented by 3 × 3 matrices, allowing easier composition of transformations.
Higher-quality 2D rendering engines such as SVG renderers usually implement anti-aliasing to reduce the jagged appearance of rasterized lines and shape edges. When rendering overlapping shapes, renderers commonly use a "painter's model" in which the shapes are drawn in some determined order, or their contributions to each pixel are composited using blending operations that may depend on the order of the inputs. Renderers may allow giving shapes a "z index" or "stacking order" to specify the rendering or blending order (unlike the z coordinate used in 3D rendering, this third coordinate only indicates an order, not a distance, and cannot be meaningfully rotated together

*(note truncated for size; full article at the source link below)*

## Related

- [[Cinematic rendering]]
- [[Floating origin]]
- [[Gaussian splatting]]
- [[Graphics pipeline]]
- [[Non-photorealistic rendering]]
- [[Path tracing]]
- [[Spatiotemporal reservoir resampling]]
- [[Stencil buffer]]
- [[Texture atlas]]
- [[Volumetric lighting]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Rendering_(computer_graphics)