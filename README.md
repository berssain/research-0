
# Heuristic Algorithm for Solving the Tower of Hanoi Problem

This repository contains the Python implementation of the heuristic algorithm developed to solve the Tower of Hanoi problem using the **Best-First Search** method. The algorithm minimizes memory usage and optimizes the necessary moves to solve the puzzle by evaluating direction and time parameters through a heuristic function.

## Algorithm Description

The algorithm is designed to solve the problem for an arbitrary number of disks across three towers. Starting from a 2D geometric projection of the original 3D model, a heuristic function `h(k)` is defined, composed of two sub-functions: `d(k)` (to evaluate the direction of movement) and `t(k)` (to evaluate the time). These functions ensure that at each step, only the correct disk is moved based on the lowest heuristic values, optimizing both the number of moves and memory usage.

## Repository Content

- **Python Source Code**: The algorithm implementation with auxiliary functions to simulate and verify each step of the process.
- **Test Files**: Output generated during the simulation of disk movements.
- **Usage Instructions**: How to run the code and test the algorithm with different numbers of disks.

## Execution

To run the code, simply clone this repository and execute the main Python file. The program will ask for the number of disks to start the puzzle.

\`\`\`bash
python hanoi_algorithm.py
\`\`\`

## Reference

This code was developed as part of the academic paper:  
*Heuristic function in an algorithm of First-Best search for the problem of Tower of Hanoi: optimal route for n disks*  
Authors: Erick Berssaín García Ventura and Norma Elva Chávez Rodríguez, (2017).

If you use this code in your research or project, please credit the authors and consider citing the paper.
