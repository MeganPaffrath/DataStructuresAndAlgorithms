# Graphs
[Return to Main](../README.md)

- A **graph** represents connections among items
  - Implementation examples: geographical maps, roads in a city, a computer network, social networks
  - Each **vertex** (or node) represents an item within the graph
  - **Edges** represent a connection between 2 vertices
    - **Edge weights** may be used in cases such as flight paths to represent the distance or time of a travel route
    - **Edge Directions**
      - **Directed Graphs** have edges directed from one vertex to another (ex: flight path)
      - **Undirected Graphs** are graphs without directed edges (ex: 2 way roads)
  - Two vertices are **adjacent** if they are connected by an edge
    - Note: when given vertices A ----> B
      - A is adjacent to B
      - B is adjacent from A
  - A **path** is a sequence of edges leading from a source to destination vertex
    - **path length** is the number of edges in the path
  - The **distance** between 2 vertices is the count of edges following the shortest path between the vertices
  - An **adjacency list** is a graph representation in which each vertex has a list of adjacent vertices where each list item represents an edge
    - Size: O(V+E) where v = vertices and E = edges (which appear twice)
- Formally:
  - Graphs are a mathematical concept
    - A graph G is defined as G = (V,E)




[Return to Main](../README.md)
