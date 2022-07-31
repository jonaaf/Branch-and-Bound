# Branch-and-Bound
Humble attempt to implement the Branch and Bound algorithm

The current work is an attempt to gain more knowledge about the workhorse for solving Mixed Integer Programming problems (MIPs), namely the Branch and Bound algorithm.

This repository contains:
- Implementation for the 0/1 Knapsack problem
- Implementation for the Traveling Salesman Problem

Benchmarks and optimality checks were performed using the non-commercial solver SCIP.

Unfortunately, this first trial of both implementations yield sub optimal solutions for a minor fraction of the problems, and the performance struggles when increasing the problem sizes.
