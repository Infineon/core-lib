# Core Library Release Notes

### What Changed?
#### v1.8.0
* Documentation Update
#### v1.7.0
* Documentation Update
* Added new macro _BOOL2UINT
* Added base module identifier for the user owned result code space CY_RSLT_MODULE_USER_BASE
#### v1.6.0
* Documentation Update
#### v1.5.0
* Added new module identifiers to cy_result.h
* Added CY_RSLT_GET_EX_SUBMODULE and CY_RSLT_GET_EX_CODE macros for extracting extended result information.
#### v1.4.4
* Added new module identifiers to cy_result.h:
    * CY_RSLT_MODULE_DRIVER_DSADC
    * CY_RSLT_MODULE_DRIVER_CAN2B
    * CY_RSLT_MODULE_MIDDLEWARE_PMBUS
#### v1.4.3
* Added new module identifiers to cy_result.h
* Updated CY_HALT to be an inline function
#### v1.4.2
* Added new module identifiers to cy_result.h
#### v1.4.1
* Added new module identifiers to cy_result.h
#### v1.4.0
* Added new module identifiers to cy_result.h
* Add typedefs to convey width in scenarios where there are no standard fixed-width types.
#### v1.3.1
* Added new entries to cy_en_rslt_module_t
* Update CY_NOINIT to support newer ARM compiler 6.16
#### v1.3.0
* Added a new CY_RSLT_CREATE_EX to provide more options for creating error codes
#### v1.2.0
* Added a new cy_rslt_decode_t that provides better debugging experience when examining result codes
* Converted module identifiers into enums to provide better debugging experience
#### v1.1.5
* Minor updates including new module id definitions
#### v1.1.4
* Minor updates for MISRA & documentation
#### v1.1.3
* Minor update for documentation & branding
#### v1.1.2
* Added new module identifiers to cy_result.h
#### v1.1.1
* Fixed MISRA violation
#### v1.1.0
* Migrated numerous utility & cross compiler macros from psoc6pdl into here
#### v1.0.1
* Added new module IDs in cy_result.h
* Minor updates to documentation
#### v1.0.0
* Initial release


---
© Copyright 2019-2026 Infineon Technologies AG and its affiliates. All rights reserved.
