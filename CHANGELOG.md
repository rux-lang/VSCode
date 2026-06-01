# Changelog

All notable changes to the **Rux Language** extension will be documented in this file.

## [0.3.0] — 2026-06-02

### Added

- Highlighting for `pub` visibility modifier, `self`, `super`, `asm` keywords
- Highlighting for `is` type-check operator; `as` and `is` scoped as type operators
- Highlighting for comparison operators: `==`, `!=`, `<=`, `>=`
- Highlighting for assignment operators: `=`, `+=`, `-=`, `*=`, `/=`, `%=`, `&=`, `|=`, `^=`, `<<=`, `>>=`
- Highlighting for increment and decrement operators: `++`, `--`
- Highlighting for bitwise NOT operator: `~`
- Highlighting for fat arrow operator: `=>`
- Highlighting for inclusive range operator: `..=`
- Highlighting for spread/variadic operator: `...`
- Highlighting for character literals: `'…'`, `c8'…'`, `c16'…'`, `c32'…'`
- Highlighting for prefixed string literals: `c8"…"`, `c16"…"`, `c32"…"`
- `u` and `i` bare integer literal suffixes (e.g. `100u`, `200i`)
- `{ "include": "#attributes" }` added to function body context

### Fixed

- `||` operator was incorrectly matched as two separate `|` tokens
- `constant.language.bool.rux` renamed to `constant.language.rux` to correctly cover `null`

### Removed

- `class` keyword (not part of the Rux language)
- `#package` compile-time intrinsic (not in the compiler; use `#module`)

## [0.2.0] — 2026-05-26

### Added

- Highlighting for `interface`, `extend`, `module` keywords
- Highlighting for `extern` keyword
- Highlighting for pointer return types in function signatures (`-> *T`, `-> *const T`)
- Highlighting for compile-time intrinsics: `#module`, `#file`, `#function`, `#line`, `#column`, `#date`, `#time`

### Changed

- License updated to be more community-friendly

## [0.1.1] — 2026-05-02

### Added

- Highlighting for attributes (`@[AttributeName(...)]`)
- Highlighting for `opaque` pointer type
- Highlighting for address-of operator (`&`)
- Highlighting for `match` and `in` keywords

## [0.1.0] — 2026-04-29

### Added

- Syntax highlighting for `.rux` source files
- Support for line comments (`//`), documentation comments (`///`), block comments (`/* */`)
- Highlighting for control flow keywords: `if`, `else`, `for`, `while`, `do`, `break`, `continue`, `return`
- Highlighting for storage modifiers: `let`, `var`, `const`
- Highlighting for type declaration keywords: `func`, `struct`, `enum`, `union`, `type`
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
