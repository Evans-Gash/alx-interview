# N Queens Problem Solver

## Overview
This project focuses on solving the N Queens problem, a classic chess puzzle that challenges you to place N non-attacking queens on an N×N chessboard. The program should print every possible solution to the problem, with one solution per line.

## Algorithm
The solution to the N Queens problem involves backtracking, a technique used to systematically search for solutions to a problem among all possible candidates. In this case, the program iterates through each column of the chessboard, attempting to place a queen in each row while ensuring it does not attack any other queens already placed.

## Requirements
### General
- Allowed editors: vi, vim, emacs
- All files will be interpreted/compiled on Ubuntu 20.04 LTS using Python 3 (version 3.4.3)
- All files should end with a new line
- The first line of all files should be exactly `#!/usr/bin/python3`
- A `README.md` file, at the root of the folder of the project, is mandatory
- Your code should follow the PEP 8 style (version 1.7.*)
- All files must be executable

## Tasks
### 0. N queens (mandatory)
- Implement a program that solves the N Queens problem.
- Usage: `nqueens N`
- If the user provides the wrong number of arguments, print `Usage: nqueens N`, followed by a new line, and exit with status 1.
- If N is not an integer, print `N must be a number`, followed by a new line, and exit with status 1.
- If N is smaller than 4, print `N must be at least 4`, followed by a new line, and exit with status 1.
- The program should print every possible solution to the problem, one solution per line.
- Solutions are represented as a list of coordinates indicating the position of queens on the chessboard.
- You are only allowed to import the `sys` module.

### Examples
```
$ ./0-nqueens.py 4
[[0, 1], [1, 3], [2, 0], [3, 2]]
[[0, 2], [1, 0], [2, 3], [3, 1]]
$ ./0-nqueens.py 6
[[0, 1], [1, 3], [2, 5], [3, 0], [4, 2], [5, 4]]
[[0, 2], [1, 5], [2, 1], [3, 4], [4, 0], [5, 3]]
[[0, 3], [1, 0], [2, 4], [3, 1], [4, 5], [5, 2]]
[[0, 4], [1, 2], [2, 0], [3, 5], [4, 3], [5, 1]]
```

## Repository Information
- **GitHub Repository:** alx-interview
- **Directory:** 0x05-nqueens
- **File:** 0-nqueens.py

