---
title: "A Parallel GPU Algorithm for the Stepping Stone Puzzle"
collection: publications
category: technical-project
permalink: /projects/2025-Parallel-GPU-Algorithm-for-the-Stepping-Stone-Puzzle
excerpt: >
        University of Minnesota - Twin Cities, Fall 2025<br>
        Applied Parallel Programming (EE 5351) Final Project<br>
        Instructor: John Sartor<br>
        Co-author: Peter Weiblen
---

University of Minnesota - Twin Cities, Fall 2025

Applied Parallel Programming (EE 5351) Final Project

Instructor: John Sartor

Co-author: Peter Weiblen

# Project Summary

The stepping stone puzzle features a state space that rapidly grows as the input increases. The primary known solution approach is to check all possible solution states for a given input N, with N ≥ 7 not yet being solved. We propose a parallel GPU algorithm for solving the stepping stone puzzle, with each GPU thread taking in a board and checking the entire state space of said board. This proves to be more efficient than an equivalent CPU implementation, solving N = 5 in ~1.3 hours, compared to ~4 hours by the previous best algorithm. Extrapolations of computation time for N ≥ 6 also result in theoretically saved time. However, it is still not enough to solve N = 7 in a reasonable timeframe. Further optimization is needed to solve this problem at N ≥ 7.

# Personal Contributions
* Helped set up the initial algorithm to run on the GPU
* Implemented multiple optimizations to improve performance
    * Implemented packing of x position, y position, and numerical values of board positions into single 32 bit integers
    * Implemented symmetry-reduction functions to eliminate equivalent reflected and rotation board states
    * Implemented additional smaller memory optimizations
* Wrote the Abstract, Introduction, Boards, Multiboards, Verification, Performance, Board in Shared Memory, Future Work, & Conclusion sections of the report

# Skills Demonstrated:
* Parallel GPU Computation

# Technologies Used
* C++
* CUDA

# [Download Full Report](https://asbmeyers.github.io/files/A_Parallel_GPU_Algorithm_for_the_Stepping_Stone_Puzzle.pdf)

