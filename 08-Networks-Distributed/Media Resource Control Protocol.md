---
title: "Media Resource Control Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Media_Resource_Control_Protocol"
wikipedia_categories: ["Application layer protocols", "Internet protocols", "Multimedia software stubs"]
related: ["[[Border Gateway Protocol]]", "[[DNS over HTTPS]]", "[[DNS over TLS]]", "[[Domain Name System]]", "[[GPSoverIP]]", "[[Internationalized Resource Identifier]]", "[[Internet Content Adaptation Protocol]]", "[[Internet Open Trading Protocol]]", "[[InterPlanetary File System]]", "[[Lightweight Directory Access Protocol]]"]
---

# Media Resource Control Protocol

Media Resource Control Protocol (MRCP) is a communication protocol used by speech servers to provide various services (such as speech recognition and speech synthesis) to their clients. MRCP relies on another protocol, such as Real Time Streaming Protocol (RTSP) or Session Initiation Protocol (SIP) for establishing a control session and audio streams between the client and the server.
MRCP uses a similar style of clear-text signaling as HTTP and many other Internet protocols, in which each message contains 3 sections: a first-line, a header and a body. The first line indicates the type of message as well as information such as response codes. The header contains a number of lines, each in the format <header>: <data>. The body, whose length is specified by the header, contains the details of the message.
Like HTTP, MRCP uses a request (usually issued by the client) and response model. Responses may simply acknowledge receipt of the request or give other information regarding its processing. For example, an MRCP client may request to send some audio data for processing (say, for speech recognition), to which the server could respond with a message containing a suitable port number to send the data, since MRCP does not have support for audio data specifically as this would have to be handled by some other protocol, such as Real-time Transport Protocol (RTP).
MRCP protocol version 2 has been approved as an RFC. Version 2 uses SIP for managing sessions and audio streams between the server and the clients, whereas version 1 did not specify the underlying protocol.
MRCP has been adopted by a wide range of commercial speech servers, such as Verbio Technologies, Skit.ai's VIVA, Microsoft Speech Server, LumenVox Speech Engine, ReadSpeaker speechServer MRCP, Nuance Recognizer and Vocalizer, Sestek TTS, Sestek Call Steering as well as commercial Interactive Voice Response software such as Blueworx Voice Response..

## Related

- [[Border Gateway Protocol]]
- [[DNS over HTTPS]]
- [[DNS over TLS]]
- [[Domain Name System]]
- [[GPSoverIP]]
- [[Internationalized Resource Identifier]]
- [[Internet Content Adaptation Protocol]]
- [[Internet Open Trading Protocol]]
- [[InterPlanetary File System]]
- [[Lightweight Directory Access Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Media_Resource_Control_Protocol