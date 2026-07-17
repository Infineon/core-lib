# Core Library - Basic Types and Utilities for ModusToolbox

# Overview

The Core Library provides basic types and utilities that can be used between different devices. This allows different libraries to share common items among themselves to avoid reimplementation and promote consistency.

* **Result type** — `cy_rslt_t` and `cy_rslt_decode_t` provide a structured 32-bit result value
  that encodes a severity type, a module identifier, and an error code, allowing any library to
  report and decode errors in a consistent way.

* **Assertion and flow control** — macros to halt execution on unexpected conditions, with variants
  that return a value or void on failure, and a supervisor-call helper.

* **Bit and register manipulation** — macros for extracting the high/low byte or half-word of a
  value, swapping byte order (16/32/64-bit), and performing get-clear-modify-write operations on
  8-, 16-, and 32-bit memory-mapped registers.

* **Integer arithmetic helpers** — division with rounding to nearest and rounding up, with defined
  sign constraints to avoid undefined behaviour.

* **Compiler portability attributes** — macros that map to the correct compiler-specific syntax for
  GCC, Arm Compiler 6, IAR, and LLVM/Clang, allowing shared code to control placement, alignment,
  and inlining without `#ifdef` clutter.

* **MISRA C-2012 typedefs** — explicitly named types for `char`, `float`, and `double` to satisfy
  Directive 4.6.

# Related Middleware and Dependencies

**This library is used by:**
- Device Support Libraries (DSL) for all supported Infineon device families

**This library depends on:**
- None (standalone; requires only standard C headers)

# Release Notes and Changelog

- RELEASE.md - Detailed release notes for all versions

# More Information

* [Reference Guide](https://infineon.github.io/core-lib/html/modules.html)
* [Infineon Technologies](https://www.infineon.com)
* [Infineon GitHub](https://github.com/infineon)
* [ModusToolbox Software Environment, Quick Start Guide, Documentation, and Videos](https://www.infineon.com/cms/en/design-support/tools/sdk/modustoolbox-software/)

# License

This library is released under the Apache License, Version 2.0. See the individual source files for the SPDX-License-Identifier or visit https://www.apache.org/licenses/LICENSE-2.0 for the full license text.

---

## Copyright

© Copyright 2019-2026 Infineon Technologies AG and its affiliates. All rights reserved.
