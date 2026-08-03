---
title: "RTCM SC-104"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/RTCM_SC-104"
wikipedia_categories: ["Satellite navigation"]
related: ["[[Comparison of free off-line satellite navigation software]]", "[[Comparison of satellite navigation software]]", "[[Controlled reception pattern antenna]]", "[[Degree Confluence Project]]", "[[Differenced one-way doppler]]", "[[Dilution of precision]]", "[[EarthScope]]", "[[EUREF Permanent Network]]", "[[European Satellite Navigation Competition]]", "[[Garmin]]"]
---

# RTCM SC-104

RTCM SC-104 (named after the Radio Technical Commission for Maritime Services Special Committee 104), also known simply as "RTCM", is a communication protocol for sending GNSS-related data. It supports recording and sending navigation messages as received by a GNSS receiver as well as additional correction data such as those for differential GPS (DGPS, observation space) and (since version 3.1 Amendment 5) state-space correction. It has two main use cases:

A base station at a known location and containing a GNSS receiver can generate RTCM-format correction data in real time. This is fed to a mobile GNSS receiver to improve its accuracy.
The data format of RTCM version 3 is a compact binary format for the storage of GPS observation data. Storing observations allows post-processing of existing data at a later time.
RTCM SC-104 format does not define the source of the messages and has been used with systems as varied as longwave marine radio, communications satellite broadcasts, and Internet (Networked Transport of RTCM via Internet Protocol) distribution.
RTCM SC-104 is not the only standard for DGPS; Trimble introduced the Compact Measurement Record (CMRx) format for the same basic purpose and there are several other similar standards used for special purposes. Most of these other standards have fallen into disuse with the introduction of RTCM 10403.1 (RTCM 3.1).

## Related

- [[Comparison of free off-line satellite navigation software]]
- [[Comparison of satellite navigation software]]
- [[Controlled reception pattern antenna]]
- [[Degree Confluence Project]]
- [[Differenced one-way doppler]]
- [[Dilution of precision]]
- [[EarthScope]]
- [[EUREF Permanent Network]]
- [[European Satellite Navigation Competition]]
- [[Garmin]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/RTCM_SC-104