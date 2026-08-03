---
title: "Wf-XML"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Wf-XML"
wikipedia_categories: ["Business process modelling", "Groupware", "Workflow technology"]
related: ["[[AnyMeeting]]", "[[Application sharing]]", "[[Archives management]]", "[[Basic Support for Cooperative Work]]", "[[Battle command knowledge system]]", "[[Board portal]]", "[[Business reference model]]", "[[Bynari]]", "[[Censhare]]", "[[Central Desktop]]"]
---

# Wf-XML

Wf-XML is a BPM standard developed by the Workflow Management Coalition.
Wf-XML is designed and implemented as an extension to the OASIS Asynchronous Service Access Protocol (ASAP). ASAP provides a standardized way that a program can start and monitor a program that might take a long time to complete. It provides the capability to monitor the running service, and be informed of changes in its status. Wf-XML extends this by providing additional standard web service operations that allow sending and retrieving the “program” or definition of the service which is provided. A process engine has this behavior of providing a service that lasts a long time, and also being programmable by being able to install process definitions.
Wf-XML offers a standard way for a BPM engine to invoke a process in another BPM engine, and to wait for it to complete. Process editing tools and process execution tools may be produced by different vendors. A standard way to retrieve process definitions and send definitions will allow a user to match the best process definition tool with the best process execution engine for their needs. Wf-XML completes the job by giving a standard way to pass the process definition between the design tool and the execution engine.
The roots of the current effort began in 1997 with the Internet Engineering Task Force (IETF) effort named Simple Workflow Access Protocol (SWAP) led by Netscape, Oracle Corporation and others. This was followed by the WfMC standard known as Wf-XML 1.0 and Wf-XML 1.1. Wf-XML was implemented by a number of commercial products. Wf-XML 1.0 and Wf-XML 1.1 predated SOAP and so did not use SOAP message structures. ASAP and Wf-XML 2.0 uses SOAP messages to provide the same capability.
Wf-XML provides a standard way to retrieve a process definition from a BPM engine, and to provide an updated one to the BPM engine. A process design tool could use this standard web services based protocol to browse processes on remote BPM server. It provides an interface between such a design tool and the BPM engine; this is the traditional WfMC Interface 1 for getting and setting the process definition. There is no other effort known to be proposed for standardizing this interaction.
Wf-XML 2.0 is defined using WSDL, thus generally accepted as a standard web service.  It should be known that services built using Wf-XML 2.0 and later are not backwards compatible with those using Wf-XML 1.1, as the earlier protocol was not based on SOAP messages.

## Related

- [[AnyMeeting]]
- [[Application sharing]]
- [[Archives management]]
- [[Basic Support for Cooperative Work]]
- [[Battle command knowledge system]]
- [[Board portal]]
- [[Business reference model]]
- [[Bynari]]
- [[Censhare]]
- [[Central Desktop]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Wf-XML