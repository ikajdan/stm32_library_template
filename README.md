# STM32 Library Template

This repository provides a basic template for developing STM32 libraries. It includes a structured directory layout, placeholder configuration files, and source code files to streamline the development process.

## Directory Structure

```
ikajdan-stm32_library_template/
├── Inc/
│   ├── template.h          # Template library header file
│   ├── template_conf.h     # Configuration header file
└── Src/
    ├── template.c          # Template library source file
    └── template_conf.c     # Configuration source file
```

## Files Overview

### `Inc/template.h`
- Declares public function prototypes, macros, and variables for the library.
- Includes the configuration file `template_conf.h`.

### `Inc/template_conf.h`
- Contains configuration settings and definitions for the library.
- Provides macros and type definitions for customization.

### `Src/template.c`
- Implements the functions declared in `template.h`.
- Contains placeholders for private and public functions.

### `Src/template_conf.c`
- Implements configurable parameters defined in `template_conf.h`.
- Manages configurable variables and settings.

## Usage

1. Modify `template_conf.h` to configure the library according to your requirements.
2. Implement specific functions inside `template.c`.
3. Include `template.h` in your main project files to use the library.

## License

This project is licensed under the CC0 1.0 Universal License. See the [LICENSE](LICENSE.md) file for details.
