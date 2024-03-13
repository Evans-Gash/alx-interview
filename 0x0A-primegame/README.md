# 0x0A. Prime Game

## Overview
This project involves solving a competitive game scenario by strategically removing prime numbers and their multiples from a set of consecutive integers. The challenge requires understanding prime numbers, game theory, and algorithm optimization. You will implement a function to determine the winner of each round of the game.

## Table of Contents
- [Description](#description)
- [Concepts Needed](#concepts-needed)
- [Resources](#resources)
- [Requirements](#requirements)
- [Tasks](#tasks)
- [Example](#example)
- [Repo](#repo)

## Description
Maria and Ben play a game where they take turns choosing prime numbers from a set of consecutive integers starting from 1 up to and including n. They remove the chosen number and its multiples from the set. The player who cannot make a move loses the game. The task is to determine the winner of each round for a given number of rounds.

## Concepts Needed
- **Prime Numbers**: Understanding and identifying prime numbers efficiently.
- **Sieve of Eratosthenes**: An algorithm for finding prime numbers up to a given limit.
- **Game Theory**: Principles of competitive games and optimal play strategies.
- **Dynamic Programming/Memoization**: Optimizing calculations using previous results.
- **Python Programming**: Implementing game logic and algorithms using Python.

## Resources
- **Prime Numbers and Sieve of Eratosthenes**: Khan Academy, Sieve of Eratosthenes in Python.
- **Game Theory Basics**: Introduction to Game Theory.
- **Dynamic Programming**: What Is Dynamic Programming With Python Examples.
- **Python Official Documentation**: Python Lists.

## Requirements
- **Editors**: visual studios.
- **Platform**: Ubuntu 20.04 LTS, Python 3.4.3.
- **File Endings**: All files should end with a new line.
- **Shebang**: The first line of all files should be `#!/usr/bin/python3`.
- **README**: A README.md file at the root of the project folder.
- **PEP 8**: Code should follow the PEP 8 style.
- **Execution**: All files must be executable.
- **Tasks**: Implement the provided task.
- **Packages**: No packages should be imported.

## Tasks
- **Prime Game**: Implement the function `isWinner(x, nums)` to determine the winner of each round.

## Example
```python
x = 3
nums = [4, 5, 1]
print(isWinner(x, nums))  # Output: Ben
```

## Repo
- **GitHub Repository**: [Evans-Gash/alx-interview](https://github.com/Evans-Gash/alx-interview)
- **Directory**: 0x0A-primegame
- **File**: 0-prime_game.py