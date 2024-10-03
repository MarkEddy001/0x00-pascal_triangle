# Prime Game

## Project Description
The Prime Game is a strategic game played between two players, Maria and Ben, where they take turns selecting prime numbers from a set of consecutive integers. The player who cannot make a legal move loses the game. The goal of this project is to determine the winner of multiple rounds of this game based on provided ranges of integers.

## Implementation Details
The project contains a function called `isWinner(x, nums)` that determines the winner of the game. The parameters are:
- `x`: the number of rounds to be played.
- `nums`: an array of integers representing the upper limits of the consecutive integers for each round.

The implementation utilizes a strategy based on prime numbers, game theory, and dynamic programming to ensure an optimized solution. Players must strategically remove primes and their multiples from the game space.

## Usage
To run the game, execute the script and call the `isWinner` function with the appropriate parameters. Ensure that the project adheres to the PEP 8 style guide and runs on Python 3.4.3 or higher.

## Interview Expectations
During a technical interview for this project, candidates are expected to demonstrate the following skills:
- Understanding prime numbers and efficient algorithms for selection.
- Knowledge of game theory and its applications in strategic decision-making.
- Ability to implement algorithms in Python, employing lists and loops effectively.
- Familiarity with dynamic programming to enhance performance in repetitive calculations.

## Example
An example invocation of the `isWinner` function would be:

```python
isWinner(5, [2, 5, 1, 4, 3])
# Expected Output: Ben




### Instructions for Creating the README.md File in Vim

1. Open your terminal.
2. Navigate to your project directory where you want to create the README file.
3. Type `vim README.md` and press Enter.
4. Press `i` to enter insert mode.
5. Copy and paste the above content into Vim.
6. Press `Esc`, then type `:wq` and press Enter to save and exit.

This README provides an overview of the project, its implementation details, usage instructions, expectations for interviews related to this project, an example usage case, and a conclusion summarizing its significance.
