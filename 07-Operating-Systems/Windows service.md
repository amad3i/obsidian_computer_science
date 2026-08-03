---
title: "Windows service"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Windows_service"
wikipedia_categories: ["Process (computing)", "Windows commands", "Windows services"]
related: ["[[Kill (command)]]", "[[Application-level gateway]]", "[[Background process]]", "[[Chain loading]]", "[[Child process]]", "[[Clipboard (computing)]]", "[[Code cave]]", "[[Command-line interface]]", "[[COMMAND.COM]]", "[[Complex event processing]]"]
---

# Windows service

In Windows NT operating systems, a Windows service is a computer program that operates in the background. It is similar in concept to a Unix daemon. A Windows service must conform to the interface rules and protocols of the Service Control Manager, the component responsible for managing Windows services. It is the Services and Controller app, services.exe, that launches all the services and manages their actions, such as start, end, etc.
Windows services can be configured to start when the operating system is started and run in the background as long as Windows is running. Alternatively, they can be started manually or by an event. Windows NT operating systems include numerous services which run in context of three user accounts: System, Network Service and Local Service. These Windows components are often associated with Host Process for Windows Services. Because Windows services operate in the context of their own dedicated user accounts, they can operate when a user is not logged on.
Prior to Windows Vista, services installed as an "interactive service" could interact with Windows desktop and show a graphical user interface. In Windows Vista, however, interactive services are deprecated and may not operate properly, as a result of Windows Service hardening.

## Related

- [[Kill (command)]]
- [[Application-level gateway]]
- [[Background process]]
- [[Chain loading]]
- [[Child process]]
- [[Clipboard (computing)]]
- [[Code cave]]
- [[Command-line interface]]
- [[COMMAND.COM]]
- [[Complex event processing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Windows_service