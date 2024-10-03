---
title: Discrete Structures I
---

<!-- Load KaTeX CSS and JS -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.13.11/katex.min.css">
<script defer src="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.13.11/katex.min.js"></script>
<script defer src="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.13.11/contrib/auto-render.min.js"
    onload="renderMathInElement(document.body, {delimiters: [{left: '$$', right: '$$', display: true}, {left: '$', right: '$', display: false}]});"></script>



# Lecture 1: The basics of Graph Theory

Graphs provide a simple way to represent and study relationships between different objects. 

<div style="border:1px solid; padding:10px">
    <strong>Definition (Graphs):</strong> 

A graph is a pair of sets $G = (V, E)$, where $V=V(G)$ is a finite set and $E=E(G)$ is a set of unordered pairs of elements of $V$. That is, 
$$ E \subseteq \{ \{u, v\} \mid u \neq v, u, v \in V \}. $$
$V$ is called the set of vertices, and $E$ is the set of edges.
We often write $uv$ or $vu$ for an edge $\{u,v\}$.
</div> <br>

Sometimes $v(G) = \mid V(G) \mid$ is called the *order* of the graph $G$ and $e(G) = \mid E(G)\mid$ is called the *size* of the graph $G$.

Graphs can model a wide variety of real-world situations and allows us to solve many different types of problems.
They are particularly useful for modeling:


**Social Networks**: Graphs are often used to study social networks. Each person is a vertex, and a connection between two people (like a friendship or a message) is an edge. Graphs help us understand how people are connected, who are the most influential people, or how information spreads.

**Transportation Networks**: In transportation, cities can be represented as vertices, and roads or flights between cities as edges. Graphs help solve problems like finding the shortest path from one city to another (e.g., for a GPS system), or planning a route that visits several cities with the least amount of travel (like the [Traveling Salesperson Problem](https://www.youtube.com/watch?v=LL1t1WbdMZw)).

**Scheduling Management**: 
 Imagine a train schedule, where trains have to be run at certain times.
 Here, the trains are the vertices, and if two of them overlap in time, there is an edge between them.
 The goal is to find the minimum number of crews needed to run all the trains without any conflicts. Graph colourings can be used to solve this type of problem. See this [video](https://www.youtube.com/watch?v=295ONmLcj60) for an example.

 **Graphs are a very versatile tool for modelling all kinds of problems, but they are also an interesting mathematical object in their own right.**

 Before we delve into the puzzles and problems of graph theory, we need to establish some vocabulary to facilitate our communication.

<div style="border:1px solid; padding:10px">
    <strong>Definition (Adjacency, incidence, endpoints):</strong> 

Two vertices $u,v$ are <strong>adjacent</strong> in a graph $G$ if $uv\in E(G)$. 
We say that $u$ and $v$ are <strong>endpoints</strong> of the edge $uv$, and we say that an edge $e \in E(G)$ is <strong>incident</strong> with a vertex $v$ if $v\in e$.
</div> 
<br>

Local properties are important for understanding global properties of a graph. To explore this, we need to define the degree of a vertex.

<div style="border:1px solid; padding:10px">
    <strong>Definition (Degree and neighbourhood):</strong> 

For a graph $G$ and a vertex $v\in V(G)$,
we say $u\in V(G)$ is a <strong>neighbour</strong> of $v$ if $uv\in E(G)$.
The set of all neighbours of $v$ is denoted by 
$$
N_G(v) = \{ u \in V(G) \mid uv \in E(G) \}.
$$ 
We refer to it as the <strong>neighbourhood</strong> of $v$.
The <strong>degree</strong> $d_G(v)$ of $v$ is the size of the neighbourhood of $v$. That is, $d_G(v) = \mid N_G(v) \mid$.
</div> 
<br>
