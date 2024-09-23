---
aliases:
  - Beck-Chevalley
---

>[!lemma]
Pullback along the $\infty$-functor $f: T \to S$ induce the $\infty$-functor $f^* : Grpd_{/S} \to Grpd_{/T}$.  This functor is right adjoint to the functor $f_{!}: Grpd_{/T} \to Grpd_{/S}$  given by post composition with $f$. The following **Beck-Chevalley** condition holds for $\infty$-groupoids: given a pullback square
```tikz
\usepackage{tikz-cd}
\begin{document}
\begin{tikzcd}
	\cdot \arrow[r, "f"] \arrow[d, swap, "p"] & \cdot \arrow[d, "q"] \\
\cdot \arrow[r, swap, "g"] & \cdot
\end{tikzcd}
\end{document}
```

there is a canonical equivalence of functors $$p_{!} \circ f^{*} = g^{*} \circ q_{{!}}.$$ 