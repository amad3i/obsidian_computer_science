---
title: "General Data Format for Biomedical Signals"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/General_Data_Format_for_Biomedical_Signals"
wikipedia_categories: ["Bioinformatics", "Computer file formats", "Standards for electronic health records"]
related: ["[[European Data Format]]", "[[BGZF]]", "[[Gene transfer format]]", "[[Multiscale Electrophysiology Format]]", "[[Predicted Aligned Error]]", "[[wps]]", "[[100,000 Genomes Project]]", "[[1000 Genomes Project]]", "[[3D-Jury]]", "[[ABCD Schema]]"]
---

# General Data Format for Biomedical Signals

The General Data Format for Biomedical Signals is a scientific and medical data file format. The aim of GDF is to combine and integrate the best features of all biosignal file formats into a single file format.
The original GDF specification was introduced in 2005 as a new data format to overcome some of the limitations of the European Data Format for Biosignals (EDF). GDF was also designed to unify a number of file formats which had been designed for very specific applications (for example, in ECG research and EEG analysis). The original specification included a binary header, and used an event table. An updated specification (GDF v2) was released in 2011 and added fields for additional subject-specific information (gender, age, etc.) and utilized several standard codes for storing physical units and other properties. In 2015, the Austrian Standardization Institute made GDF an official Austrian Standard https://shop.austrian-standards.at/action/en/public/details/553360/OENORM_K_2204_2015_11_15, and the revision number has been updated to v3.
The GDF format is often used in brain–computer interface research. However, since GDF provides a superset of features from many different file formats, it could be also used for many other domains.
The free and open source software BioSig library provides implementations for reading and writing of GDF in GNU Octave/MATLAB and C/C++. A lightweight C++ library called libGDF is also available and implements version 2 of the GDF format.

## Related

- [[European Data Format]]
- [[BGZF]]
- [[Gene transfer format]]
- [[Multiscale Electrophysiology Format]]
- [[Predicted Aligned Error]]
- [[wps]]
- [[100,000 Genomes Project]]
- [[1000 Genomes Project]]
- [[3D-Jury]]
- [[ABCD Schema]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/General_Data_Format_for_Biomedical_Signals