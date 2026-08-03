---
title: "WxSQLite3"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/WxSQLite3"
wikipedia_categories: ["Database software stubs", "Free and open-source software stubs", "Free software programmed in C++", "Relational database management systems", "Software that uses wxWidgets", "WxWidgets"]
related: ["[[Apache Celix]]", "[[Apache Kylin]]", "[[DuckDB]]", "[[Graphics Layout Engine]]", "[[IBM IS1]]", "[[Scalasca]]", "[[Skyline operator]]", "[[4th Dimension (software)]]", "[[Accelerated Linear Algebra]]", "[[Actian Vector]]"]
---

# WxSQLite3

wxSQLite3 is a C++ wrapper around the public domain SQLite 3.x database and is specifically designed for use in programs based on the wxWidgets library.
wxSQLite3 does not try to hide the underlying database, in contrary almost all special features of the current SQLite version 3.47.2 are supported, like for example the creation of user defined scalar or aggregate functions. Since SQLite stores strings in UTF-8 encoding, the wxSQLite3 methods provide automatic conversion between wxStrings and UTF-8 strings. This works best for the Unicode builds of wxWidgets. In ANSI builds the current locale conversion object (wxConvCurrent) is used for conversion to/from UTF-8. Special care has to be taken if external administration tools are used to modify the database contents, since not all of these tools operate in Unicode resp. UTF-8 mode.
Since version 1.7.0 optional support for key based database encryption (128-bit AES) is included. Starting with version 1.9.6 of wxSQLite3 the encryption extension is compatible with the SQLite amalgamation source and includes the extension functions module. Support for 256-bit AES encryption has been added in version 1.9.8.
Since version 3.5.0 the SQLite library is an integrated part of wxSQLite3.
Since version 4.0.0 wxSQLite3 supports to select the encryption scheme at runtime. Currently, 7 different cipher schemes can be selected:

wxSQLite3 AES-128 bit
wxSQLite3 AES-256 bit
sqleet (a.k.a. ChaCha20 - Poly1305)
SQLCipher (a.k.a. AES-256 bit - SHA-1/SHA256/SHA512 - all SQLCipher variants from version 1 up to version 4 supported)
System.Data.SQLite (a.k.a. RC4)
Ascon Ascon-128 v1.2 (lightweight cryptography)
AEGIS (since version 4.10.0)
Since version 4.6.0 wxSQLite3 uses a separate implementation of the encryption extension, namely SQLite3 Multiple Ciphers, because the formerly used SQLITE_HAS_CODEC interface was removed from SQLite in February 2020.

## Related

- [[Apache Celix]]
- [[Apache Kylin]]
- [[DuckDB]]
- [[Graphics Layout Engine]]
- [[IBM IS1]]
- [[Scalasca]]
- [[Skyline operator]]
- [[4th Dimension (software)]]
- [[Accelerated Linear Algebra]]
- [[Actian Vector]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/WxSQLite3