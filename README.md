# C-CSP-Backtracking

A collection of **Constraint Satisfaction Problems (CSP)** solved using **Backtracking algorithms** implemented in C. These examples demonstrate standard foundational AI approaches to solving puzzle verification, combinatorial search, and constraint graph satisfaction map-coloring scenarios.

## 📂 Repository Contents

| File | Description | Problem Type |
| :--- | :--- | :--- |
| `Cryptarithmetic.c` | Solves the classic puzzle: `SEND + MORE = MONEY` where each unique letter represents a unique digit. | Cryptarithmetic / Constraint Match |
| `Sudokusolver.c` | Implements a robust 9x9 Sudoku grid configuration backtracking solver. | Constraint Placement Grid |
| `Telanganamapcolouring.c` | Assigns discrete colors to adjacent districts of Telangana ensuring no two share the same color boundary. | Graph Coloring (Local) |
| `main.c` | Solves the classic 7-region Australia Map Coloring benchmark problem using 3 distinct colors. | Graph Coloring (Global) |

## 🛠️ How to Compile and Run

Make sure you have a standard C compiler toolchain installed (`gcc`).

```bash
# Example: Compiling the Sudoku Solver
gcc Sudokusolver.c -o sudoku

# Run the executable
./sudoku
