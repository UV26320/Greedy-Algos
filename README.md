# Greedy Algos

## Overview

Greedy algorithms are a class of algorithms that make locally optimal choices at each stage with the hope of finding a global optimum. These algorithms are often used for optimization problems where the goal is to find the best solution from a set of possibilities. Greedy algorithms are simple, efficient, and often provide good approximations to the optimal solution.

## Characteristics of Greedy Algorithms

1. **Greedy Choice Property**: A global optimum can be arrived at by selecting a local optimum at each step.

2. **Optimal Substructure**: An optimal solution to the problem contains an optimal solution to subproblems.

## Common Greedy Algorithms

1. **Activity Selection**
   - **Problem**: Given a set of activities with start and finish times, select the maximum number of activities that do not overlap.
   - **Example**: Scheduling tasks to maximize productivity.

2. **Huffman Coding**
   - **Problem**: Given a set of characters and their frequencies, construct a binary tree that minimizes the total encoding length.
   - **Example**: Data compression.

3. **Dijkstra's Algorithm**
   - **Problem**: Find the shortest path from a source vertex to all other vertices in a weighted graph.
   - **Example**: Shortest route in a road network.

4. **Fractional Knapsack**
   - **Problem**: Given weights and values of items, maximize the total value of items in a knapsack with a weight capacity.
   - **Example**: Packing a knapsack with limited weight capacity.

## Usage

To use greedy algorithms, follow these general steps:

1. **Define the Problem**: Clearly define the problem and identify the objective.

2. **Greedy Choice**: Identify the greedy choice at each step that seems to be the best option locally.

3. **Optimal Substructure**: Prove that the greedy choice at each step leads to an optimal solution for the problem.

4. **Implement Algorithm**: Write code to implement the algorithm based on the identified greedy choices.

## Conclusion

Greedy algorithms offer a straightforward approach to solving optimization problems by making locally optimal choices. While they may not always guarantee the global optimum, they often provide practical and efficient solutions to a wide range of problems. Understanding the characteristics and common use cases of greedy algorithms is essential for effective problem-solving in various domains.
