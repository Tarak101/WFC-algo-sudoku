# SudokuSolverWFC
Sudoku Solver using a Wave Function Algorithm.

# How does it work?
The Wave Function Collapse (WFC) algorithm was developed by Maxim Gumin. For a more detailed page about the algorithm, see the [Wikipedia page](https://en.wikipedia.org/wiki/Wave_function_collapse).

# Overview

The Sudoku Solver is a web application that allows users to solve Sudoku puzzles with ease. Utilizing an algorithm inspired by Wave Function Collapse (WFC), the application offers an intuitive interface for entering custom puzzles or selecting from a range of preloaded puzzles categorized by difficulty: easy, hard, and expert.

## Features

- **Puzzle Entry:** Input your Sudoku puzzle into a 9x9 grid.
- **Solve Feature:** Click to solve the puzzle using an advanced algorithm.
- **Reset Option:** Clear the grid to enter a new puzzle.
- **Sample Puzzles:** Access preloaded puzzles with different difficulty levels.
- **Adaptive Interface:** Enjoy a sleek, dark-themed, user-friendly design.

## Requirements

- **Python 3.x:** Required programming language
- **Flask:** Python framework for building web applications
- **NumPy:** Library for performing numerical computations

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Tarak101/WFC-algo-sudoku.git
   
   
2. **Install Dependencies from `requirements.txt`:**

   ```bash
   pip install -r requirements.txt



## Usage
1. **Run the Application:**

    ```bash
   python app.py
   
 # Using the Web Interface

- **Enter Puzzle:** Fill in the Sudoku grid with your puzzle, leaving empty cells as blank spaces.
- **Solve Puzzle:** Press the "Solve" button to compute and display the solution in the grid.
- **Reset Grid:** Use the "Clear" button to empty the grid and start a new puzzle.
- **Load Sample Puzzles:** Select "Easy," "Hard," or "Expert" to load preset puzzles.

## Wave Function Collapse Algorithm

The solver utilizes an approach inspired by the Wave Function Collapse (WFC) algorithm:

1. **Value Determination:** For each empty cell, determine possible values based on Sudoku rules (row, column, and 3x3 subgrid constraints).
2. **Minimize Choices(Entropy):** Choose the cell with the least number of possible values to fill next.
3. **Recursive Backtracking:** Continuously place numbers and backtrack when encountering conflicts, until the puzzle is solved.



   
   
   




