# Connected Component Finder (CCF) in PySpark

This project implements the Connected Component Finder (CCF) algorithm using PySpark, based on the paper "CCF: Fast and Scalable Connected Component Computation in MapReduce" by Kardes et al. (2014). The algorithm efficiently finds connected components in large-scale graphs using a distributed computing approach.

## Authors

- Min HUANG
- Mounia ZRIGUI
- Mohamed KOUHOU

## Features

- Two implementations of CCF:
  1. CCF-Iterate: Basic iterative implementation
  2. CCF-Iterate with secondary sorting: Optimized version for better performance on large graphs
- Utilizes PySpark for distributed processing
- Tested on the Google Web Graph dataset
- Performance analysis and visualization of results
- Graph visualization using NetworkX

## Contents

- PySpark implementation of CCF algorithms
- Data loading and cleaning for the Google Web Graph dataset
- Performance comparison between the two CCF implementations
- Visualization of execution time and new pairs generated per iteration
- Graph visualization of the connected components

## Requirements

- PySpark
- Python 3.x
- matplotlib
- networkx

## Usage

1. Set up a Spark environment (local or cluster)
2. Run the provided PySpark code in a Jupyter notebook or as a Python script
3. Load the Google Web Graph dataset (`web-Google.txt`)
4. Execute the CCF algorithms and analyze the results

## Performance Analysis

The notebook includes performance analysis of both CCF implementations:
- Execution time per iteration
- Number of new pairs generated per iteration
- Total execution time

## Visualization

- Plots of execution time and new pairs vs. iterations for both implementations
- Graph visualization of the connected components using NetworkX

## Dataset

The project uses the [Google Web Graph dataset](https://snap.stanford.edu/data/web-Google.html), which is loaded and preprocessed within the code.

## References

Kardes, H., Agrawal, S., Wang, X., & Sun, A. (2014). CCF: Fast and Scalable Connected Component Computation in MapReduce. In Proceedings of the 2014 IEEE International Conference on Big Data.
