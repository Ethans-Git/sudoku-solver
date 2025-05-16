**Sudoku Solver**
A Java program that solves 9x9 Sudoku puzzles using recursive backtracking. The puzzle is read from a file at runtime, allowing easy testing with custom inputs.

Features:
- Solves standard 9x9 Sudoku puzzles
- Uses recursive backtracking
- Tracks constraints across rows, columns, and 3x3 subgrids
- Reads puzzle input from a text file
- Outputs the solution or reports if none exists

How It Works:
The program prompts the user to enter the name of a puzzle file (e.g., puzzle.txt) and attempts to solve it. Blank cells in the puzzle are represented by 0s.

Sample Input File: sample-puzzle.txt
Each line must contain exactly 9 digits, with no spaces. For example:

530070000

600195000

098000060

800060003

400803001

700020006

060000280

000419005

000080079

Output:
If the puzzle is solvable, the solution is printed. Otherwise, the program states that no solution exists and prints the current puzzle state.

Usage
1. Compile
javac sudoku-solver.java
2. Run
java Sudoku

You'll be prompted:
Enter the name of the puzzle file:
Type the name of your file (e.g., puzzle.txt) and press Enter.

Author
Ethan Quach
