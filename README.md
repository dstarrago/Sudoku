# Sudoku
Text based Sudoku solver

The algorithm introduced here to solve sudoku puzzles is a hybrid method that combines logic deduction with a backtracking algorithm. Whenever possible it tries to infere new sudoku numbers by applying deduction rules, that are based on the sudoku constrains, to the numbers already in the grid. When deduction is not possible, a backtraking algorithm searches the space of possible solutions starting with the most feasible cell. When the value of a new cell is found by the backtracking algorithm, the deduction algorithm is applied again to the updated grid to maximize the opportunities to find new sudoku numbers. 

Most sudoku puzzles can be solved by the algorithm within 7 to 10 recursive backtracking levels. The hardest sudoku puzzles are solved in less than 15 recursive backtracking levels.

Program written in Python 3, using NumPy and Jupyter Notebook.
