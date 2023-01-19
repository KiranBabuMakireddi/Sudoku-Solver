# Introduction: Sudoku Solver

Getting Started
Simply download the sudoku-solver.cpp file found in the Sudoku-Solver/ directory. Run it using any standard C++ compiler. In case of any errors or compatibility issues, submit an issue in this git.

Once downloaded, compiled and run; the program will require the user to input the Sudoku puzzle into it. There are two ways to do this.

The user can either input the values manually one-by-one when the program is running.

The user can write all the values into a file, seperated by whitespaces. The file can have any name or extension. When the program is running, the user will be prompted to simply enter the name of the file (with extension). Below is an example of how the contents of such a file might look. Look at the sample.txt files in the same directory for more examples.

#Sample
`
0 0 0  0 0 0  6 8 0
0 0 0  0 7 3  0 0 9
3 0 9  0 0 0  0 4 5

4 9 0  0 0 0  0 0 0
8 0 3  0 5 0  9 0 2
0 0 0  0 0 0  0 3 6

9 6 0  0 0 0  3 0 8
7 0 0  6 8 0  0 0 0
0 2 8  0 0 0  0 0 0
`
#After Solving
Once solved, the Sudoku puzzles shall be displayed like this.
`
++=====================================++
|| 1   7   2 || 5   4   9 || 6   8   3 ||
++-----------++-----------++-----------++
|| 6   4   5 || 8   7   3 || 2   1   9 ||
++-----------++-----------++-----------++
|| 3   8   9 || 2   6   1 || 7   4   5 ||
++=====================================++
|| 4   9   6 || 3   2   7 || 8   5   1 ||
++-----------++-----------++-----------++
|| 8   1   3 || 4   5   6 || 9   7   2 ||
++-----------++-----------++-----------++
|| 2   5   7 || 1   9   8 || 4   3   6 ||
++=====================================++
|| 9   6   4 || 7   1   5 || 3   2   8 ||
++-----------++-----------++-----------++
|| 7   3   1 || 6   8   2 || 5   9   4 ||
++-----------++-----------++-----------++
|| 5   2   8 || 9   3   4 || 1   6   7 ||
++=====================================++
`
