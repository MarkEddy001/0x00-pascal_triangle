# Lockboxes Project

## Overview

This repository contains the solution to the Lockboxes project, a Python programming challenge. The project involves working with a list of locked boxes, where each box may contain keys to other boxes. The goal is to determine if all the boxes can be opened.

## Concepts Needed

To solve this project, you'll need to understand the following concepts:

1. **Lists and List Manipulation**: You'll need to know how to work with lists in Python, including accessing elements, iterating over lists, and modifying lists dynamically.

2. **Graph Theory Basics**: Although not explicitly required, knowledge of graph theory can be helpful. You can think of the boxes and keys as nodes and edges in a graph. This can help you approach the problem using traversal algorithms like Depth-First Search (DFS) or Breadth-First Search (BFS).

3. **Algorithmic Complexity**: Understanding the time and space complexity of your solution is important. It can help in writing more efficient algorithms.

4. **Recursion**: Some solutions might require a recursive approach to traverse through the boxes and keys.

5. **Queue and Stack**: You'll need to know how to use queues and stacks if implementing a BFS or DFS algorithm.

6. **Set Operations**: Understanding how to use sets for keeping track of visited boxes and available keys can optimize the search process.

## Additional Resources

- **Mock Technical Interview**: This is a simulated technical interview where you'll be asked to solve the Lockboxes problem.

- **Requirements**: The requirements for the project include the use of the Python programming language, specific editor requirements, and specific file requirements.

- **Tasks**: The project involves writing a method named `canUnlockAll` that takes a list of lists as input and determines if all the boxes can be opened.

## Sample Code

The sample code provided in the project is as follows:

```python
#!/usr/bin/python3

def canUnlockAll(boxes):
    # Your code here
    pass

boxes = [[1], [2], [3], [4], []]
print(canUnlockAll(boxes))

boxes = [[1, 4, 6], [2], [0, 4, 1], [5, 6, 2], [3], [4, 1], [6]]
print(canUnlockAll(boxes))

boxes = [[1, 4], [2], [0, 4, 1], [3], [], [4, 1], [5, 6]]
print(canUnlockAll(boxes))
