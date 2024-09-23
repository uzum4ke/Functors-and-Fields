---
aliases:
  - cohesive, cohesion, cohesive structure
---

>[!definition]
>A **cohesive structure** on an $\infty$-topos $\mathcal{H}$ is the datum of a quadruple of adjoint $\infty$-functors $$(\Pi \dashv Disc \dashv \Gamma \dashv coDisc)$$ with respect to the category of $\infty$-groupoids $Grpd$ that satisfied the following:
>1. the $\infty$-functor $\Gamma$ is the global section fuctor;
>2. the $\infty$-functors $Disc$ and $coDisc$ are fully faithful;
>3. the $\infty$-functor $\Pi$ preserves finite products.
>
>That is, a **cohesive** $\infty$-topos is a [[202409221942_locally_local|local]] [[202409221948_locally_connected|connected]] $\infty$-topos such that $\Pi$ preserves all finite products (not just terminal objects). 

```tikz
\usepackage{tikz-cd}
\begin{document}
\begin{tikzcd}
	\mathcal{H} \arrow[rr, yshift=-1ex, "\Gamma"] \arrow[rr, yshift=3ex, "\Pi"] & & Grpd \arrow[ll, yshift=1ex, hook, swap, "Disc"] \arrow[ll, yshift=-3ex, hook, swap, "coDisc"].
\end{tikzcd}
\end{document}
```




$\textcolor{yellow}{Note:}$ The intuitive idea is that $\mathcal{H}$ represents a general notion of abstract topological space. $\Gamma$ represents the forgetful functor that takes a space and returns its underlying groupoid. $\Pi$ is the *fundamental groupoid functor* or  *geometric path groupoid functor*. The functors $Disc$ and $coDisc$ are supposed to represent discrete and codiscrete topologization.