# Binary Search Tree OOP

This project implements a binary search tree in Java using an object-oriented design. Each node stores a value and points to its left and right child, allowing values to be inserted and organized efficiently.

## Features
* **Dynamic Insertion:** Maintains binary search ordering ($left < parent \le right$) for incoming numeric values.
* **Recursive Depth Calculation:** Computes the maximum height of the tree recursively without relying on global state or external counters.
* **Structural Analysis:** Compares different insertion sequences to demonstrate how order affects tree balance and total depth.

## Run the project
```bash
javac src/*.java
java -cp src Main
```

The sample program creates two trees and prints their depths to show how insertion order affects structure.
