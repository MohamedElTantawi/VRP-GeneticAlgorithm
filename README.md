# VRP-GeneticAlgorithm
This repository contains an implementation of the Vehicle Routing Problem (VRP) using a Genetic Algorithm. The VRP is a well-known combinatorial optimization problem where a fleet of vehicles must serve a set of customers, each with a given demand, while minimizing the total distance traveled.
## Introduction
The VRP-GeneticAlgorithm project aims to solve the VRP using a genetic algorithm approach. The genetic algorithm is a metaheuristic inspired by the process of natural selection and evolution. It starts with an initial population of candidate solutions and applies genetic operators such as mutation and crossover to produce new generations of better solutions.
## Features
- Solve VRP instances with various problem sizes and complexities.
- Optimize vehicle routes to minimize the total distance traveled.
- Support for multiple depots and multiple vehicles.
- Genetic algorithm implementation with customizable parameters.
### First Part: Genetic Algorithm
A full standard genetic algorithm is implemented using Python.
### Second Part: Variants over the standard GA
Modify the standard version of genetic algorithms developed in the previous step, by choosing only one of the following:

Genetic Algorithm with Varying Population Size The idea is to introduce the concept of "ageing" into the population of chromosomes. Each individual will get a "life-expectancy" value, which directly depends on the fitness. Parents are selected randomly, without paying attention to their fitness, but at each step all chromosomes gain +1 to their age, and those reaching their life-expectancy are removed from the population. It is very important to design a good function calculating life-expectancy, so that better individuals survive during more generations, and therefore get more chances to be selected for crossover.

Cellular Genetic Algorithm The idea is to introduce the concept of "neighbourhood" into the population of chromosomes (for instance, placing them into a grid-like arrangement), in such a way that each individual can only perform crossover with its direct neighbours.
## Contributing
### Github
Contributions to this project are welcome. If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.
### Blog 
Visit our blog at:
- https://cogsci6.wordpress.com/ 
## Acknowledgments
We would like to express our gratitude to the "Fleet" team for their contributions to this project. The team members include:

- Omar Hatem
- Mohamed Tantawi
- Farida Helmy
- Maram Benamer
- Salma Kish
- Haidy Tohfa


Their expertise, dedication, and collaborative spirit were instrumental in the development and success of this implementation of the Vehicle Routing Problem using a Genetic Algorithm. We extend our heartfelt thanks to each team member for their valuable contributions.
