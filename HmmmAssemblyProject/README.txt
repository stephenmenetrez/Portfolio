This project is the sudoku-esque solver.

What do I mean by sudoku-esque:
This project is focused on a 3x3 grid of numbers. 
In order to a grid to be a solution, each column and each row must sum to 7.
There are no requirements about which numbers are used or how many times a given number is used.

How it runs:
When ran, the program will prompt the user for 9 number entries. These values make up the 3x3 grid.
It will then scan the entries sequentially to see if there are missing values.
If there are missing values, it will check if 1, 2, or 4 are values that make the grid a solution.
This process is done recursively.
If a missing value is found, while the check to see if the imputed value is a solution it will impute other missing values.
In this way, it checks all combinations of 1, 2, and 4 for all missing values.
