# GNSS Adjustment Optimization Codes

## Introduction

This repository contains codes for optimizing Global Navigation Satellite Systems (GNSS) adjustment using various optimization algorithms. The codes are designed to improve the accuracy and reliability of GNSS network adjustments.


## Optimization Algorithms

The following optimization algorithms are implemented in this repository:

- **ABC (Artificial Bee Colony)**: An optimization algorithm inspired by the foraging behavior of honeybees.
- **BSA (Backtracking Search Algorithm)**: A population-based evolutionary algorithm designed for global optimization.
- **GSA (Gravity Search Algorithm)**: An optimization algorithm inspired by the law of gravity.
- **PSO (Particle Swarm Optimization)**: An algorithm based on the social behavior of birds and fish.
- **WDE (Weighted Differential Evolution)**: An optimization algorithm that combines differential evolution with a weighted strategy.

## Files

- All data files used for GNSS adjustment are stored with the name 'LSU20.'
- To run any of the optimization algorithms, locate and execute the 'main' file associated with that algorithm.

## Data
The data should contains 4 Matrices: data (n x 3), connection (m x 2), Disatnace (m x 1), dxdydz (m x 3)
Where n number of points, m number of baselines. 
dxdydz=data(connections(:,1),:)-data(connections(:,2),:)

## Usage

1. Choose the optimization algorithm you wish to use.
2. Locate the 'main' file for that algorithm in the repository.
3. Change the Data name to your data name file in (load your_data)
4. Run the 'main' file to initiate the optimization process.
5. Monitor the algorithm's progress and results.

## Contributing

If you would like to contribute to this project or have any questions, please feel free to contact us, email:ahmedzen09@hotmail.com.
