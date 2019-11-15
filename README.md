# Cypress Core Library

## Overview

The Cypress Core Library provides basic types and utilities that can be used between different devices. This allows different libraries to share common items between themselves to avoid reimplementation and promote consistency.

## Features

* Common result type (`cy_rslt_t`) for reporting errors or status
* Common APIs for
    * `CY_ASSERT`: Verifies a value and halts if invalid (if not NDEBUG)
    * `CY_HALT`: Halts the application
    * `CY_UNUSED_PARAMETER`: Avoid warnings if a function argument isn't used

## More information
* [API Reference Guide](https://cypresssemiconductorco.github.io/core-lib/html/modules.html)
* [Cypress Semiconductor](http://www.cypress.com)
* [Cypress Semiconductor GitHub](https://github.com/cypresssemiconductorco)
* [ModusToolbox](https://www.cypress.com/products/modustoolbox-software-environment)

---
© Cypress Semiconductor Corporation, 2019.
