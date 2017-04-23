# C++ Coding Conventions
A set of informal coding conventions for C++

## Contents
- [Definitions](Conventions.md#definitions)
  - [Pascal Case](Conventions.md#pascal-case)
  - [Camel Case](Conventions.md#camel-case)
  - [Macro Case](Conventions.md#macro-case)
- [Naming Rules](Conventions.md#naming-rules)
  - [Acronyms](Conventions.md#acronyms)
  - [Language Features](Conventions.md#language-features)
- [Spacing Rules](Conventions.md#spacing-rules)
  - [Operators](Conventions.md#operators)
    - [Unary Operators](Conventions.md#unary-operators)
    - [Binary Operators](Conventions.md#binary-operators)

## Definitions

### Pascal Case
- No underscores.
- Each word in an identifier begins with an upper case letter.

#### Examples
- `PascalCase`
- `UsbPort`
- `Run()`

### Camel Case
- No underscores.
- Each word in an identifier begins with an upper case letter.
- The first letter of the identifier is in lower case.

#### Examples
- `camelCase`
- `usbPort`
- `run()`

### Macro Case
- No lower case letters.
- All words in upper case (a.k.a. "all caps").
- Words are delimited by underscores.

#### Examples
- `MACRO_CASE`
- `USB_PORT`
- `RUN()`

## Naming Rules

### Acronyms
- Acronyms should match the default casing rules.

#### Examples
- ejectUsb (camelCase)
- usbPort (camelCase)
- EjectUsb (PascalCase)
- UsbPort (PascalCase)

### Language Features

| Feature          | Ruling      |
|------------------|-------------|
| Classes          | Pascal Case |
| Methods          | Pascal Case |
| Public Fields    | Pascal Case |
| Private Fields   | Camel Case  |
| Protected Fields | Pascal Case |
| Free Functions   | Pascal Case |
| Variables        | Camel Case  |
| Arguments        | Camel Case  |

## Spacing Rules

### Operators

#### Unary Operators
- No space between the operator and the expression

#### Binary Operators
- Should have space on either side of the operator

#### Examples
- `!a`
- `a + b`
- `!(a && b)`
- `a && !b`













