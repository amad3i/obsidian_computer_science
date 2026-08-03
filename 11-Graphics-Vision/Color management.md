---
title: "Color management"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Color_management"
wikipedia_categories: ["Color", "Computer graphics"]
related: ["[[2D computer graphics]]", "[[3D computer graphics]]", "[[3D lookup table]]", "[[4D reconstruction]]", "[[9-slice scaling]]", "[[A-buffer]]", "[[ACM Transactions on Graphics]]", "[[Adaptive tile refresh]]", "[[Bitmap textures]]", "[[Blanking (video)]]"]
---

# Color management

Color management is the process of ensuring consistent and accurate colors across various devices, such as monitors, printers, and cameras. It involves the use of color profiles, which are standardized descriptions of how colors should be displayed or reproduced.
Color management is necessary because different devices have different color capabilities and characteristics. For example, a monitor may display colors differently than a printer can reproduce them. Without color management, the same image may appear differently on different devices, leading to inconsistencies and inaccuracies.
To achieve color management, a color profile is created for each device involved in the color workflow. This profile describes the device's color capabilities and characteristics, such as its color gamut (range of colors it can display or reproduce) and color temperature. These profiles are then used to translate colors between devices, ensuring consistent and accurate color reproduction.
Color management is particularly important in industries such as graphic design, photography, and printing, where accurate color representation is crucial. It helps to maintain color consistency throughout the entire workflow, from capturing an image to displaying or printing it.
Parts of color management are implemented in the operating system (OS), helper libraries, the application, and devices. The type of color profile that is typically used is called an ICC profile. A cross-platform view of color management is the use of an ICC-compatible color management system. The International Color Consortium (ICC) is an industry consortium that has defined:

an open standard for a Color Matching Module (CMM) at the OS level
color profiles for:
devices, including DeviceLink profiles that transform one device profile (color space) to another device profile without passing through an intermediate color space, such as L*A*B*, more accurately preserving color
working spaces, the color spaces in which color data is meant to be manipulated
There are other approaches to color management besides using ICC profiles. This is partly due to history and partly because of other needs than the ICC standard covers. The film and broadcasting industries make use of some of the same concepts, but they frequently rely on more limited boutique solutions. The film industry, for instance, often uses 3D LUTs (lookup table) to represent a complete color transformation for a specific RGB encoding.
At the consumer level, system wide color management is available in most of Apple's products (macOS, iOS, iPadOS, watchOS). Microsoft Windows lacks system wide color management and virtually all applications do not employ color management. Windows' media player API is not color space aware, and if applications want to color manage videos manually, they have to incur significant performance and power consumption penalties. Android supports system wide color management, but most devices ship with color management disabled.

## Related

- [[2D computer graphics]]
- [[3D computer graphics]]
- [[3D lookup table]]
- [[4D reconstruction]]
- [[9-slice scaling]]
- [[A-buffer]]
- [[ACM Transactions on Graphics]]
- [[Adaptive tile refresh]]
- [[Bitmap textures]]
- [[Blanking (video)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Color_management