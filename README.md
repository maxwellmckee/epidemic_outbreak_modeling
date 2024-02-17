# epidemic_outbreak_modeling

Outbreak Dynamics and Centrality Analysis: This repository contains Python analyses and simulations focused on understanding outbreak dynamics within a network, exploring the impact of transmission rates on infection spread, and evaluating how the centrality of the initial infected node affects the outbreak's progression.

## Overview

The project is divided into three parts, each addressing different aspects of outbreak modeling and analysis within a constructed network of individuals based on their interactions.

### Part 1: Outbreak Modeling

- **Objective**: Model an outbreak within a school setting using the SIS (Susceptible-Infectious-Susceptible) model.
- **Methodology**: Construct an undirected graph from `fludata.txt`, simulate outbreak scenarios with specified transmission and recovery rates, and visualize the dynamics of the outbreak.
- **Key Tasks**:
  - Simulate outbreaks and visualize the number of infected and susceptible individuals over time.
  - Fit an exponential growth model to the initial phase of the outbreak and compare theoretical growth rates with empirical data.
  - Calculate and visualize theoretical values for the time constant (τ) based on different assumptions about the infection spread.

### Part 2: Transmission Rate Analysis

- **Objective**: Investigate how varying the transmission rate affects the spread of infection.
- **Methodology**: Perform simulations across a range of transmission rates to observe changes in the outbreak size and duration.
- **Key Tasks**:
  - Conduct simulations to determine the average time constant (τ) for each transmission rate.
  - Compare experimental and theoretical endemic sizes as a function of the transmission rate.
  - Visualize how changes in transmission rate influence the outbreak's characteristics.

### Part 3: Patient-0 Centrality & Infection Spread

- **Objective**: Examine the effect of the centrality of the initial infected node ("patient-0") on the outbreak's spread.
- **Methodology**: Simulate the outbreak from each node in the network, analyze various centrality measures, and correlate these with the speed and extent of the outbreak.
- **Key Tasks**:
  - Identify successful simulations based on initial infected nodes and calculate centrality metrics for these nodes.
  - Correlate centrality metrics with the outbreak's spread to identify predictors of outbreak severity.
  - Analyze results to understand the relationship between node centrality and outbreak dynamics.

## Tools and Libraries

The analysis is conducted using Python, with key libraries including:
- `networkX` for network construction and analysis.
- `matplotlib` for data visualization.
- `scipy` for curve fitting and statistical analysis.
- `numpy` for numerical computations.

## Note

The project is an attempt to apply theoretical models to practical scenarios to understand the dynamics of disease spread in networked communities. Particular attention is given to the role of network structure and individual node characteristics in influencing the course of an outbreak.

