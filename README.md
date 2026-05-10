# Rux Language — VS Code Extension

Syntax highlighting support for the [Rux](https://rux-lang.dev) programming language in [Visual Studio Code](https://code.visualstudio.com).

![Rux syntax highlighting preview](https://raw.githubusercontent.com/rux-lang/VSCode/main/images/preview.png)

## Features

- **Syntax highlighting** for `.rux` source files
- **Markdown code fence injection** — Rux code inside ` ```rux ` blocks in `.md` files is highlighted automatically
- Highlights the following language constructs:

| Category               | Elements                                                                               |
| ---------------------- | -------------------------------------------------------------------------------------- |
| Keywords               | `module`, `func`, `struct`, `enum`, `union`, `type`, `interface`, `extend`             |
| Control flow           | `if`, `else`, `for`, `while`, `do`, `loop`, `break`, `continue`, `return`              |
| Storage                | `let`, `var`, `const`                                                                  |
| Modifiers              | `as`, `is`, `import`, `export`                                                         |
| Signed Integer types   | `int`, `int8`, `int16`, `int32`, `int64`, `int128`, `int256`, `int512`                 |
| Unsigned Integer types | `uint`, `uint8`, `uint16`, `uint32`, `uint64`, `uint128`, `uint256`, `uint512`         |
| Float types            | `float`, `float8`, `float16`, `float32`, `float64`, `float128`, `float256`, `float512` |
| Character types        | `char`, `char8`, `char16`, `char32`, `char64`, `char128`, `char256`, `char512`         |
| Boolean types          | `bool`, `bool8`, `bool16`, `bool32`, `bool64`, `bool128`, `bool256`, `bool512`         |
| Literals               | Decimal, hexadecimal (`0x`), octal (`0o`), binary (`0b`) with type suffixes            |
| Constants              | `true`, `false`, `null`                                                                |
| Comments               | `//` line, `///` doc, `/* */` block                                                    |
| Strings                | Double-quoted strings with escape sequences                                            |

## Requirements

No additional requirements. Install the extension and open any `.rux` file.

## Extension Settings

This extension does not add any configuration settings.

## Known Issues

Please report issues on the [GitHub issue tracker](https://github.com/rux-lang/VSCode/issues).

## Release Notes

### 0.2.0

Added `interface`, `extend`, `module` keywords and `#module`, `#file`, `#line`, `#column`, `#date`, `#time` intrinsics.

### 0.1.0

Initial release with full syntax highlighting for Rux source files and Markdown code fence injection.

## License

[MIT](LICENSE)
