# C++ Coding Conventions
A set of informal coding conventions for C++

---

# Contents
- Definitions
- Naming Rules
- Spacing Rules

---

# Definitions

## Pascal Case
- No underscores.
- Each word in an identifier begins with an upper case letter.

### Examples
- `PascalCase`
- `UsbPort`
- `Run()`

## Camel Case
- No underscores.
- Each word in an identifier begins with an upper case letter.
- The first letter of the identifier is in lower case.

### Examples
- `camelCase`
- `usbPort`
- `run()`

## Macro Case
- No lower case letters.
- All words in upper case (a.k.a. "all caps").
- Words are delimited by underscores.

### Examples
- `MACRO_CASE`
- `USB_PORT`
- `RUN()`

---

# Naming Rules

## Acronyms
- Acronyms should match the default casing rules.

### Example
- ejectUsb (camelCase)
- usbPort (camelCase)
- EjectUsb (PascalCase)
- UsbPort (PascalCase)

## Language Features

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

---

# Spacing Rules

## Operators

### Unary Operators
- No space between the operator and the expression

### Binary Operators
- Should have space on either side of the operator

### Examples
- `!a`
- `a + b`
- `!(a && b)`
- `a && !b`













