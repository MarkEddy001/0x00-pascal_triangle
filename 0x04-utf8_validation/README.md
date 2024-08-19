# 0x04. UTF-8 Validation

## Description

This project involves writing a method to determine if a given dataset represents a valid UTF-8 encoding. The dataset is represented by a list of integers, where each integer represents one byte of data. The goal is to validate whether the data conforms to the UTF-8 encoding scheme.

## Requirements

- Allowed editors: `vi`, `vim`, `emacs`
- All files will be interpreted/compiled on Ubuntu 20.04 LTS using `python3` (version 3.4.3)
- All files should end with a new line
- The first line of all files should be exactly `#!/usr/bin/python3`
- A `README.md` file, at the root of the folder of the project, is mandatory
- Code should use the PEP 8 style (version 1.7.x)
- All files must be executable

## Concepts

### Bitwise Operations in Python

Understanding how to manipulate bits in Python, including operations like AND (`&`), OR (`|`), XOR (`^`), NOT (`~`), shifts (`<<`, `>>`).

### UTF-8 Encoding Scheme

Familiarity with the UTF-8 encoding rules, including how characters are encoded into one or more bytes. Understanding the patterns that represent a valid UTF-8 encoded character.

### Data Representation

How to represent and work with data at the byte level. Handling the least significant bits (LSB) of integers to simulate byte data.

### List Manipulation in Python

Iterating through lists, accessing list elements, and understanding list comprehensions.

### Boolean Logic

Applying logical operations to make decisions within the program.

## Resources

- [Python Bitwise Operators](https://docs.python.org/3/library/stdtypes.html#bitwise-operations-on-integer-types)
- [UTF-8 Wikipedia](https://en.wikipedia.org/wiki/UTF-8)
- [Characters, Symbols, and the Unicode Miracle](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)
- [The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/)
- [Python Lists](https://docs.python.org/3/tutorial/datastructures.html)

## Task

### 0. UTF-8 Validation

Write a method that determines if a given dataset represents a valid UTF-8 encoding.

- **Prototype**: `def validUTF8(data)`
- **Return**: `True` if data is a valid UTF-8 encoding, else return `False`
- A character in UTF-8 can be 1 to 4 bytes long
- The dataset can contain multiple characters
- The data will be represented by a list of integers
- Each integer represents 1 byte of data, therefore you only need to handle the 8 least significant bits of each integer

### Example

```python
#!/usr/bin/python3
"""
Main file for testing
"""

validUTF8 = __import__('0-validate_utf8').validUTF8

data = [65]
print(validUTF8(data))  # True

data = [80, 121, 116, 104, 111, 110, 32, 105, 115, 32, 99, 111, 111, 108, 33]
print(validUTF8(data))  # True

data = [229, 65, 127, 256]
print(validUTF8(data))  # False
