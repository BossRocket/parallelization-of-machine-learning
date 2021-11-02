## About 

This research was performed in Spring, 2021 as a final project for my Concepts of Parallel and Distributed Processing class with Dr. Damian Dechev.

## Abstract

This research proposes that a concurrent implementation of the gradient descent algorithm in machine  earning is much more efficient than a sequential version. Provided a dataset containing the garage names at the University of Central Florida, occupancy rates, days of the week, and times, the algorithm will generate quadratic regression models of the data. While the sequential version is successful in accomplishing the creation of these gradients, they consume more time and memory than desired when testing at a higher number of epochs to obtain a more accurate model. Combining the mini-batch stochastic gradient descent approach along with Python’s multiprocessing module to achieve parallelism yields faster results, while also allowing the user to create more accurate models.
