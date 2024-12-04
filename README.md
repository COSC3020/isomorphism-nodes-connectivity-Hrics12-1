# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.


Let $V_1={a_1,a_2,....,a_n}$ and $V_2={b_1,b_2,....,b_n}$ where $|V_1|=|V_2|=n$. Then since both graphs are completely connected, every pair of distinct vertices in each graph is connected by an edge. For any two distinct vertices in graph $G_1$, $u$ and $v$ from $V_1$, the edge $(u,v) \in E_1$ exists. Same with graph $G_2$, for any two distinct vertices $u'$ and $v'$ from $V_2$, the edge $(u',v') \in E_2$ exists.

Since $A$ and $B$ have the same number of nodes, let the set of vertices $V_1 = V_2 = \{v_1, v_2, ..., v_n\}$. Since $G_1$ is completely connected, for every pair of vertices $v_x, v_y$ that exists in $V_1$ where $x \ne y$, there exists an edge that connects these vertices. Since $G_2$ is also completely connected, the same applies for $V_2$.

Let $f: V_1 \rightarrow V_2$ be defined as $f(v_x) = v_x$ for all $x$ from $1$ to $n$. $f$ is a bijection because each vertex in $V_1$ maps to a unique vertex in $V_2$.

Since every node is connected to every other node in graph $G_1$, and the same is true for graph $G_2$, then the conditions for isomorphism are met. So, under the mapping for $f$, the structure for $f(u)$ and $f(v)$ are distinct vertices in $V_2$, so there is an edge between them in $G_2$. So, if $(u, v) \in E_1$, then the pair $(f(u), f(v))$ must also be an edge in $E_2$, since $G_2$ is completely connected and every distinct pair of vertices is connected by an edge.

With the bijection $f$ having the adjacency relation between the graphs, if two vertices are connected by an edge in $G_1$, their images under $f$ are connected by an edge in $G_2$. This shows that the function $f$ is isomorphism between $G_1$ and $G_2$, as it keeps the structure of the graph.

So, since graphs $A$ and $B$ have the same number of nodes and are completely connected, they must be isomorphic.




"I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice."
