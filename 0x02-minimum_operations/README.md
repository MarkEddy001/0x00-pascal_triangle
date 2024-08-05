# 0x02. Minimum Operations

## Description

In this project, we aim to calculate the minimum number of operations required to achieve exactly `n` characters in a text file using only two operations: "Copy All" and "Paste". This problem can be approached using various algorithmic concepts such as dynamic programming, prime factorization, and greedy algorithms.

## Learning Objectives

By the end of this project, you should be able to:
- Understand and apply dynamic programming to break down complex problems.
- Perform prime factorization to simplify the problem.
- Optimize code for efficiency.
- Implement greedy algorithms to make optimal choices at each step.
- Write clean and efficient Python code following PEP 8 guidelines.

## Requirements

- Allowed editors: `vi`, `vim`, `emacs`
- All files will be interpreted/compiled on Ubuntu 20.04 LTS using `python3` (version 3.4.3)
- All files should end with a new line
- The first line of all files should be exactly `#!/usr/bin/python3`
- A `README.md` file at the root of the project folder is mandatory
- Code should be documented
- Code should use the PEP 8 style (version 1.7.x)
- All files must be executable

## Concepts Needed

- **Dynamic Programming**: Breaking down the problem into simpler subproblems.
- **Prime Factorization**: Reducing the problem to finding the sum of the prime factors of `n`.
- **Code Optimization**: Approaching problems from an optimization perspective.
- **Greedy Algorithms**: Choosing the best option at each step.
- **Basic Python Programming**: Proficiency in Python, including loops, conditionals, and functions.

## Tasks

### 0. Minimum Operations

Write a method that calculates the fewest number of operations needed to result in exactly `n` H characters in the file.

**Prototype**: `def minOperations(n)`

- Returns an integer
- If `n` is impossible to achieve, return `0`

**Example**:

```python
n = 9
H => Copy All => Paste => HH => Paste => HHH => Copy All => Paste => HHHHHH => Paste => HHHHHHHHH
Number of operations: 6
