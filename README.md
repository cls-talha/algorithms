# Graph Algorithms and Sorting/Searching Algorithms

This repository contains Python implementations of various graph algorithms including Depth First Search (DFS), Breadth First Search (BFS), and Dijkstra's Algorithm, as well as linear search and insertion sort algorithms.

## Graph Algorithms

### Depth First Search (DFS)

Depth First Search is an algorithm for traversing or searching tree or graph data structures.

#### Usage

To use DFS, import the `dfs` function from `dfs.py` into your Python script and call it with the graph and starting vertex as parameters.

#### Time Complexity

DFS has a time complexity of O(V + E), where V is the number of vertices and E is the number of edges.

### Breadth First Search (BFS)

Breadth First Search is an algorithm for traversing or searching tree or graph data structures.

#### Usage

To use BFS, import the `bfs` function from `bfs.py` into your Python script and call it with the graph and starting vertex as parameters.

#### Time Complexity

BFS has a time complexity of O(V + E).

### Dijkstra's Algorithm

Dijkstra's Algorithm is an algorithm for finding the shortest paths between nodes in a graph.

#### Usage

To use Dijkstra's Algorithm, import the `dijkstra` function from `dijkstra.py` into your Python script and call it with the graph and starting vertex as parameters.

#### Time Complexity

Dijkstra's Algorithm has a time complexity of O((V + E) log V).

## Sorting/Searching Algorithms

### Linear Search

Linear search is a simple search algorithm that sequentially checks each element of the list until a match is found or the whole list has been searched.

#### Usage

To use linear search, import the `linear_search` function from `linear_search.py` into your Python script and call it with the list and the value to search for.

#### Time Complexity

Linear search has a time complexity of O(n), where n is the number of elements in the list.

### Insertion Sort

Insertion sort is a simple sorting algorithm that builds the final sorted array (or list) one item at a time.

#### Usage

To use insertion sort, import the `insertion_sort` function from `insertion_sort.py` into your Python script and call it with the list you want to sort.

#### Time Complexity

Insertion sort has a time complexity of O(n^2) for average and worst-case scenarios, and O(n) for the best-case scenario when the list is already sorted.
