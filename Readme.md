# OpenArkCompiler

## Overview
-----------------
> A new generation of compilers for IoT that support multiple languages and multiple devices.

OpenArkCompiler is an open source project from the Huawei Ark compiler.

### OpenArkCompiler four technical points ###

Efficient execution in the runtime environment by compiling different language code into a set of executables in the development environment:：
- Support multi-language joint optimization and eliminate cross-language call overhead;
- The program does not need to rely on virtual machines when running, reducing resource consumption and having an efficient memory recovery mechanism;
- Flexible compilation and optimization for different applications;
- Developers have low learning and use costs.

### Future-oriented intelligent hardware ecosystem ###

With the development of current terminal hardware, there is a trend toward the development of intelligent IoT diversity, gradually forming a hardware form with mobile phone as the center and multi-device interconnection; the development of hardware diversity brings the complexity of software architecture and programming framework, the upper layer Application and business software developers urgently need a set of compilation frameworks, which can realize multiple compilations of multiple programming languages, multi-device operation, and a good performance foundation. Based on the above hardware development trends and software ecological development requirements, the Ark compiler combines the industry's latest compiler frontier technology to create a multi-architecture programming language environment for software developers.

## Open source plan ##
** Opensource Compiler Framework **
- Time: August 2019
- Opensource scope: compiler IR + mid-range language implementation
- Open ability:
   - Opensource Framework for reference learning, understand the Ark compiler architecture and framework code
   - Developers can build a complete compiler toolchain that supports Java Sample program compilation (non-application)

** Follow-up opensource scope **
Opensource compiler frontend, backend; support Java program compilation, JavaScript language application compilation.

**Keep updating......**

## References

- Architecture design principle
   - [MAPLE IR Design](doc/MapleIRDesign.md)
   - [RC API](doc/RC_API.md)
   - [Simple version of RC operation insertion principle](doc/Naive_RC_Principle.md)
   - [Virtual function table and interface function table design introduction](doc/Vtable&Itable.md)
   - [Phase design introduction](doc/Phase_Design.md)

- [Environment](doc/Development_Preparation.md)

- [Developer Guide](doc/Developer_Guide.md)

- [Programming Specifications](doc/Programming_Specifications.md)

## LICENSE
- [LICENSE](license/LICENSE)
- [Opensource software statement](license/Third_Party_Open_Source_Software_Notice.md)

Tranlated By Robot "airhead"

