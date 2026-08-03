---
title: "Super-resolution optical fluctuation imaging"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Super-resolution_optical_fluctuation_imaging"
wikipedia_categories: ["Covariance and correlation", "Image processing", "Optical microscopy"]
related: ["[[3D selfie]]", "[[Abel transform]]", "[[ActionShot]]", "[[Acutance]]", "[[Adaptive histogram equalization]]", "[[Albert Bijaoui]]", "[[Alpha to coverage]]", "[[Analog image processing]]", "[[Anisotropic diffusion]]", "[[Atkinson dithering]]"]
---

# Super-resolution optical fluctuation imaging

Super-resolution optical fluctuation imaging (SOFI) is a post-processing method for the calculation of super-resolved images from recorded image time series that is based on the temporal correlations of independently fluctuating fluorescent emitters.
SOFI has been developed for super-resolution of biological specimen that are labelled with independently fluctuating fluorescent emitters (organic dyes, fluorescent proteins). In comparison to other super-resolution microscopy techniques such as STORM or PALM that rely on single-molecule localization and hence only allow one active molecule per diffraction-limited area (DLA) and timepoint, SOFI does not necessitate a controlled photoswitching and/ or photoactivation as well as long imaging times. Nevertheless, it still requires fluorophores that are cycling through two distinguishable states, either real on-/off-states or states with different fluorescence intensities. In mathematical terms SOFI-imaging relies on the calculation of cumulants, for what two distinguishable ways exist. For one thing an image can be calculated via auto-cumulants that by definition only rely on the information of each pixel itself, and for another thing an improved method utilizes the information of different pixels via the calculation of cross-cumulants. Both methods can increase the final image resolution significantly although the cumulant calculation has its limitations. Actually SOFI is able to increase the resolution in all three dimensions.

## Related

- [[3D selfie]]
- [[Abel transform]]
- [[ActionShot]]
- [[Acutance]]
- [[Adaptive histogram equalization]]
- [[Albert Bijaoui]]
- [[Alpha to coverage]]
- [[Analog image processing]]
- [[Anisotropic diffusion]]
- [[Atkinson dithering]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Super-resolution_optical_fluctuation_imaging