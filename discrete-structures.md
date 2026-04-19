---
title: Discrete Structures I
math: true
---

<!-- Load KaTeX CSS and JS -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.13.11/katex.min.css">
<script defer src="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.13.11/katex.min.js"></script>
<script defer src="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.13.11/contrib/auto-render.min.js"
    onload="renderMathInElement(document.body, {delimiters: [{left: '$$', right: '$$', display: true}, {left: '$', right: '$', display: false}]});"></script>

	

Below you can find my hand-written lecture notes for the course Discrete Structures I at the University of Heidelberg. 
It is based mostly in following references:

- [Graph Theory, by Reinhard Diestel](https://katalog.ub.uni-heidelberg.de/cgi-bin/titel.cgi?katkey=68186198&sess=5f7a7579bfaf3a64015bcea36e810349&art=f&kat1=freitext&kat2=ti&kat3=au&op1=AND&op2=AND&var1=diestel%20graph%20theory&var2=&var3=)
- [Introduction to Graph Theory, by Douglas West](https://katalog.ub.uni-heidelberg.de/cgi-bin/titel.cgi?katkey=65556254&sess=b50347097cae2224671ddc674cf2f8f3&query=introduction%20to%20graph%20theory)
- [Combinatorial Optimization, by Bernhard Korte and Jens Vygen](https://katalog.ub.uni-heidelberg.de/cgi-bin/titel.cgi?katkey=68239473&sess=b4681c0144bdad684b6bf44a4fee8e1a&art=f&kat1=freitext&kat2=ti&kat3=au&op1=AND&op2=AND&var1=Korte&var2=Combinatorial%20optimisation&var3=)
  
![Here](/DS1-lucian-lecture-notes.pdf) you can find the typed lecture notes taken by my student, Lucian von Hagen, based on the classes.

![Lecture 1](/DS1-lecture-notes/L1.pdf): 
- Basic notation and definitions
- Graph isomorphisms
- The hand-shaking lemma
- For every $G$ there is $H$ such that $H$ is $\Delta(G)$-regular and $G \subseteq H$.

![Lecture 2](/DS1-lecture-notes/L2.pdf): 
- Existence of subgraphs with large minimum degree
- Lower bounds for the size of the longest path and longest cycle in terms of the minimum degree
- Walks, distance and their basic properties
- Diameter, girth and their relationship

![Lecture 3](/DS1-lecture-notes/L3.pdf): 
- Moore's theorem: lower bound on the number of vertices of a graph with large minimum degree and large girth
- Corollary: Logarithmic upper bound on the girth for graphs with minimum degree at least 3
- Acyclic graphs, trees and leaves

![Lecture 4](/DS1-lecture-notes/L4.pdf): 
- Equivalent definitions of tree
- Algorithms, running time and function growth
- Decision problems
- The classes P and NP

![Lecture 5](/DS1-lecture-notes/L5.pdf): 
- Examples of classical problems in P and in NP
- The classes co-NP, NP-hard and NP-complete
- The graph scanning algorithm and its running time

![Lecture 6](/DS1-lecture-notes/L6.pdf): 
- BFS, DFS and their main properties

![Lecture 7](DS1-lecture-notes/L7.pdf): 
- The Kruskal's algorithm for finding minimum spanning trees
- Euler tours
- A connected graph is Eulerian if and only if all vertices have even degree

![Lecture 8](/DS1-lecture-notes/L8.pdf): 
- Dirac's theorem
- Chvátal's theorem

![Lecture 9](/DS1-lecture-notes/L9.pdf): 
- The travelling salesperson problem (TSP) and the metric TSP
- The double tree algorithm is a 2-approximation algorithm for the metric TSP
- The Christofides' algorithm is a 3/2-approximation algorithm for the metric TSP

![Lecture 10](/DS1-lecture-notes/L10.pdf): 
- A graph is bipartite if and only if it does not contain cycles of odd length
- Matchings, vertex covers and König's theorem

![Lecture 11](/DS1-lecture-notes/L11.pdf): 
- Hall's theorem
- Every $k$-regular bipartite graph has a perfect matching (1-factor)
- Every $2k$-regular graph has a 2-factor
- Statement of Tutte's theorem and the Gallai decomposition theorem

![Lecture 12](/DS1-lecture-notes/L12.pdf): 
- Proof of Tutte's theorem and the Gallai decomposition theorem
- If a graph is 3-regular and 2-edge-connected, then it has a perfect matching
- The Hopcroft-Karp algorithm

![Lecture 13](/DS1-lecture-notes/L13.pdf): 

- The Hopcroft-Karp algorithm for finding matchings in bipartite graphs

![Lecture 14](/DS1-lecture-notes/L14.pdf): 
- Upper bounds on the running time of the Hopcroft-Karp algorithm
- Connectivity and separations
- Mader's theorem on the existence of $k$-connected subgraphs with large average degree

![Lecture 15](DS1-lecture-notes/L15.pdf): 
- Menger's theorem and a generalisation
- Caracterisation of $k$-connectivity via internally disjoint paths between every pair of vertices
  
