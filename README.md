# Sudoku
Python script with multiple explained logic steps to solve medium difficulty 9x9 sudokus

Enter your sudoku via the pandas dataframe object called 'data'

The script will then iterate through multiple solver steps to identify possible candidates for each cell, and then use logic steps to coalesce to a final solution.
- The script will advise for each time a specific cell is solved and the rationale for why.
- Error checking module is in place to ensure that the final solution is viable
- Kill-switches for various solution logic steps exist to enable the user to see which steps contribute to faster solutions.
- Max loop of 500 steps exists if puzzle cannot be solved by existing implemented logic. (Future enhancements coming!)

Enjoy and happy sudoku-ing!
