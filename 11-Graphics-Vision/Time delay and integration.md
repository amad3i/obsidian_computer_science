---
title: "Time delay and integration"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Time_delay_and_integration"
wikipedia_categories: ["Image processing", "Image sensors"]
related: ["[[Charge-coupled device]]", "[[Minimum resolvable contrast]]", "[[3D selfie]]", "[[Abel transform]]", "[[ActionShot]]", "[[Acutance]]", "[[Adaptive histogram equalization]]", "[[Albert Bijaoui]]", "[[Alpha to coverage]]", "[[Analog image processing]]"]
---

# Time delay and integration

A time delay and integration or time delay integration (TDI) is a forward motion compensation (FMC) technique for capturing images of moving objects at low light levels. It's a type of line scanning where multiple linear arrays are placed side by side. After the first array is exposed, the charge is transferred to the neighboring line. When the object moves the distance of the separation between lines, a second exposure is taken on top of the first with the next array, and so on. Thus, each line of the object is imaged repeatedly, and the exposures are added to each other. This works by synchronized mechanical and electronic scanning, so that the effects of dim imaging targets on the sensor can be integrated over longer periods of time.
TDI is more of an operating mode of an image sensor than a separate type of imaging device altogether, even if technical optimizations for the mode are also available. The most used way to perform TDI is called dTDI from digital time delay integration, which is software-based and independent of the type of underlying imaging sensor. The principle behind TDI—constructive interference between separate observations—is often applicable to other sensor technologies, so that it is comparable to any long-term integrating mode of imaging, such as speckle imaging, adaptive optics, and especially long exposure astronomical observation.

## Related

- [[Charge-coupled device]]
- [[Minimum resolvable contrast]]
- [[3D selfie]]
- [[Abel transform]]
- [[ActionShot]]
- [[Acutance]]
- [[Adaptive histogram equalization]]
- [[Albert Bijaoui]]
- [[Alpha to coverage]]
- [[Analog image processing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Time_delay_and_integration