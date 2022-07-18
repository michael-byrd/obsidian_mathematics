---
cssclass: clean-embeds
---
# Definition
![[ring_homomorphism_def]]
## Properties
![[ring_homomorphism_kernel_def]]
**Proposition**: Let $R$ and $S$ be rings and $\phi: R \rightarrow S$ be a ring homomorphism. 
* $\operatorname{im}(\phi)$ is a [[subring_def|subring]] of $S.$
* $\ker{(\phi)}$ is a [[subring_def|subring]] of $R.$ Moreover, if $\alpha \in \ker(\phi)$ and $r \in R,$ then $r\alpha \in \ker(\phi).$
**Proposition**: Let $I$ be an ideal of $R.$ Then the map $R \rightarrow R/I$ given by $r \mapsto r+I$ is a sirjective ring homomorphism with kernel $I.$

## Ring Isomorphism Theorems
**First Ring Isomorphism Theorem**: Let $R$ and $S$ be rings and $\phi:R\rightarrow S$ be a ring homomorphism. Then the [[ring_homomorphism_kernel_def|kernel]] of $\phi$ is an [[ideal_def|ideal]] of $R$ and the image of $\phi$ is isomorphic to the [[quotient_ring_def|quotient ring]] $R/\ker(\phi).$

**Second Ring Isomorphism Theorem**: Let $A$ be a subring of $R$ and $B$ and ideal of $R.$ Then $A+B = \{ a + b: a\in A, b\in B \}$ is a subring of $R,$ $A \cap B$ is an ideal of $A,$ and $(A+B)/B\cong A/(A \cap B).$

**Third Ring Isomorphism Theorem**: Let $R$ be a ring and $I \subseteq J$ ideals of $R.$ Then $J/I$ is an ideal of $R/I$ and $(R/I)/(J/I) \cong R/J.$ 

**Theorem**: Let $I$ be an ideal of a ring $R.$ Consider the quotient map $R \rightarrow R/I.$ There is a bijection between subrings of $R/I$ and subrings of $R$ containing $I.$ A subring is an ideal of $R/I$ if and only if the preimage is an ideal of $R.$ 

### Other Propositions
**Corollary (to a prop in ideal topic):** Let $F$ be a field, then any nonzero ring homomorphism from $F$ to another ring is injective. 