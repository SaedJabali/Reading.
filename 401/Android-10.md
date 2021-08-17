# Graphs

A graph is a non-linear data structure that can be looked at as a collection of **vertices** (or *nodes*) potentially 
connected by line segments named **edges**.

### Terminology

1. Vertex - A vertex, also called a “node”, is a data object that can have zero or more adjacent vertices.
2. Edge - An edge is a connection between two nodes.
3. Neighbor - The neighbors of a node are its adjacent nodes, i.e., are connected via an edge.
4. Degree - The degree of a vertex is the number of edges connected to that vertex.

## Types of Graphs

There are many types. This depends on how connected the graphs are to other node/vertices
1. Directed 
2. Undirected
3. Complete
4. Connected
5. Disconnected
6. Acyclic
7. Cyclic
   


1. Directed

A Directed Graph also called a Digraph is a graph where every edge is directed.

this a graph with 7 nodes and 9 edges.

![graph](https://www.researchgate.net/profile/Hakan-Terelius/publication/265428782/figure/fig4/AS:669498856185861@1536632374551/A-directed-graph-with-7-nodes-and-9-edges.png)

2. Undirected 

this is a graph with 7 nodes and 7 edges

![graph](https://www.researchgate.net/profile/Hakan-Terelius/publication/265428782/figure/fig3/AS:669498856194058@1536632374537/An-undirected-graph-with-7-nodes-and-7-edges.png)
     
3. Complete

A complete graph is when all nodes are connected to all other nodes.

![graph](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9e/Complete_graph_K7.svg/1200px-Complete_graph_K7.svg.png)


4. Connected

A connected graph is graph that has all vertices/nodes have at least one edge

![graph](https://gateoverflow.in/?qa=blob&qa_blobid=12366043276973393181)

5. Disconnected

A disconnected graph is a graph where some vertices may not have edges.

![graph](https://i1.wp.com/www.steveclarkapps.com/wp-content/uploads/2019/03/Screenshot-2019-04-30-at-15.15.11.png?resize=812%2C330&ssl=1)

6. Acyclic

An acyclic graph is a directed graph without cycles.

![graph](https://www.statisticshowto.com/wp-content/uploads/2016/04/directed-acyclic-graph.png)

7. Cyclic

A Cyclic graph is a graph that has cycles.

![graph](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1c/Directed_graph%2C_cyclic.svg/1200px-Directed_graph%2C_cyclic.svg.png)


## Graph Representation

We represent graphs through:

1. Adjacency Matrix

2. Adjacency List
   

### Adjacency Matrix

An Adjacency matrix is represented through a 2-dimensional array. If there are n vertices, then we are looking at an n x n Boolean matrix

Each Row and column represents each vertex of the data structure.

![matrix](https://static.javatpoint.com/ds/images/sequential-representation.png)

### Adjacency List

An adjacency list is the most common way to represent graphs.

An adjacency list is a collection of linked lists or array that lists all the other vertices that are connected.
      
![list](https://kajabi-storefronts-production.kajabi-cdn.com/kajabi-storefronts-production/blogs/27029/images/FVKdPFTlTmyXQBiypTge_375dbebabc31445637557c91ec1fe4de.jpg)

## Traversals

1. **Breadth First**

Breadth first traversal is when you visit all the nodes that are closest to the root as possible. From there you traverse outwards, level by level, until you have visited all the vertices/nodes.

Here is what the algorithm breadth first traversal looks like:

1. Enqueue the declared start node into the Queue.

2. Create a loop that will run while the node still has nodes present.

3. Dequeue the first node from the queue
if the Dequeue‘d node has unvisited child nodes, add the unvisited children to visited set and insert them into the queue.
    

1. **Depth First**

In a depth first traversal, we approach it a bit different from the way we do when working with a depth first traversal of a tree. Similar to how the breadth-first uses a queue, we are going to use a Stack for our depth-first traversal.


