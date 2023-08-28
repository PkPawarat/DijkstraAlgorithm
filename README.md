# Dijkstra-Algorithm
Dijkstra Algorithm using C# with finding paths as location in X and Y plane


# Dijkstra Algorithm Pathfinding

This is a C# implementation of the Dijkstra algorithm for pathfinding on a 2D grid using a custom-defined graph structure. The algorithm calculates the shortest path between two nodes in a weighted graph, where each node represents a location in a 2D plane.

# Overview
The code consists of three main classes: Node, DijkstraAlgorithm, and PriorityQueue, along with a Main method to demonstrate the algorithm. Here's an explanation of each part of the code:

Node Class: Represents a location on the 2D plane. It has X and Y properties to store the coordinates of the location. It also implements the IComparable interface for comparison based on the coordinates.

DijkstraAlgorithm Class: Implements the Dijkstra algorithm to find the shortest path between two nodes in the graph. It uses a dictionary (graph) to store the adjacency list of the graph, where each node maps to a list of its neighbors and their associated costs. The class provides methods to add edges between nodes and to find the shortest path using Dijkstra's algorithm.

PriorityQueue Class: A priority queue implementation used in Dijkstra's algorithm. It enqueues elements based on their priorities (costs) and dequeues the element with the lowest priority.

Main Method: Demonstrates the usage of the DijkstraAlgorithm class. It defines a graph with nodes representing locations and adds edges between them. Then, it calculates the shortest path between two nodes and visualizes the graph and the shortest path on the console.

# Usage
Node Class: Represents a single location with X and Y coordinates. It allows comparison based on these coordinates.

DijkstraAlgorithm Class: Provides methods to add edges between nodes and calculate the shortest path between two nodes using the Dijkstra algorithm.

PriorityQueue Class: Implements a priority queue for efficient processing of nodes in Dijkstra's algorithm.

Main Method: Demonstrates the Dijkstra algorithm by creating a graph with locations (nodes) and calculating the shortest path between two nodes (A and G). It then visualizes the graph with the shortest path using DrawMapWithShortestPath.

# Visualization
The code includes two visualization methods: DrawMap and DrawMapWithShortestPath. The latter method creates a grid that displays the locations, the shortest path, and the entire graph. The grid is printed to the console, using * to represent the graph nodes and P to represent the nodes in the shortest path.

Feel free to replace these visualization methods with your preferred visualization approach if you'd like to visualize the graph differently.

# How to Run
Ensure you have a C# compiler (part of the .NET SDK) installed on your system.

Copy and paste the provided code into a .cs file.

Open a Command Prompt or terminal window.

Navigate to the directory containing the .cs file using the cd command.

Compile the code using the C# compiler (csc). Run the following command:

    csc "YourFileName.cs"


Replace "YourFileName.cs" with the actual name of your file.

After compiling successfully, an executable file with the same name as your script file but with a .exe extension will be generated (e.g., YourFileName.exe).

Run the compiled executable by entering its name in the Command Prompt:


    YourFileName.exe


The console output will display the shortest path and the visualized grid with the graph and shortest path.

Feel free to modify the graph, add more nodes, and experiment with different scenarios to understand how the Dijkstra algorithm works for pathfinding in a 2D grid.




# Noted that if you can't run this script in the 'visual studio code', please use the 'visual studio' program.
