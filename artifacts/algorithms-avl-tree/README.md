# AVL Tree Artifact

# Overview

This artifact represents my work from CS 300 – Data Structures and Algorithms, enhanced for CS 499 to demonstrate mastery of algorithmic complexity, balanced tree structures, and performance-oriented design. The project implements an AVL Tree, a self-balancing binary search tree used for efficient data lookup and insertion.

The program loads course information, inserts nodes into the AVL tree, and provides in-order traversal to display courses alphabetically.

# Original Project Summary

In the original project, I built:

A basic AVL tree

Insert and search functionality

File parsing to load course/prerequisite data

Sorted traversal for course listing

While functional, several areas needed enhancement:

Rotation logic lacked clarity

Balancing checks needed refinement

Documentation for rotations was limited

Some height calculations were inconsistent

# Enhancements for CS 499

1. Improved Rotation Logic

I refined and corrected the four AVL rotation types:

Left-Left (LL)

Right-Right (RR)

Left-Right (LR)

Right-Left (RL)

Enhancements ensure:

Accurate balancing after insertions

No height desynchronization

Correct handling of complex imbalance cases

2. Strengthened Height & Balance Factor Calculations

I improved the functions governing:

Subtree height retrieval

Node height resetting

Balance factor computation

This reduced errors and improved data integrity.

3. Added Detailed Documentation and Comments

To make the algorithm accessible and professional, I added:

Clarifying comments for each rotation

Step-by-step logic descriptions

An explanation of how balance is maintained

This helps peers and instructors easily follow the algorithm.

# How to Run

Open the project folder in a C++ environment (VS Code, CLion, etc.)

Compile using a standard C++ compiler:

g++ main.cpp -o coursePlanner


Place the input file in the same directory.

Run the program:

./coursePlanner
