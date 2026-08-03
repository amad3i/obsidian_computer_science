---
title: "Audio-visual speech recognition"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Audio-visual_speech_recognition"
wikipedia_categories: ["Applications of computer vision", "Artificial intelligence stubs", "Computational linguistics", "Computational linguistics stubs", "Multimodal interaction", "Speech recognition"]
related: ["[[Automated Lip Reading]]", "[[Articulatory speech recognition]]", "[[Linguatec]]", "[[VoxForge]]", "[[JSGF]]", "[[Lexical simplification]]", "[[Phonetic search technology]]", "[[Spoken dialog system]]", "[[Subspace Gaussian mixture model]]", "[[ACL Data Collection Initiative]]"]
---

# Audio-visual speech recognition

Audio visual speech recognition (AVSR) is a technique that uses image processing capabilities in lip reading to aid speech recognition systems in recognizing indeterministic phones or giving preponderance among near probability decisions.
Each system of lip reading and speech recognition works separately, then their results are mixed at the stage of feature fusion. As the name suggests, it has two parts. First one is the audio part and second one is the visual part. In audio part we use features like log mel spectrogram, mfcc etc. from the raw audio samples and we build a model to get feature vector out of it . For visual part generally we use some variant of convolutional neural network to compress the image to a feature vector after that we concatenate these two vectors (audio and visual ) and try to predict the target object.

## Related

- [[Automated Lip Reading]]
- [[Articulatory speech recognition]]
- [[Linguatec]]
- [[VoxForge]]
- [[JSGF]]
- [[Lexical simplification]]
- [[Phonetic search technology]]
- [[Spoken dialog system]]
- [[Subspace Gaussian mixture model]]
- [[ACL Data Collection Initiative]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Audio-visual_speech_recognition