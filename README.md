#### Comparison of Local search algorithms for solving Travelling salesman problem

Travelling sales person problem is a complex combinatorial optimization problem which is used tond the most efficient and minimum cost route to travel various cities in a map without passing through the same city and return to the start city. Local search algorithms such as Hill Climbing, Simulated Annealing, Genetic Algorithms help researchers to solve NP-Hard problems like TSP. These algorithms would not give the exact best answer; however they can give the optimal or near optimal answers and help researchers to optimize their problems. Each algorithm
is implemented, evaluated individually and optimized according to its parameters. This project aims at comparing the algorithms based on performance andfinding the best algorithm for the problem. The criteria for performance is the quality of solution and run time of algorithm.

##### Execution

All three algorithms can be executed using their respective files and the visualization is also implemented in the same file.

##### Results Analysis

###### Runtime

Run time for Genetic and Hill climbing increased exponentially with increase in number of cities. Whereas in case of simulated annealing, run time increased but not
exponential. Run time is affected by the set of parameters used. If in genetic algorithm, we reduce population size there will be an improvement in run time but, the solution quality decreases. Same is the case of hill climbing, if number of iterations is decreased, run time will have an improvement. Thus, if run time is used for comparison then, Simulated annealing is the best performer.

###### Solution Quality

All the three algorithms produced nearly same minimum distance. Here solution quality is also affected by the parameters. In genetic algorithm, if we increase
population size without bothering about run time, we would get optimal results. Similarly, with increase in number of iterations for hill climbing, we get good results. In case of simulated annealing, if we have very lowfinal temperature, we would see satisfying results. In all these cases run time should not become an issue. Thus from the outputs, we can see that Genetic algorithm produced near optimal results i.e.; even if it takes time it produces good results.
