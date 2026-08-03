---
title: "Multiscale Electrophysiology Format"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Multiscale_Electrophysiology_Format"
wikipedia_categories: ["Bioinformatics", "Computational neuroscience stubs", "Computer file formats", "Electroencephalography", "Electrophysiology", "Health standards", "Neurophysiology", "Neurotechnology"]
related: ["[[European Data Format]]", "[[BGZF]]", "[[Brain mapping]]", "[[EEG analysis]]", "[[Gene transfer format]]", "[[General Data Format for Biomedical Signals]]", "[[OBO Foundry]]", "[[OpenVibe]]", "[[Predicted Aligned Error]]", "[[wps]]"]
---

# Multiscale Electrophysiology Format

Multiscale Electrophysiology Format (MEF) was developed to handle the large amounts of data produced by large-scale electrophysiology in human and animal subjects. MEF can store any time series data up to 24 bits in length, and employs lossless range encoded difference compression. Subject identifying information in the file header can be encrypted using 128-bit AES encryption in order to comply with HIPAA requirements for patient privacy when transmitting data across an open network.
Compressed data is stored in independent blocks to allow direct access to the data, facilitate parallel processing and limit the effects of potential damage to files. Data fidelity is ensured by a 32-bit cyclic redundancy check in each compressed data block using the Koopman polynomial (0xEB31D82E), which has a Hamming distance of from 4 to 114 kbits.
A formal specification  and source code  are available online. MEF_import is an EEGLAB plugin to import MEF data into EEGLAB.

## Related

- [[European Data Format]]
- [[BGZF]]
- [[Brain mapping]]
- [[EEG analysis]]
- [[Gene transfer format]]
- [[General Data Format for Biomedical Signals]]
- [[OBO Foundry]]
- [[OpenVibe]]
- [[Predicted Aligned Error]]
- [[wps]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Multiscale_Electrophysiology_Format