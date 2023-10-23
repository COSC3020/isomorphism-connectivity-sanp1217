[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12513263&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Proof:

Suppose $A = (V_1, E_1)$ and $B = (V_2, E_2)$ are two graphs that are isomorphic. By definition, there must be a function $f : V_1 \to V_2$ such that $(u, v) \in E_1$ if and only if $(f(u), f(v)) \in E_2$.

Suppose $A$ is not completely connected. This means there are two vertices $u$ and $v$ in graph $A$ that do not have an edge between them. Since the graphs are isomorphic, there cannot be an edge $(f(u), f(v))$ in $B$, meaning that $B$ is also not completely connected but both graphs are still isomorphic.

Therefore, two graphs do not have to be completely connected to be isomorphic.
