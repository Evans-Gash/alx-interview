# 0x02. Minimum Operations

## Introduction

Welcome to the **0x02. Minimum Operations** project in the ALX-Interview GitHub repository. In this project, you will find an implementation of an algorithm in Python that solves a specific problem related to text file operations.

## Project Overview

### Problem Statement

In a text file, there is a single character 'H'. Your text editor can execute only two operations in this file: Copy All and Paste. Given a number `n`, the task is to write a method that calculates the fewest number of operations needed to result in exactly `n` 'H' characters in the file.

### Example

For instance, when `n = 9`:
- H
- Copy All
- Paste (HH)
- Paste (HHH)
- Copy All
- Paste (HHHHHH)
- Paste (HHHHHHHHH)

Number of operations: 6

### Project Structure

- **0-minoperations.py**: Python script containing the implementation of the `minOperations` function.
- **0-main.py**: Main file for testing the `minOperations` function with example cases.

## Requirements

- **Allowed editors:** vi, vim, emacs
- **Interpreter/Compiler:** Ubuntu 20.04 LTS using Python3 (version 3.4.3)
- **File Ending:** All files should end with a new line
- **Shebang:** The first line of all your files should be exactly `#!/usr/bin/python3`
- **Documentation:** Your code should be well-documented
- **Coding Style:** Your code should use the PEP 8 style (version 1.7.x)
- **Executable Files:** All your files must be executable

## Testing

To test the provided implementation, use the `./0-main.py` script. It includes examples to demonstrate the functionality of the `minOperations` function.

```bash
$ ./0-main.py

Min number of operations to reach 4 characters: 4
Min number of operations to reach 12 characters: 7
```

## Repository Information

- **GitHub repository:** [alx-interview](https://github.com/Evans-Gash/alx-interview)
- **Directory:** 0x02-minimum_operations
- **File:** 0-minoperations.py
