---
title: "Non-local means"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Non-local_means"
wikipedia_categories: ["Image noise reduction techniques", "Image processing"]
related: ["[[Anisotropic diffusion]]", "[[Bilateral filter]]", "[[Gaussian blur]]", "[[Guided filter]]", "[[3D selfie]]", "[[Abel transform]]", "[[ActionShot]]", "[[Acutance]]", "[[Adaptive histogram equalization]]", "[[Albert Bijaoui]]"]
---

# Non-local means

Non-local means is an algorithm in image processing for image denoising. Unlike "local mean" filters, which take the mean value of a group of pixels surrounding a target pixel to smooth the image, non-local means filtering takes a mean of all pixels in the image, weighted by how similar these pixels are to the target pixel. This results in much greater post-filtering clarity, and less loss of detail in the image compared with local mean algorithms.
If compared with other well-known denoising techniques, non-local means adds "method noise" (i.e. error in the denoising process) which looks more like white noise, which is desirable because it is typically less disturbing in the denoised product. Recently non-local means has been extended to other image processing applications such as deinterlacing, view interpolation, and depth maps regularization.

## Related

- [[Anisotropic diffusion]]
- [[Bilateral filter]]
- [[Gaussian blur]]
- [[Guided filter]]
- [[3D selfie]]
- [[Abel transform]]
- [[ActionShot]]
- [[Acutance]]
- [[Adaptive histogram equalization]]
- [[Albert Bijaoui]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Non-local_means