# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.




Let $V_1={a_1,a_2,....,a_n}$ and $V_2={b_1,b_2,....,b_n}$ where both, $|V_1|=|V_2|=n$.Then since both graphs are completely connected, every pair of distinct vertices in each graph is connected by an edge. For any two distinct vertices in graph 1 $(G_1)$, u and v from $V_1$ the edge $(u,v) \in E_1$ exists. Same with $G_2$ for any two distinct vertices u' and v' from $V_2$ the edge $(u',v') \in E_2$ exists. bijection can be defined as above $f: V_1 \rightarrow V_2$ so every vertex in $V_1$ is mapped to a unique vertex in $V_2$ and vice versa for $V_2$ to $V_1$. Since $G_1$ is completely connected, it follows that for any pair of distinct vertices $(u,v) \in V_1$, the edge $(u,v) \in E_1$. Under the mapping for $f$ , the images $f(u)$ and $f(v)$ are distinct vertices in $V_2$, so there is an edge between them in $G_2$. So, if $(u, v) \in E_1$, then the pair $(f(u), f(v))$ must also be an edge in  $E_2$, since $G_2$ is completely connected and every distinct pair of vertices is connected by an edge. With the bijection $f$ preserves the adjacency relation between the graphs if two vertices are connected by an edge in $G_1$, their images under $f$ are connected by an edge in $G_2$. This shows that the function $f$ is indeed an isomorphism between $G_1$ and $G_2$, as it keeps the structure of the graph.



"I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice."
