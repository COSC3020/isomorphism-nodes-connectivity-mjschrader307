# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

---

Answer:

Need to show that there is a bijective function, $f$, that maps vertices in $A$ to those in $B$, where adjacency is preserved.

Two vertices are adjacent in one graph if their corresponding vertices are adjacent in the other.

### $A$ and $B$ are complete graphs

- For all $i$ and $j$ in $\{1, 2, ..., n\}$ and $i \neq j$:
    - Edges $\{a_i, a_j\}$ are all in $E_A$
    - Edges $\{b_i, b_j\}$ are all in $E_B$

There are $n$ edges in both sets $E_A$ and $E_B$

### Vertex sets written out

$V_A = \{a_1, a_2, a_3, ..., a_n\}$

$V_B = \{b_1, b_2, b_3, ..., b_n\}$

### Introduce function, $f$

There must be a function $f$ that can map $a_i$ in $V_A$ to $b_i$ in $V_B$: $f(a_i) = b_i$ for all $i$ in $\{1, 2, ..., n\}$

This would mean that for all distinct $i$ and $j$ in $\{1, 2, ..., n\}$, the edge $\{a_i, a_j\}$ in $E_A$ maps to $\{f(a_i), f(a_j)\}$ or $\{b_i, b_j\}$ in $E_2$

If $f$ is bijective, this works both ways.

---

**I certify that I have listed all sources used to complete this exercise, including the use
of any Large Language Models. All of the work is my own, except where stated
otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is
suspected, charges may be filed against me without prior notice.**