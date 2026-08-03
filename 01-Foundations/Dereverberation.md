---
title: "Dereverberation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Dereverberation"
wikipedia_categories: ["Acoustics", "Audio effects", "Digital signal processing"]
related: ["[[Audio normalization]]", "[[Dattorro industry scheme]]", "[[Digital delay line]]", "[[Digital room correction]]", "[[Fourier analysis]]", "[[Head-related transfer function]]", "[[Outboard gear]]", "[[Steered-response power]]", "[[Virtual acoustic space]]", "[[2D adaptive filters]]"]
---

# Dereverberation

Dereverberation is the process by which the effects of reverberation are removed from sound, after such reverberant sound has been picked up by microphones. Dereverberation is a subtopic of acoustic digital signal processing and is most commonly applied to speech but also has relevance in some aspects of music processing. Dereverberation of audio (speech or music) is a corresponding function to blind deconvolution of images, although the techniques used are usually very different. Reverberation itself is caused by sound reflections in a room (or other enclosed space) and is quantified by the room reverberation time and the direct-to-reverberant ratio. The effect of dereverberation is to increase the direct-to-reverberant ratio so that the sound is perceived as closer and clearer.
A main application of dereverberation is in hands-free phones and desktop conferencing terminals because, in these cases, the microphones are not close to the source of sound – the talker’s mouth – but at arm’s length or further distance. As well as telecommunications, dereverberation is importantly applied in automatic speech recognition because speech recognizers are usually error-prone in reverberant scenarios.
Dereverberation became established as a topic of scientific research in the years 2000 to 2005., although a few notable early articles exist. The first scientific text book on the topic was published in 2010.  A global scientific study sponsored by the IEEE Technical Committee for Audio and Acoustic Signal Processing  took place in 2014.
Three different approaches can be followed to perform dereverberation. In the first approach, reverberation is cancelled by exploiting a mathematical model of the acoustic system (or room) and, after estimation of the room acoustic model parameters, forming an estimate for the original signal. In the second approach, reverberation is suppressed by treating it as a type of (convolutional) noise and performing a de-noising process specifically adapted to reverberation. In the third approach, the original dereverberated signal is directly estimated from the microphone signals using, for example, a deep neural network machine learning approach or alternatively a multichannel linear filter. Examples of the most effective methods in the state-of-the art include approaches based on linear prediction

## Related

- [[Audio normalization]]
- [[Dattorro industry scheme]]
- [[Digital delay line]]
- [[Digital room correction]]
- [[Fourier analysis]]
- [[Head-related transfer function]]
- [[Outboard gear]]
- [[Steered-response power]]
- [[Virtual acoustic space]]
- [[2D adaptive filters]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dereverberation