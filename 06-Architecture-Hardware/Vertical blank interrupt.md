---
title: "Vertical blank interrupt"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Vertical_blank_interrupt"
wikipedia_categories: ["Video game development"]
related: ["[[2.5D]]", "[[2022–2026 video game industry layoffs]]", "[[AAA (video game industry)]]", "[[AbleGamers]]", "[[Academy of Interactive Arts & Sciences]]", "[[Amazon Lumberyard]]", "[[Artificial intelligence in video games]]", "[[Asset flip]]", "[[Atari 2600 homebrew]]", "[[Australian Game Developers Conference]]"]
---

# Vertical blank interrupt

A vertical blank interrupt (also known as a vertical blanking interrupt, vertical retrace interrupt or abbreviations of these such as VBL or VBI) is a hardware feature found in many older computer systems that generate a video signal. Video display circuits must generate vertical blanking and vertical sync pulses to indicate the start of each field within the video signal. With VBI, the display circuitry also generates an interrupt request for the computer's microprocessor at the start of the vertical blanking period.
As no display information is being transmitted to the display during the vertical blanking period, an interrupt service routine for the vertical blanking interrupt can make changes to the displayed image or to the configuration of the display without the effects being immediately visible on screen. This can be used in a variety of ways to achieve smooth animation without screen tearing artefacts. For simple animation, it was possible to do all of the drawing within the limited time available during the vertical blanking period. For more complex animation, the vertical blank interrupt handler could be used to switch buffers in a double-buffering scheme, or to configure a graphics coprocessor that would generate the display as it was being output. Some systems also support a horizontal blank interrupt, which allows more elaborate interrupt-driven techniques such as sprite multiplexing.
As the VBI will be generated at the start of every displayed field (50 Hz for PAL, approximately 60 Hz for NTSC), it is a useful timebase in systems lacking other timing sources. VBIs are used in some home computers to perform regular functions like scanning the keyboard, mouse and joystick ports. In a more complex operating system, the VBI may be used as a clock source for task switching or to trigger periodic background jobs.
VBIs became less important in graphics programming on general-purpose computers in the 1990s, as multitasking operating systems no longer provide direct address to hardware features, and modern graphics libraries provide higher-level ways of achieving smooth animation. For examples of computers that support VBIs, see raster interrupt.

## Related

- [[2.5D]]
- [[2022–2026 video game industry layoffs]]
- [[AAA (video game industry)]]
- [[AbleGamers]]
- [[Academy of Interactive Arts & Sciences]]
- [[Amazon Lumberyard]]
- [[Artificial intelligence in video games]]
- [[Asset flip]]
- [[Atari 2600 homebrew]]
- [[Australian Game Developers Conference]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Vertical_blank_interrupt