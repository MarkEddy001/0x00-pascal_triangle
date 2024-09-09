# 0x07. Rotate 2D Matrix

## Description

This project involves implementing an in-place algorithm to rotate an n x n 2D matrix by 90 degrees clockwise. The challenge requires a good understanding of matrix manipulation and in-place operations in Python.

## Concepts

### Matrix Representation in Python

- 2D matrices are represented using lists of lists in Python.
- Accessing and modifying elements in a 2D matrix.

### In-place Operations

- Performing operations on data without creating a copy of the data structure.
- Minimizing space complexity by modifying the matrix in place.

### Matrix Transposition

- Transposing a matrix involves swapping rows and columns.
- Implementing matrix transposition as a step in the rotation process.

### Reversing Rows in a Matrix

- Manipulating rows of a matrix by reversing their order as part of the rotation process.

### Nested Loops

- Using nested loops to iterate through 2D data structures like matrices.
- Modifying elements within nested loops to achieve the desired rotation.

## Resources

### Python Official Documentation

- [Data Structures](https://docs.python.org/3/tutorial/datastructures.html) (list comprehensions, nested list comprehension)
- [More on Lists](https://docs.python.org/3/tutorial/datastructures.html#more-on-lists)

### GeeksforGeeks Articles

- [Inplace rotate square matrix by 90 degrees](https://www.geeksforgeeks.org/inplace-rotate-square-matrix-by-90-degrees/)
- [Transpose a matrix in Single line in Python](https://www.geeksforgeeks.org/transpose-matrix-single-line-python/)

### TutorialsPoint

- [Python Lists](https://www.tutorialspoint.com/python/python_lists.htm) for basics of list manipulation in Python.

## Requirements

- Allowed editors: `vi`, `vim`, `emacs`
- All files will be interpreted/compiled on Ubuntu 20.04 LTS using `python3` (version 3.8.10)
- All files should end with a new line
- The first line of all files should be exactly `#!/usr/bin/python3`
- A `README.md` file, at the root of the folder of the project, is mandatory
- Code should use the `pycodestyle` style (version 2.8.0)
- No module imports allowed
- All modules and functions must be documented
- All files must be executable

## Task

### 0. Rotate 2D Matrix

Given an n x n 2D matrix, rotate it 90 degrees clockwise.

#### Prototype

```python
def rotate_2d_matrix(matrix):
    """
    Rotates an n x n 2D matrix 90 degrees clockwise in place.

    Args:
        matrix (list of list of int): The n x n matrix to rotate.

    Returns:
        None
    """
