# Rux Language — VS Code Extension

Syntax highlighting support for the [Rux programming language](https://github.com/rux-lang/Rux) in Visual Studio Code.

![Rux syntax highlighting preview](https://raw.githubusercontent.com/rux-lang/VSCode/main/images/preview.png)

## Features

- **Syntax highlighting** for `.rux` source files
- **Markdown code fence injection** — Rux code inside ` ```rux ` blocks in `.md` files is highlighted automatically
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

No additional requirements. Install the extension and open any `.rux` file.

## Extension Settings

This extension does not add any configuration settings.

## Known Issues

Please report issues on the [GitHub issue tracker](https://github.com/rux-lang/VSCode/issues).

## Release Notes

### 0.1.0

Initial release with full syntax highlighting for Rux source files and Markdown code fence injection.

## License

[MIT](LICENSE)
