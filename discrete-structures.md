---
title: Discrete Structures I
---

<!-- Load MathJax -->
<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>


# Lecture 1: The Basics of Graph Theory

Graphs provide a simple way to represent and study relationships between different objects. 

> **Definition:** A graph is a pair of sets $(V, E)$, where $V$ is a finite set and $E$ is a set of unordered pairs of elements of $V$. That is,
> $$
E \subseteq \{ \{u, v\} \mid u \neq v, u, v \in V \}.
> $$
> $V$ is called the set of vertices, and $E$ is the set of edges.



<div style="border:1px solid; padding:10px">
    <strong>Definition:</strong> A graph is a mathematical structure used to model pairwise relations between objects. $$a$$ and $b$ are called the vertices of the graph, and the edge $\{a, b\}$ represents the relation between them.
</div>



This structure can model a wide variety of real-world situations and allows us to solve many different types of problems.
They are particularly useful for modeling:

**Social Networks**: Graphs are often used to study social networks. Each person is a vertex, and a connection between two people (like a friendship or a message) is an edge. Graphs help us understand how people are connected, who are the most influential people, or how information spreads.

**Transportation Networks**: In transportation, cities can be represented as vertices, and roads or flights between cities as edges. Graphs help solve problems like finding the shortest path from one city to another (e.g., for a GPS system), or planning a route that visits several cities with the least amount of travel (like the [Traveling Salesman Problem](https://www.youtube.com/watch?v=LL1t1WbdMZw)).

**Scheduling Management**: 
 Imagine a train schedule, where trains have to be run at certain times.
 Here, the trains are the vertices, and if two of them overlap in time, there is an edge between them.
 The goal is to find the minimum number of crews needed to run all the trains without any conflicts. Graph colorings can be used to solve type of problem. See this [video](https://www.youtube.com/watch?v=295ONmLcj60) for an example.

 **Graphs are a very versatile tool for modelling all kinds of problems, but they are also an interesting mathematical object in their own right.**
