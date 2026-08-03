---
title: "Linux color management"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Linux_color_management"
wikipedia_categories: ["Computer graphics"]
related: ["[[2D computer graphics]]", "[[3D computer graphics]]", "[[3D lookup table]]", "[[4D reconstruction]]", "[[9-slice scaling]]", "[[A-buffer]]", "[[ACM Transactions on Graphics]]", "[[Adaptive tile refresh]]", "[[Bitmap textures]]", "[[Blanking (video)]]"]
---

# Linux color management

Linux color management has the same goal as the color management systems (CMS) for other operating systems, which is to achieve the best possible color reproduction throughout an imaging workflow from its source (camera, video, scanner, etc.), through imaging software (Digikam, darktable, RawTherapee, GIMP, Krita, Scribus, etc.), and finally onto an output medium (monitor, video projector, printer, etc.). In particular, color management attempts to enable color consistency across media and throughout a color-managed workflow.
Linux color management relies on the use of accurate ICC (International Color Consortium) and DCP (DNG Color Profile) profiles describing the behavior of input and output devices, and color-managed applications that are aware of these profiles. These applications perform gamut conversions between device profiles and color spaces. Gamut conversions, based on accurate device profiles, are the essence of color management.
Historically, color management was not an initial design consideration of the X Window System on which much of Linux graphics support rests, and thus color-managed workflows have been somewhat more challenging to implement on Linux than on other OS's such as Microsoft Windows or macOS. This situation is now being progressively remedied, and color management under Linux, while functional, has not yet acquired mature status. Although it is now possible to obtain a consistent color-managed workflow under Linux, certain problems still remain:

The absence of a central user control panel for color settings.
Some hardware devices for color calibration lack Linux drivers, firmware or accessory data.
Since ICC color profiles are written to an open specification, they are compatible across operating systems. Hence, a profile produced on one OS should work on any other OS given the availability of the necessary software to read it and perform the gamut conversions. This can be used as a workaround for the lack of support for certain spectrophotometers or colorimeters under Linux: one can simply produce a profile on a different OS and then use it in a Linux workflow. Additionally, certain hardware, such as most printers and certain monitors, can be calibrated under another OS and then used in a fully color-managed workflow on Linux.
The popular Ubuntu Linux distribution added initial color management in the 11.10 release (the "Oneiric Ocelot" release).

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

- Wikipedia: https://en.wikipedia.org/wiki/Linux_color_management