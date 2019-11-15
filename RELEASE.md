### Cypress Core Library 1.0.1
The Cypress Core Library provides basic types and utilities that can be used between different devices. This allows different libraries to share common items between themselves to avoid reimplementation and promote consistency.

### What's New In This Release?
* Added new module IDs in cy_result.h
* Minor updates to documentation
 
### What's Included?
* Common result type for reporting errors or status
* Common APIs for
    * CY_ASSERT: Verifies a value and halts if invalid (if not NDEBUG)
    * CY_HALT: Halts the application
    * CY_UNUSED_PARAMETER: Avoid warnings if a function argument isn't used

### Supported Software and Tools
This version of the Cypress Core Library was validated for compatibility with the following Software and Tools:

| Software and Tools                        | Version |
| :---                                      | :----:  |
| ModusToolbox Software Environment         | 2.0     |
| GCC Compiler                              | 7.4     |
| IAR Compiler                              | 8.32    |
| ARM Compiler                              | 6.11    |


### More information
Use the following links for more information, as needed:
* [API Reference Guide](https://cypresssemiconductorco.github.io/core-lib/html/modules.html)
* [Cypress Semiconductor](http://www.cypress.com)
* [Cypress Semiconductor GitHub](https://github.com/cypresssemiconductorco)
* [ModusToolbox](https://www.cypress.com/products/modustoolbox-software-environment)


---
© Cypress Semiconductor Corporation, 2019.