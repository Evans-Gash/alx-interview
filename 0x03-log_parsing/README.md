# Project 0x03: Log Parsing

## Overview

Welcome to Project 0x03 - Log Parsing! This project involves creating a Python script that reads log entries from standard input, computes metrics, and prints statistics at regular intervals. The script should adhere to specific requirements and use the PEP 8 style.

## Requirements

- **Editors:** vi, vim, emacs
- **Execution Environment:** Ubuntu 20.04 LTS using Python 3.4.3
- **File Endings:** All files should end with a new line.
- **Shebang Line:** The first line of all files should be exactly `#!/usr/bin/python3`.
- **README.md:** A mandatory README.md file at the root of the project folder.
- **Coding Style:** Your code should use the PEP 8 style (version 1.7.x).
- **File Execution:** All files must be executable.
- **File Length:** The length of your files will be tested using `wc`.

## Tasks

### Task 0: Log Parsing

**Objective:** Write a script that reads stdin line by line and computes metrics.

**Input Format:**
```
<IP Address> - [<date>] "GET /projects/260 HTTP/1.1" <status code> <file size>
```

**Output:**
- After every 10 lines or a keyboard interruption (CTRL + C), print the following statistics from the beginning:
  - Total file size: `File size: <total size>` (where `<total size>` is the sum of all previous `<file size>`).
  - Number of lines by status code:
    - Possible status codes: 200, 301, 400, 401, 403, 404, 405, and 500.
    - If a status code doesn’t appear or is not an integer, don’t print anything for this status code.
    - Format: `<status code>: <number>` (status codes should be printed in ascending order).

**Example:**
```bash
$ cat 0-generator.py | ./0-stats.py
File size: 5213
200: 2
401: 1
403: 2
404: 1
405: 1
500: 3
File size: 11320
200: 3
301: 2
400: 1
401: 2
403: 3
404: 4
405: 2
500: 3
File size: 16305
200: 3
301: 3
400: 4
401: 2
403: 5
404: 5
405: 4
500: 4
^CFile size: 17146
200: 4
301: 3
400: 4
401: 2
403: 6
404: 6
405: 4
500: 4
```

**Repository Details:**
- GitHub repository: [alx-interview](https://github.com/Evans-Gash/alx-interview)
- Directory: 0x03-log_parsing
- File: 0-stats.py
