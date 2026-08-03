---
title: "Moodbar"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Moodbar"
wikipedia_categories: ["Computer science stubs", "Data and information visualization software", "Music visualization software", "User interface techniques"]
related: ["[[Attentive user interface]]", "[[Focus-plus-context screen]]", "[[Progressive disclosure]]", "[[3D human–computer interaction]]", "[[Accelerator table]]", "[[Alewife (multiprocessor)]]", "[[ALF (proof assistant)]]", "[[Alt-Tab]]", "[[Amira (software)]]", "[[Analog image processing]]"]
---

# Moodbar

Moodbar is a computer visualization used for navigating within a piece of music or any other recording on a digital audio track. This is done with a commonly horizontal bar that is divided into vertical stripes. Each stripe has a colour combination showing the "mood" within a short part of the audio track. The colour can depend on spectrum and/or rhythmic features of the part of the track. If the audio is a song then various parts of it (intro, choruses, solos, accents etc.) as well as changes (dynamics, rhythm, texture, playing instruments) are differently coloured on the bar. If the audio is a speech or an interview then the moodbar displays different speaking segments in unique colour combinations. 
Moodbar was originally presented by Gavin Wood and Simon O’Keefe in their paper On Techniques for Content-Based Visual Annotation to Aid Intra-Track Music Navigation. 
Moodbar has been implemented for Amarok, Clementine, its fork Strawberry, and Exaile music players and the GJay smart playlist creator for Linux.
As of 2008, the default implementation of Amarok's moodbar only uses the spectral content of the current section of the track. It calculates the energy in the low, medium, and high frequency bands, and turns this into the amount of red, green, and blue in the corresponding stripe. Each moodbar file is 1000 samples long, which corresponds to roughly 4–5 samples every second for a typical 3–4 minute long song. This is not useful for telling anything about the rhythm of a song, but it is sometimes possible to guess where different instruments are playing. This can be useful for spotting verse, chorus, verse structure, and breaks in the music.

## Related

- [[Attentive user interface]]
- [[Focus-plus-context screen]]
- [[Progressive disclosure]]
- [[3D human–computer interaction]]
- [[Accelerator table]]
- [[Alewife (multiprocessor)]]
- [[ALF (proof assistant)]]
- [[Alt-Tab]]
- [[Amira (software)]]
- [[Analog image processing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Moodbar