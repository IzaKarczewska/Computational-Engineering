# Computational-Engineering

AGH Academic Course "Computational Intelligence in Data Analysis"

## Monte Carlo Algorithm

This project contains estimating the value of π (pi) using Monte Carlo method. The Monte Carlo algorithm is a classic probabilistic method that uses random sampling to approximate mathematical quantities.

### Function Descriptions

1. Generate random points within a square with side length 'r'.
2. Determines whether each point is inside or outside the circle.
3. Estimates the value of pi using the Monte Carlo method.
4. Visualizes the generated points and the quarter circle.

### Vizualization

In addition to the above functions, the Jupyter notebook also includes various generated visualizations. This help in understanding the behavior of the estimation of π as the number of random points increases.

#### 1. Temporary Estimated Value of π vs. Number of Random Points

A plot showing the temporary estimated value of π as the number of random points increases.

#### 2. Mean Squared Error in Estimation of π vs. Number of Points

A plot showing the mean squared error in the estimation of π as the number of points increases.

#### 3. Boxplot of π Estimation of π vs. Number of Points

A boxplot showing the distribution of π estimates after 50 series for different numbers of points.

## Traveling Salesman Problem solved using Genetic Algorithm

This project contains a Python implementation of a genetic algorithm which solve Traveling Salesman Problem.

### Problem Descripiton

TSP asks the questionL _"Given a list of cities and the pairwise distances, what is the shortest possible route that visits each city exactly once and returns to the starting city?"_

### Parameters of the mail function

- `num_cities`: Number of cities in the TSP problem instance.
- `num_individuals`: Number of individuals in the population.
- `generations`: Number of generations.
- `mutation_rate`: Probability of mutation for each individual (default: 0.02).
- `crossover_rate`: Probability of crossover for each pair of individuals (default: 0.8).
- `area_size`: Size of the area within which cities are randomly distributed (default: 200).
- `selection_type`: Type of selection mechanism ('roulette' or 'ranking').

### Visualization functions

#### Visualizations are provided for:

1. **Shortest Route in Each Population**: Shows the shortest route found in generation during the algorithm's execution.
2. **Improvement of Fitness Function**: Illustrates the improvement of the fitness value (shortest route length) across generations.

Eperimental approach - by changing the parameters of the algorithm, the aim was to optimize the solutions. Finally, presented a graph of the values ​​of the quality function in all generations and a histogram of route lengths.
