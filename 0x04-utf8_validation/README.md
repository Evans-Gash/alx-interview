# 0x04. UTF-8 Validation

## Overview

Welcome to the 0x04 UTF-8 Validation project! In this project, you will be implementing a method in Python to determine if a given data set represents a valid UTF-8 encoding. The project is designed to enhance your algorithmic and Python programming skills.

## Project Details

- **Weight:** 1
- **Project Start:** Jan 29, 2024, 6:00 AM
- **Project Deadline:** Feb 2, 2024, 6:00 AM
- **Checker Release:** Jan 30, 2024, 6:00 AM
- **Auto Review:** Will be launched at the deadline

## Resources

Before starting the project, make sure to read or watch the following resources:

- [UTF-8](https://en.wikipedia.org/wiki/UTF-8)
- [Characters, Symbols, and the Unicode Miracle](https://www.youtube.com/watch?v=MijmeoH9LT4)

## Requirements

### General

- **Allowed Editors:** vi, vim, emacs
- **Interpreted/Compiled:** Ubuntu 20.04 LTS using python3 (version 3.4.3)
- **File Endings:** All files should end with a new line
- **Shebang:** The first line of all files should be exactly `#!/usr/bin/python3`
- **README.md:** A README.md file at the root of the project folder is mandatory
- **Coding Style:** Your code should adhere to the PEP 8 style (version 1.7.x)
- **Executable Files:** All files must be executable

## Tasks

### 0. UTF-8 Validation (mandatory)

Write a method `validUTF8(data)` that determines if a given data set represents a valid UTF-8 encoding.

- **Prototype:** `def validUTF8(data)`
- **Return:** True if data is a valid UTF-8 encoding, else return False
- A character in UTF-8 can be 1 to 4 bytes long
- The data set can contain multiple characters
- The data will be represented by a list of integers
- Each integer represents 1 byte of data, therefore you only need to handle the 8 least significant bits of each integer

### Example

```python
validUTF8 = __import__('0-validate_utf8').validUTF8

data = [65]
print(validUTF8(data))  # Output: True

data = [80, 121, 116, 104, 111, 110, 32, 105, 115, 32, 99, 111, 111, 108, 33]
print(validUTF8(data))  # Output: True

data = [229, 65, 127, 256]
print(validUTF8(data))  # Output: False
```

## Repository Details

- **GitHub Repository:** [alx-interview](https://github.com/Evans-Gash/alx-interview)
- **Directory:** 0x04-utf8_validation
- **File:** 0-validate_utf8.py
