---
title: "Asynchronous reprojection"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Asynchronous_reprojection"
wikipedia_categories: ["Computer graphics stubs", "Virtual reality"]
related: ["[[360 video projection]]", "[[360-degree video]]", "[[3D stereo view]]", "[[3D tracking]]", "[[4D reconstruction]]", "[[A-Frame (software)]]", "[[Advanced disaster management simulator]]", "[[Affective haptics]]", "[[AGX Dynamics]]", "[[Alpha to coverage]]"]
---

# Asynchronous reprojection

Asynchronous reprojection is a class of computer graphics technologies aimed at ensuring a virtual reality headset is responsive to user motion even when the GPU isn't able to keep up with the headset's target framerate, and to reduce perceived input lag at all times regardless of internal framerate. Reprojection involves the headset's driver taking one or multiple previously rendered frames and using newer motion information from the headset's sensors to extrapolate (often referred to as "reprojecting" or "warping") the previous frame into a prediction of what a normally rendered frame would look like. "Asynchronous" refers to this process being continuously performed in parallel with rendering, allowing synthesized frames to be displayed without delay in case a regular frame is not rendered in time, and reprojecting all frames by default to reduce perceived latency.
The use of these techniques allows for a lowering in the video rendering hardware specifications required to achieve a certain intended level of responsiveness.

## Related

- [[360 video projection]]
- [[360-degree video]]
- [[3D stereo view]]
- [[3D tracking]]
- [[4D reconstruction]]
- [[A-Frame (software)]]
- [[Advanced disaster management simulator]]
- [[Affective haptics]]
- [[AGX Dynamics]]
- [[Alpha to coverage]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Asynchronous_reprojection