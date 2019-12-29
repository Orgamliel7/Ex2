# Ex2
The task were written by: Shahar Niknazar - 316416668 Or Gamliel - 208202663

We have 3 classes in our project:
DGraph  - implements the interface "graph" and represents a directional weighted graph.
 * The interface has a road-system or communication network in mind - and should support a large number of nodes (over 100,000).
 * The implementation based on an efficient compact representation.
 
Graph_Algo –  implements the interface "graph_algorithms", represents bunch of algorithms based on the graph we've created in DGraph. 
GUI  - 



DGraph class have few functions:


1) **getNode(int key)**

2) **getEdge(int src, int dest)**

3) **addNode(node_data n)**

4) **connect(int src, int dest, double w)**

5) **Collection<node_data> getV()** 

6) **Collection<edge_data> getE(int node_id)**

7) **node_data removeNode(int key)**

8) **edge_data removeEdge(int src, int dest)** 

9) **nodeSize()** 

10) **edgeSize()** 

11) **getMC()** 


The class have 3 constructors:

Default constructor.
Copy constructor.
String constructor - get string of monom and turn it to new monom.
we also have getters and setters:

power getter and setter.
coefficient getter and setter.

Graph_Algo class have few functions:

1) **init(graph g)**

2) **graph copy()** 

3) **init(String file_name)** 

4) **save(String file_name)** 

5) **isConnected()** 

6) **shortestPathDist(int src, int dest)** 

7) **List<node_data> shortestPath(int src, int dest)** 

8) **List<node_data> TSP(List<Integer> targets)** 



The class have 3 constructors:
default constructor.
string constructor - get string of polynom and make it to new polynom.
copy constructor.
Polynom class have few functions:



stdDraw:

This class represents a graphical interface here we can display a graph, Run algorithms on it and View their results.
