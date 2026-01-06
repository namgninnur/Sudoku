# Sudoku
Python script with multiple explained logic steps to solve medium difficulty 9x9 sudokus

Enter your sudoku via the pandas dataframe object called 'data'

The script will then iterate through multiple solver steps to identify possible candidates for each cell, and then use logic steps to coalesce to a final solution.
- The script will advise for each time a specific cell is solved and the rationale for why.
- Error checking module is in place to ensure that the final solution is viable
- Kill-switches for various solution logic steps exist to enable the user to see which steps contribute to faster solutions.
- Max loop of 500 steps exists if puzzle cannot be solved by existing implemented logic. (Future enhancements coming!)

Enjoy and happy sudoku-ing!

Future enhancements in the works:
1) Developing a web interface for this solver.
2) Packaging this web interface into an Android mobile app.
3) Buidling object recognition capabilities and using OCR to enable users to upload a photo of a partially complete sudoku and for the system to automatically fill out the current grid based on the data in the photo.
4) Data analytics of solving steps used across a library of sudokus to determine if future logic changes improve the following OKRs:
- Enable correct solution to be found - Improve successful completion rate % to 100% for medium and 50% for hard sudokus.
- Enable solver to be faster - reduce average solving time
5) Enable the logic to be more dynamic based on an understanding of the current problem state of a partially completed sudoku.
- both avoiding duplicated erroneus steps on known cells, as well as,
- more intelligent routing of the solver based on key indicators (e.g. current solved %)