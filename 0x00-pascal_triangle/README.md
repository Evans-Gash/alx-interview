# Pascal's Triangle

## Project Overview

This project, based on the algorithm by Alexa Orrico, Software Engineer at Holberton School, aims to implement Pascal's Triangle in Python. Pascal's Triangle is a mathematical construct where each number is the sum of the two directly above it. The implementation is expected to return a list of lists of integers representing the Pascal’s triangle of a given height.

## Task Details

### Task 0: Pascal's Triangle

Create a Python function `pascal_triangle(n)` that returns a list of lists of integers representing the Pascal’s triangle of `n`:

- Returns an empty list if `n` <= 0.
- Assumes `n` will always be an integer.

## How to Use

1. Clone the repository:

```bash
git clone https://github.com/your-username/alx-interview.git
```

2. Navigate to the project directory:

```bash
cd alx-interview/0x00-pascal_triangle
```

3. Run the provided main script:

```bash
./0-main.py
```

This script calls the `pascal_triangle` function and prints the resulting triangle for a given value of `n`.

## Example

```python
from 0-pascal_triangle import pascal_triangle

def print_triangle(triangle):
    for row in triangle:
        print("[{}]".format(",".join([str(x) for x in row])))

if __name__ == "__main__":
    print_triangle(pascal_triangle(5))
```

This example would output:

```bash
[1]
[1,1]
[1,2,1]
[1,3,3,1]
[1,4,6,4,1]
```
