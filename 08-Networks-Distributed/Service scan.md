---
title: "Service scan"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Service_scan"
wikipedia_categories: ["Computer network security"]
related: ["[[3-subset meet-in-the-middle attack]]", "[[ACARM-ng]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Anomaly-based intrusion detection system]]", "[[Application Defined Network]]", "[[Application-level gateway]]", "[[Attack tree]]", "[[Authentication server]]", "[[Banner grabbing]]"]
---

# Service scan

On computer networks, a service scan identifies the available network services by attempting to initiate many sessions to different applications with each device in a target group of devices. This is done by sending session initiation packets for many different applications to open ports on all of the devices specified in the target group of devices. This scan is done across a wide range of TCP, UDP (and other transport layer protocols if desired such as SCTP). A service scanner will identify each device it finds along with the services that it finds on the ports that it scans.
Most user-based network services are intended to be found by users. As an example, a web service may be made available on TCP port 80 on a device. TCP/80 is the standard port for HTTP and users would be able to access the content of that web server, the website, by directing their web browsers to that device where the user would be able to view the home page of the website. However, a web service may be opened on a different port, where different content may be shared. This may be in an attempt to hide some content from ordinary users and only to provide it to users who know how to access the web service on the nonstandard port. A port scan will be able to identify that a port is open on the device, but may not be able to determine what service is being offered on that port. A service scan of that device will be able to determine that the port is open and that it is a web service.
Service scanners can be set to target a single device, but they are more often set to target a large number of devices. For example, a service scanner may be configured to scan a subnet. A service scanner may also be configured to scan standardized, well-known, and otherwise unused ports and will attempt to initiate sessions to many known services for each port. This is different from a port sweep that will only identify open ports, which are assumed to be associated with the default service for that port. The difference is that a port scan and a port sweep will detect that a device has a port open and would assume that the port is associated with the service normally associated with that port. However, a service scanner would verify that the service is actually associated with that port, or would attempt to find and report the application actually associated with that port on the device.
Information security personnel may perform service scans to reduce risk. For example, a service scanner may be configured to only search for Microsoft SQL Servers on TCP ports from 1 to 50,000 on all of the devices in an enterprise private network. If the service scanner only finds the MSSQL service running on known and authorized servers at TCP/1433 (the assigned port) then they can be reasonably sure that there are no unauthorized SQL servers in their network. Tools such as nmap and nessus may be used for this purpose.
On the other hand, a network attacker may use a special type of service scanner, known as a vulnerability scanner, to find devices that have not been patched to find a known vulnerability. An attacker may also use a service scanner to find open administrative ports such as Telnet on TCP/21 and SSH on TCP/22. Once an attacker finds those ports they may then attempt to gain access to those devices by guessing usernames and passwords.

## Related

- [[3-subset meet-in-the-middle attack]]
- [[ACARM-ng]]
- [[Administrative domain]]
- [[AEGIS SecureConnect]]
- [[Anomaly-based intrusion detection system]]
- [[Application Defined Network]]
- [[Application-level gateway]]
- [[Attack tree]]
- [[Authentication server]]
- [[Banner grabbing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Service_scan