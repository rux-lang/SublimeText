# Rux Language — Sublime Text Package

Syntax highlighting support for the [Rux](https://rux-lang.dev) programming language in [Sublime Text](https://www.sublimetext.com) editor.

![Rux syntax highlighting preview](https://raw.githubusercontent.com/rux-lang/SublimeText/main/images/preview.png)

## Features

- **Syntax highlighting** for `.rux` source files
- Highlights the following language constructs:

| Category        | Elements                                                                    |
| --------------- | --------------------------------------------------------------------------- |
| Keywords        | `func`, `class`, `struct`, `enum`, `union`, `type`                          |
| Control flow    | `if`, `else`, `for`, `while`, `do`, `break`, `continue`, `return`           |
| Storage         | `let`, `var`, `const`                                                       |
| Modifiers       | `as`, `async`, `import`, `export`                                           |
| Integer types   | `int`, `int8` – `int512`, `uint`, `uint8` – `uint512`                       |
| Float types     | `float`, `float8` – `float512`                                              |
| Character types | `char`, `char8` – `char512`                                                 |
| Boolean types   | `bool`, `bool8` – `bool512`                                                 |
| Literals        | Decimal, hexadecimal (`0x`), octal (`0o`), binary (`0b`) with type suffixes |
| Constants       | `true`, `false`, `null`                                                     |
| Comments        | `//` line, `///` doc, `/* */` block                                         |
| Strings         | Double-quoted strings with escape sequences                                 |

## Requirements

No additional requirements. Install the package and open any `.rux` file.

## Package Settings

This package does not add any configuration settings.

## Known Issues

Please report issues on the [GitHub issue tracker](https://github.com/rux-lang/SublimeText/issues).

## Release Notes

### 0.1.0

Initial release with full syntax highlighting for the Rux source files.

## License

[MIT](LICENSE)
