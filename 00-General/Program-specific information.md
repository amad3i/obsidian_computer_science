---
title: "Program-specific information"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Program-specific_information"
wikipedia_categories: ["Computer programming", "MPEG", "Video codecs"]
related: ["[[Algorave]]", "[[Asynchronous procedure call]]", "[[Asynchrony (computer programming)]]", "[[Bayesian program synthesis]]", "[[Boolean flag]]", "[[Breakpoint]]", "[[Cheat sheet]]", "[[Code Club]]", "[[Code Words]]", "[[Codecademy]]"]
---

# Program-specific information

Program-specific information (PSI) is metadata about a program (channel) and part of an MPEG transport stream.
The PSI data as defined by ISO/IEC 13818-1 (MPEG-2 Part 1: Systems) includes four tables: 

PAT (Program Association Table)
CAT (Conditional Access Table)
PMT (Program Mapping Table)
NIT (Network Information Table)
The MPEG-2 specification does not specify the format of the CAT and NIT.
PSI is carried in the form of a table structure. Each table structure is broken into sections, although some tables like a PMT cannot have more than one section.  Each section can span multiple transport stream packets.  On the other hand, although this is uncommon, a transport stream packet or set of packets under the same PID can contain multiple sections belonging to different tables. Adaptation field also occurs in TS packets carrying PSI data. The PSI data will never be scrambled so that the decoder at the receiving end can easily identify the properties of the stream.
The sections comprising the PAT and CAT tables are associated with predefined PIDs (Packet Identifier) and table IDs as explained in their respective descriptions below. There may be multiple independent PMTs in a stream, one for each program. Each PMT is given a unique user-defined PID and maps a program number to the metadata describing that program and the streams within it. PMT PIDs are defined in the PAT, and are the only PIDs defined there. The streams themselves are contained in PES packets with user-defined PIDs specified in the PMT.

## Related

- [[Algorave]]
- [[Asynchronous procedure call]]
- [[Asynchrony (computer programming)]]
- [[Bayesian program synthesis]]
- [[Boolean flag]]
- [[Breakpoint]]
- [[Cheat sheet]]
- [[Code Club]]
- [[Code Words]]
- [[Codecademy]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Program-specific_information