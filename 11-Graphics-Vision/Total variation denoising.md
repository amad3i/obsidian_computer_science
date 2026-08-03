---
title: "Total variation denoising"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Total_variation_denoising"
wikipedia_categories: ["Image processing", "Nonlinear filters", "Partial differential equations"]
related: ["[[3D selfie]]", "[[Abel transform]]", "[[ActionShot]]", "[[Acutance]]", "[[Adaptive filter]]", "[[Adaptive histogram equalization]]", "[[Albert Bijaoui]]", "[[Alpha to coverage]]", "[[Analog image processing]]", "[[Anisotropic diffusion]]"]
---

# Total variation denoising

In signal processing, particularly image processing, total variation denoising, also known as total variation regularization or total variation filtering, is a noise removal process (filter). It is based on the principle that signals with excessive and possibly spurious detail have high total variation, that is, the integral of the image gradient magnitude is high. According to this principle, reducing the total variation of the signal—subject to it being a close match to the original signal—removes unwanted detail whilst preserving important details such as edges. The concept was pioneered by L. I. Rudin, S. Osher, and E. Fatemi in 1992 and so is today known as the ROF model.
This noise removal technique has advantages over simple techniques such as linear smoothing or median filtering which reduce noise but at the same time smooth away edges to a greater or lesser degree. By contrast, total variation denoising is a remarkably effective edge-preserving filter, i.e., simultaneously preserving edges whilst smoothing away noise in flat regions, even at low signal-to-noise ratios.

## Related

- [[3D selfie]]
- [[Abel transform]]
- [[ActionShot]]
- [[Acutance]]
- [[Adaptive filter]]
- [[Adaptive histogram equalization]]
- [[Albert Bijaoui]]
- [[Alpha to coverage]]
- [[Analog image processing]]
- [[Anisotropic diffusion]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Total_variation_denoising