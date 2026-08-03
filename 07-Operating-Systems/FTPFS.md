---
title: "FTPFS"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/FTPFS"
wikipedia_categories: ["Computer file systems", "File Transfer Protocol", "Network software stubs"]
related: ["[[Access method]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[Basic partitioned access method]]", "[[Block allocation map]]", "[[Block availability map]]", "[[Block suballocation]]"]
---

# FTPFS

FTPFS refers to file systems that support access to a File Transfer Protocol (FTP) server through standard file system application programming interfaces (APIs).
The ftpfs command in Plan 9 was originated by Dennis Ritchie and was included in the first release of the system (1992). It arranged for a remote file system reachable via FTP to appear as part of the local file system.
In Linux systems, FTPFS was initially implemented as a Linux kernel module that allows the user to mount a FTP server onto the local filesystem, but it was never seen as the perfect way to do it. By 2003, it has been converted to use LUFS, and later to FUSE. Now it is called CurlFtpFS because it uses the universal libcurl for FTP transactions, and is becoming part of the major Linux distributions. There also exists LftpFS for smart mirroring of FTP sites.
In macOS, a read-only FTP file system is included that can be used either via the GUI (with ⌘ Command+K) or the command line (mount_ftp). The read-only limitation is noted in the man page for mount_ftp (on a macOS system, in Terminal.app, see "man mount_ftp"). However, the free application Macfusion includes a working implementation of FTPFS. Additionally, macOS Fuse is reported to enable this but the method to do so is undocumented (as of March 4, 2013) either via various obvious man page (e.g. sshfs) or in the macOS Fuse wiki.
For Windows XP, Windows 7 and other Windows operating systems, this functionality is partially provided by the "Network Places"/"Network Location" shell facility; a network place is a link to either an FTP server or a WebDAV server and can be accessed in Windows Explorer as just another network filesystem.  This does not provide transparent access through the lowest-level Win32 file system APIs, however.  Such functionality can be provided by third party programs such as WebDrive and FTPDrive.

## Related

- [[Access method]]
- [[Allocate-on-flush]]
- [[Apple File System]]
- [[Apple Partition Map]]
- [[Archive bit]]
- [[Archive file]]
- [[Basic partitioned access method]]
- [[Block allocation map]]
- [[Block availability map]]
- [[Block suballocation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/FTPFS