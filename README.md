Network Analysis & Path OptimizationProject OverviewThis project explores the application of Linear Algebra and Graph Theory to analyze network connectivity and find optimal paths.
By representing graphs as matrices, we use mathematical operations—rather than traditional traversal algorithms—to uncover structural patterns, determine reachability, 
and calculate the most efficient routes between nodes.+3Core FeaturesMatrix-Based Connectivity:
Uses adjacency matrices and matrix powers ($A^k$) to identify paths of specific lengths and determine overall reachability without manual traversal.
Path Optimization: Implements the Floyd-Warshall algorithm to compute all-pairs shortest paths in weighted, dense graphs.
Structural Insight: Utilizes the Laplacian Matrix ($L = D - A$) and spectral analysis (eigenvalues) to detect disconnected components and evaluate network stability.
+2Scalable Simulation: Built with Python and NumPy for fast, automated matrix operations.
+1Tech StackLanguage: PythonLibraries: NumPy (for matrix operations and linear algebra) Mathematical Concepts: Matrix Powers, Floyd-Warshall Algorithm, Laplacian Spectral Analysis.
UsageThe core implementation includes functions to:Generate an Adjacency Matrix for directed or undirected graphs.Compute the Reachability Matrix to see if node $i$ can reach node $j$.
Run the Floyd-Warshall simulation to output a shortest-path distance matrix.Calculate Laplacian Eigenvalues to gain insights into the network's cohesion.
**Project Contributors:
University: BML Munjal University
Group Members: Ritesh, Piyush, Pulkit, and Rohit **
