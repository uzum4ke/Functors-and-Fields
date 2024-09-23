---
aliases:
  - pullback lemma
---

>[!lemma] 
If in a prism diagram of $\infty$-groupoids
```tikz
\usepackage{tikz-cd}
\begin{document}
\begin{tikzcd}
	\cdot \arrow{r} \arrow{d} & \cdot \arrow{r} \arrow{d} & \cdot \arrow{d} \\
	\cdot \arrow{r} & \cdot \arrow{r} & \cdot
\end{tikzcd}
\end{document}
```

the outer rectangle and inner right-hand square are pullbacks, then the left-hand square is a pulllback. 

$\textcolor{yellow}{Note:}$ Remember that the prism diagram is actually a diagram of shape $\Delta[1] \times \Delta[2]$ with the background horizontals corresponding to composition are suppressed:
```tikz
\usepackage{tikz-cd}
\begin{document}
\begin{tikzcd}
	\cdot \arrow[rr] \arrow[d] \arrow[dr] & & \cdot \arrow[dl] \arrow[d] \\
	\cdot \arrow[rr, dotted] \arrow[dr] & \cdot \arrow[d] & \cdot \arrow[dl] \\
	& \cdot &
\end{tikzcd}
\end{document}
```
We can do this suppression since the axioms of our quasi-category model ensures that there is always a filler for composites.