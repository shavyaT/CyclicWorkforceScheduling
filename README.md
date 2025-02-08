# CyclicWorkforceScheduling
Local Search for Constraint Satisfaction Problem: Cyclic  Workforce Scheduling
The Workforce Scheduling Problem (WSP) is a complex Constraint Satisfaction Problem
 which is critical in “round-the-clock” industries such as healthcare. This project focuses
 on cyclic WSP, which involves assigning employees to shifts while satisfying temporal re
quirements, shift sequence rules, and other operational constraints. Due to its NP-hard
 nature, exact solutions become computationally infeasible as problem size increases and de
mands the need for heuristic-based local search. We present an approach combining greedy
 initialization, weighted constraint prioritization, and local search optimization techniques
 to address this challenge. We compared three heuristics: Min-Conflict with Simulated
 Annealing (SA), Min-Conflict with Tabu Search, and Constraint-Guided with Simulated
 Annealing (CG-SA) to minimize conflicts and improve scheduling efficiency. We analyzed
 20 problem instances, including both benchmark datasets and real-world scenarios. Tabu
 Search exhibited scalability and runtime performance, However, for smaller instances, Sim
ulated Annealing and Constraint-Guided heuristics produced competitive outcomes. The
 results show that combining heuristics and optimization methods can help make scheduling
 solutions that are flexible and effective
