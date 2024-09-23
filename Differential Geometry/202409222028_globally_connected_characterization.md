---
aliases:
  - preserves the terminal object
---

>[!proposition]
>A [[202409221948_locally_connected|locally connected]] $\infty$-topos $\langle \mathcal{H}, (\Pi \dashv Disc \dashv \Gamma)\rangle$ is [[202409221948_locally_connected|globally connected]] iff the extra left adjoint $\Pi$ preserves the terminal object.
>`\begin{proof}`
>	First recall:
>	1.  $Disc$ is fully faithful iff the unit of the adjunction $(\Pi \dashv Disc)$ is an equivalence: $$\Pi \ Disc (S) \ \simeq S;$$
>	2. every groupoid $S \in Grpd$ is a colimit of the constant functor on the terminal object indexed by itself: $$S \simeq \varinjlim_{S}*;$$
>	3.  (LAPC) *left adjoints preserve colimits*. Since both $Disc$ and $\Pi$ are left adjoints they preserve colimits, notably including terminal objects.
>	
> Now assume that $Disc$ is fully faithful. Then $$ 
> \begin{aligned}
> \Pi (*_{\mathcal{H}}) &\simeq \Pi \ Disc \ (*_{{Grpd}}) \\ &\simeq *_{{Grpd}}
\end{aligned}
$$ hence  $\Pi$ preserves terminal objects.
> Conversely,  assume that $\Pi$ preserves terminal objects, then
>$$
>\begin{aligned}
>	\Pi \ Disc \ (S) &\simeq \Pi \ Disc \ (\varinjlim_{S} \ *_{Grpd}) \\ &\simeq \varinjlim_{S} \ (\Pi \ Disc \ *_{Grpd}) \\ &\simeq \varinjlim_{S} \ \Pi \ *_{{\mathcal{H}}} \\ &\simeq \varinjlim_{S} \ *_{{Grpd}} \\ &\simeq S.
>	
>\end{aligned}	
>$$
>We have shown that the unit of the adjunction is an equivalence it follows that  $Disc$ is fully faithful.
>	
>`\end{proof}`





