````markdown
# N-Queens Problem using Backtracking

## 📌 Project Overview

The N-Queens Problem is a classic problem in computer science that uses the **Backtracking Algorithm**.

The objective is to place **N queens on an N × N chessboard** such that no two queens can attack each other.

This project provides an interactive web application that finds all possible solutions and displays them visually on a chessboard.

## 🎯 Objective

The program ensures that:

- No two queens are in the same row.
- No two queens are in the same column.
- No two queens are on the same diagonal.

## ⚙️ Features

- Enter any value of N
- Find all possible solutions
- Display solutions as chessboards
- Display solution arrays
- Count the total number of solutions
- Count backtracking operations
- Responsive user interface
- Simple and interactive design

## 🧠 Backtracking Approach

The algorithm places one queen at a time, starting from the first row.

Before placing a queen, it checks whether the selected position is safe.

If the position is safe:

1. Place the queen.
2. Move to the next row.
3. Continue recursively.

If no valid position is available:

1. Remove the previously placed queen.
2. Go back to the previous row.
3. Try another position.

This process continues until all possible solutions are found.

## 🧮 Example

### Input

```text
N = 4
````

### Output

```text
Total Solutions = 2
```

The application displays both valid arrangements on the chessboard.

## 📊 Solution Representation

A solution is represented using an array.

Example:

```text
[1, 3, 0, 2]
```

Each index represents a row, and the value represents the column where the queen is placed.

## 🔢 Number of Solutions

| N | Solutions |
| - | --------- |
| 1 | 1         |
| 2 | 0         |
| 3 | 0         |
| 4 | 2         |
| 5 | 10        |
| 6 | 4         |
| 7 | 40        |
| 8 | 92        |

## 💻 Technologies Used

* HTML5
* CSS3
* JavaScript
* Backtracking Algorithm

## 📁 Project Structure

```text
N-Queens-Backtracking/
│
├── index.html
└── README.md
```

The complete application is contained in a single `index.html` file.

## ⏱️ Complexity

### Time Complexity

```text
O(N!)
```

The algorithm explores different possible arrangements of queens using recursive backtracking.

### Space Complexity

```text
O(N)
```

The recursive call stack and board representation require linear space.

## 🌐 Application

The application provides a visual representation of the N-Queens solutions, making it easier to understand how the Backtracking Algorithm explores and eliminates invalid choices.

## ⭐ Conclusion

The N-Queens Problem is an excellent example of the **Backtracking technique**.

This project demonstrates how a problem can be solved by making a choice, checking whether it is valid, recursively continuing the solution, and undoing the choice when necessary.

```
```
