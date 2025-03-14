# Global Air Traffic Network Analysis - COMP8880 Network Science Assignment 1

This project analyzes the global air traffic network using the provided dataset for the COMP8880: Network Science course. The project answers several questions related to basic graph attributes, connected components, degree distribution, betweenness centrality, shortest paths, and flight routes in the global air transportation network.

## Questions Answered:

### 1. Basic Graph Attributes:
- **How many nodes and undirected edges are in this network?**
  - This question calculates the number of nodes and undirected edges in the network.

### 2. Connected Components:
- **How many connected components are in this graph, and how many nodes and edges do the largest component contain?**
  - This question calculates the number of connected components in the graph and provides the number of nodes and edges in the largest connected component.

### 3. Top 10 Nodes in the Largest Component:
- **Denote the largest component as G. List the top 10 nodes in G having the highest degree, and how many other nodes are they connected to.**
  - This question finds the 10 nodes with the highest degree in the largest connected component of the network.

### 4. Degree Distribution:
- **Plot the degree distribution of the network G. Each data point is a pair (x, y), where x is a positive integer and y is the fraction of nodes in the network with degree equal to x.**
  - Also, plot the degree distribution on a log-log scale.
  - The range of x is restricted to the minimum and maximum degrees, and data points with zero entries are filtered out. Both axes on the log-log plot are in base 10.

### 5. Diameter and Longest Shortest Path:
- **What is the (unweighted) diameter of the giant component G in this network?**
  - This question calculates the diameter of the largest connected component and lists the longest (unweighted) shortest path between two cities in the network.

### 6. Flight Route from Canberra to Cape Town:
- **What is the smallest number of flights you need to take to get from Canberra (CBR) to Cape Town (CPT)?**
  - This question finds the shortest path (in terms of the number of flights) between Canberra and Cape Town, and lists all the airports you would pass through.

### 7. Centrality of Airports/Cities:
- **Which airport/city in G is most “central” by having the largest betweenness?**
  - This question calculates the betweenness centrality for each city/airport and lists the top 10 cities with the highest betweenness centrality values.

## Project Structure:
- `air_traffic_network_analysis.ipynb`: Jupyter notebook containing the analysis and answers to the questions.
- `global-cities.dat`: Data file containing city/airport information.
- `global-net.dat`: Data file containing the air traffic network (edges between nodes).
- `plots/`: Directory containing degree distribution plots and log-log scale plots.

## Requirements:
- Python 3.x
- NetworkX
- Pandas
- Matplotlib
- NumPy

## Setup Instructions:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Global-Air-Traffic-Network-Analysis.git
   cd Global-Air-Traffic-Network-Analysis
