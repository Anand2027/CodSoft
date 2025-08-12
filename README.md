# CodSoft Internship C++ Tasks


This repository contains the C++ source code for tasks completed during the CodSoft internship program. Each task is a console-based application designed to demonstrate fundamental programming concepts and problem-solving skills in C++.

## Tasks Overview

This repository includes the following C++ projects:

### Task 1: Number Guessing Game
A simple game where the program generates a random number between 1 and 100, and the user must guess it. The program provides feedback ("Too high!" or "Too low!") until the user guesses the correct number and reports the total number of attempts taken to win.

### Task 2: Simple Calculator
A basic command-line calculator that performs arithmetic operations.
*   **Operations:** Addition (+), Subtraction (-), Multiplication (*), Division (/)
*   **Input:** Takes two numbers and an operator from the user.
*   **Features:** Includes error handling for division by zero and invalid operator input.

### Task 3: Tic-Tac-Toe Game
A classic, two-player Tic-Tac-Toe game implemented in the console.
*   **Gameplay:** Players 'X' and 'O' take turns marking spaces on a 3x3 grid.
*   **Win Condition:** The game automatically detects a win by checking all rows, columns, and diagonals.
*   **Features:** Handles draws (stalemate) when the grid is full and offers an option to play again after a game concludes.

### Task 4: To-Do-List Manager
A command-line application for managing a personal to-do list.
*   **Features:**
    *   **Add Task:** Add a new task to the list.
    *   **View Tasks:** Display all tasks with their current status ([Pending] or [Completed]).
    *   **Mark Task as Complete:** Update the status of a specific task to "Completed".
    *   **Remove Task:** Delete a task from the list.

## Getting Started

To compile and run these programs, you will need a C++ compiler like `g++` installed on your system.

### Prerequisites
*   A C++ compiler (e.g., `g++` on Linux/macOS, MinGW on Windows).

### Compilation and Execution

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/Anand2027/CodSoft.git
    cd CodSoft
    ```

2.  **Navigate to a task directory.** For example, to run the Number Guessing Game:
    ```sh
    cd "Task 1"
    ```
    *Note: The source files in the repository are not named with a `.cpp` extension. You may need to rename them (e.g., rename `Task 1` to `task1.cpp`) or compile them directly if your shell supports it.*

3.  **Compile the code.** The following example assumes you have renamed the file:
    ```sh
    # Example for Task 1 (assuming the file is renamed to task1.cpp)
    g++ task1.cpp -o guessing_game
    ```

4.  **Run the compiled executable:**
    ```sh
    ./guessing_game
    ```

Repeat these steps for any other task by navigating to its respective directory (`Task 2`, `Task 3 (TIC-TAC-TOE)`, `task 4( To-Do-List)`), compiling its source code, and running the resulting executable.
