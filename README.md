# Hamiltonian Cycle Visualizer

## Overview

This project is an interactive visualization tool for the Hamiltonian Cycle problem, developed for the Algorithms I course.

The Hamiltonian Cycle problem asks whether a graph contains a cycle that visits every vertex exactly once and returns to the starting point. It is a well-known NP-complete problem.

---

## Features

* Interactive graph visualization
* Brute-force algorithm (O(n!))
* Dynamic Programming (Held-Karp) algorithm (O(2^n * n^2))
* Step-by-step execution
* Play / Pause / Reset controls
* Pseudocode highlighting
* Real-time explanations
* Comparison mode (Brute Force vs DP)
* Random graph generator
* Difficulty levels (Small, Medium, Large)
* Visualization of failed paths
* Performance warning for large inputs
* NP-Completeness explanation section

---

## Algorithms

### Brute Force

Generates all permutations of vertices and checks for a valid Hamiltonian cycle.

Time Complexity: O(n!)

---

### Held-Karp Dynamic Programming

Uses bitmasking to store intermediate results and avoid recomputation.

State:
dp[S][v] = whether there exists a path visiting vertices in S and ending at v

Time Complexity: O(2^n * n^2)

---

## Educational Purpose

This tool is designed to help students:

* Understand NP-complete problems
* Visualize algorithm behavior
* Compare algorithm efficiency
* Learn dynamic programming concepts

---

## Technologies Used

* HTML5
* CSS3
* Vanilla JavaScript (ES6)
* SVG for visualization

---

## How to Use

1. Open the deployed website (GitHub Pages link)
2. Select or create a graph
3. Choose an algorithm
4. Use controls to step through execution
5. Compare results using comparison mode

---

## Deployment

This project is deployed using GitHub Pages.

---

## Author

[Omid Ghadim]

Course: BCS 309 – Algorithms I
Instructor: Dr. Arash Kermani
