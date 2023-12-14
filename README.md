# **Bidirectional Traveling Salesman Problem(TSP) Solver**

## The Traveling Salesman Problem:
- The bidirectional traveling salesman problem involves finding the most efficient and optimal route that visits a set of nodes and returns to the starting node, minimizing the total traversal cost.
- Unlike the traditional TSP, this variant considers bidirectional connections between nodes, which introduces additional complexity.

### Implementing Branch and Bound Depth-First Search:
- The Branch and Bound Depth-First Search algorithm used in this project utilizes a systematic approach to combinitorial optimization that systematically explores the search space while using upper and lower bounds to prune the branches that cannot lead to an optimal solution.
- The Depth-First Search strategy efficiently traverses the search space, making it a suitable technique for solving this complex optimization problem.

### Implementing Stochastic Local Search:
- In addition to the BnB DFS method, this project implements a Stochastic Local Search algorithm to solve the TSP.
- SLS algorithms leverage randomness to explore the search space and determine the neighborhood of a solution by identifying states or solutions that are adjacent to the current known solution.
- The neighborhood directly influences the exploration of the state space and refers to the set of potential moves that can be applied to the current solution in the search process.
- Our approach of developing a SLS algorithm can strategically circumvent issues that traditional local search algorthms encounter in regards to local minima and maxima.
