# Computational Intelligence - UFES


This repository was created as a form of study for the Computational Intelligence discipline at UFES, taught by professor Renato Krohling.


In [exercise 1](https://github.com/pedroscortes/computational-intelligence-ufes/tree/main/exercise1) my goal was to minimize the equations F5 and F6 from the article ["Swarm algorithms with chaotic jumps applied to noisy optimization problems" by Mendel, Krohling and Campos (2010)](https://doi.org/10.1016/j.ins.2010.06.007) using algorithms studied in the classroom such as Genetic Algorithm, Differential Evolution and Particle Swarm Optimization.

In [exercise 2](https://github.com/pedroscortes/computational-intelligence-ufes/tree/main/exercise2) I did the same for the equations G1 and G9 from the article ["Constrained optimization based on modified differential evolution algorithm" by Mohamed and Sabry (2012)](https://doi.org/10.1016/j.ins.2012.01.008).

In [exercise 3](https://github.com/pedroscortes/computational-intelligence-ufes/tree/main/exercise3) the objective was to fit the equation y = a + bx + cx² for real data of x and y using the algorithms mentioned above.

In [exercise 4](https://github.com/pedroscortes/computational-intelligence-ufes/tree/main/exercise4) the objective was to train a neural network (multi-layer perceptron) for a time series prediction problem. Furthermore, we had to optimize the network's hyperparameters using an evolutionary algorithm.


# Genetic Algorithm

A genetic algorithm is a computational method for optimization inspired by natural selection. It begins with a population of potential solutions, evaluates each solution's fitness, selects individuals based on their fitness scores, and then uses genetic operators like crossover and mutation to produce offspring. The offspring replace some individuals in the population, guiding it towards better solutions. This process iterates until a termination condition is met, such as finding a satisfactory solution. Genetic algorithms are effective for solving complex optimization problems by mimicking evolutionary principles to efficiently explore solution spaces and find optimal or near-optimal solutions.

Read more [here.](https://doi.org/10.1007/s11042-020-10139-6)



# Differential Evolution

The differential evolution algorithm is an optimization technique that iteratively evolves a population of candidate solutions by combining and modifying existing ones using differential operators. It's particularly suited for complex, nonlinear, and multi-dimensional optimization problems. Unlike genetic algorithms, which operate on binary strings or other representations, differential evolution typically works directly with continuous parameter vectors. Additionally, while genetic algorithms rely on genetic operators like crossover and mutation, differential evolution employs differential operators to generate new candidate solutions. These differences make differential evolution well-suited for certain optimization tasks, especially those involving continuous variables and high-dimensional spaces.

Read more [here.](https://doi.org/10.1016/j.aej.2021.09.013)



# Particle Swarm Optimization

The particle swarm optimization (PSO) algorithm is a computational optimization technique inspired by the social behavior of bird flocking or fish schooling. It simulates the movement of a group of particles through a search space to find optimal solutions. Each particle represents a potential solution to the optimization problem, and they adjust their positions based on their own best-known position and the collective information shared among the swarm. By iteratively updating their positions according to simple rules, particles converge towards promising regions of the search space, ultimately leading to the discovery of optimal or near-optimal solutions. PSO is particularly effective for continuous optimization problems and has been successfully applied in various fields such as engineering, finance, and data science.

Read more [here.](https://doi.org/10.1007/s11831-021-09694-4)



# Multi-layer Perceptron (MLP)

A multi-layer perceptron (MLP) neural network is a type of artificial intelligence model used to recognize patterns and make decisions. It consists of several layers of connected nodes, called neurons. The first layer receives input data, the last layer produces the output, and the layers in between are called hidden layers. Each neuron in a layer is connected to neurons in the next layer, and these connections have weights that adjust during training to improve the model's accuracy. When the network is trained, it learns to transform the input data into the correct output by adjusting these weights. MLPs are powerful because they can learn and model complex relationships in data.

Read more [here.](https://doi.org/10.1016/S1352-2310(97)00447-0)
