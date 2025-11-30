Task members and role divisions

NAME | ROLE

Muhammad Talal Aqdas Team Leader Logic presenter Documenter ( README file)

Maryam Ateeq 2nd Programmer algorithm designer Flowchart Designer Researcher

Sarim Farooq Khan GitHub Manager 1st Programmer Addition of Comments Code and Logic Tester complete documentation

Description

This project is a console-based Sudoku game created in C++. The program begins with a fully solved Sudoku board and removes a set number of random values to turn it into a playable puzzle. The player can fill cells, check the board, request hints, or allow the program to solve the puzzle automatically. A scoring system and timer are included to track the player’s performance.

The game uses recursion, backtracking, randomization, input validation, and grid rule-checking to simulate the logic behind Sudoku solving. This makes the program a good demonstration of algorithm design and structured problem-solving in C++.

Functions used and their explanation

welcome() shows a basic introduction message. display() prints the available actions for the user. printgrid() prints the Sudoku grid. addRandomZeros() removes random values from the grid to create the puzzle. copyGrid() copies one 9x9 grid into another. findEmptyCell() searches the grid for any empty (zero) value. isValidMoveLocal() checks if a number can be placed in a specific cell during hint generation. solveLocal() solves a temporary grid to generate hint values. giveHint() inserts a correct value into a random empty cell. isvalidmove() checks if the player's move follows Sudoku rules. findEmpty() locates empty cells for the solver. solveSudoku() uses backtracking to complete the puzzle automatically. isValidSudoku() checks whether the current grid violates any Sudoku rules.

Working

The game starts with a fully solved 9x9 Sudoku grid. Using the addRandomZeros function, the program removes 30 randomly selected values to create a playable puzzle. The user interacts with the program by entering numbers, taking hints, checking the board, solving the board, or quitting.

Every correct move increases the score. Incorrect moves, hints, and auto-solving reduce the score. The puzzle is completed either when the user fills in all empty cells correctly or when the user selects the solve option. A timer records the total time spent and is displayed at the end of the program.

The program uses rand() and srand(time(0)) to generate randomness for empty cells and hint selection. Backtracking is used to validate moves and solve the puzzle.

Execution instructions

Copy the code into any C++ compiler such as Visual Studio, Dev-C++, or CodeBlocks. Compile the program and then run it. The file is a standard .cpp and runs in the terminal or console window. Screenshots of the code and example outputs can be added separately in a Word file if needed.

Team Collaboration

Team coordination was done through discussions and shared resources. Tasks were divided among members, and each person contributed to separate modules of the program. After individually working on assigned parts, the modules were combined and tested to ensure the final program worked correctly. GitHub was used for collaboration, and each member contributed multiple commits. Proof of these contributions can be added in the Word file as screenshots.

Usage of AI

AI assistance was used only at the beginning to understand the overall logic needed for Sudoku generation and solving. After receiving initial guidance, the team discussed the logic and then wrote the code independently without relying on AI-generated solutions. At the end, AI was used again to provide an example structure for a README file, which helped the team write their own final version. AI served only as a starting reference, while the main work was completed manually by the group.

Future Improvements

Store the results of each move using arrays so the user can review progress. Add file handling to save the final solved puzzle or player history. Introduce difficulty options such as Easy, Medium, and Hard by changing how many cells are cleared. Improve the interface for clearer user guidance. Add color formatting options for better readability.

