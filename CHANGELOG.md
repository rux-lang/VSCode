# Changelog

All notable changes to the **Rux Language** extension will be documented in this file.

## [0.1.0] — 2026-04-29

### Added

- Syntax highlighting for `.rux` source files
- Support for line comments (`//`), documentation comments (`///`), block comments (`/* */`)
- Highlighting for control flow keywords: `if`, `else`, `for`, `while`, `do`, `break`, `continue`, `return`
- Highlighting for storage modifiers: `let`, `var`, `const`
- Highlighting for type declaration keywords: `func`, `class`, `struct`, `enum`, `union`, `type`
- Highlighting for other keywords: `as`, `async`, `import`, `export`
- Highlighting for built-in integer types (`int`, `int8`–`int512`, `uint`, `uint8`–`uint512`)
- Highlighting for built-in float types (`float`, `float8`–`float512`)
- Highlighting for built-in character types (`char`, `char8`–`char512`)
- Highlighting for built-in boolean types (`bool`, `bool8`–`bool512`)
- Highlighting for numeric literals: decimal, hexadecimal (`0x`), octal (`0o`), binary (`0b`) with optional type suffixes
- Highlighting for language constants: `true`, `false`, `null`
- Highlighting for string literals with escape sequences
- Function signature highlighting: name, generic type parameters, parameter names and types, return type (`->`)
- Markdown code fence injection — ` ```rux ` blocks in `.md` files are syntax-highlighted
- Bracket matching and auto-closing pairs for `{}`, `[]`, `()`
- Bracket auto-closing for `"` and `'`
