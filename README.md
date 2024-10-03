# Distributed Algorithms - K-Means

This project implements the **K-Means algorithm** ([described in this article]https://arxiv.org/pdf/1203.6402) in the context of distributed algorithms. It was developed as part of the course **Physics of Data - Management and Analysis of Physics Datasets mod.B**, academic year 2023-2024.

## Authors
- Alessio Tuscano
- Chiara Tramarin 

## Project Description
The goal of this project is to implement and benchmark the **K-means|| algorithm** across a distributed system using **Dask**. We will develop an alternative version of K-means||, aiming to identify the optimal cluster configuration that maximizes the efficient use of available resources. The performance will be evaluated based on several metrics, including execution time, memory usage, and task distribution.

For benchmarking, we will use the **KDD Cup 1999 Dataset** (available [here](https://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html)). The dataset will help assess how well the algorithm handles large-scale data, with a focus on scalability and resource optimization.



