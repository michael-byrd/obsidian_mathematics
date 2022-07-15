**Theorem 1.3** - Let $V$ be a vector space and $W$ a subset of $V.$ Then $W$ is a [[subspaceDef|subspace]] of $V$ if and only if the following three conditions hold for the operations defined in $V:$
* $0 \in W.$
* $x + y \in W$ whenever $x,y\in W.$
* $cx \in W$ whenever $c \in F$ and $x \in W.$

**Theorem 1.4** - Any intersection of [[subspaceDef|subspaces]] of a vector space $V$ is a subspace of $V.$

**Theorem 1.5** - The [[spanDef|span]] of any subset $S$ of a vector space $V$ is a [[subspaceDef|subspace]] of $V.$ Moreover, any subspace of $V$ that contains $S$ must also contain the span of $S$

**Theorem 1.6** - Let $V$ be a vector space, and let $S_1 \subseteq S_2 \subseteq V.$ If $S_1$ is [[linearlyIndependentDef|linearly dependent]], then $S_2$ is linearly dependent.

**Corollary** - Let $V$ be a vector space, and let $S_1 \subseteq S_2 \subseteq V.$ If $S_2$ is [[linearlyIndependentDef|linearly independent]], then $S_1$ is linearly independent.

**Theorem 1.7** - Let $S$ be a [[linearlyIndependentDef|linearly independent]] subset of a vector space $V,$ and let $v \in V\setminus S.$ Then $S \cup \{v\}$ is linearly dependent if and only if $v \in \operatorname{span}(S).$ 

**Theorem 1.8** - Let $V$ be a vector space and $\beta = \{ u_1, \ldots, u_n \}$ be a subset of $V.$ Then $\beta$ is a [[basisDef|basis]] for $V$ if and only if each $v \in V$ can be uniquely expressed as a [[linearCombinationDef|linear combination]] of vectors in $\beta.$ That is $$v = a_1u_1 + a_2u_2 + \cdots a_nu_n$$ for unique scalars $a_1, \ldots, a_n.$

 **Theorem 1.9** - If a vector space $V$ is [[spanningSetDef|spanned]] by a finite set $S,$ then some subset of $S$ is a [[basisDef|basis]] for $V,$ hence $V$ has a finite basis.

**Theorem 1.10** - Let $V$ be a vector space that is [[spanningSetDef|spanned]] by a set $G$ containing exactly $n$ vectors, and let $L$ be a [[linearlyIndependentDef|linearly independent]] subset of $V$ containing exactly $m$ vectors. Then $m\leq n$ and there exists a subset $H$ of $G$ containing exactly $n-m$ vectors such that $L \cup H$ [[spanDef|spans]] $V.$

**Corollary** - Let $V$ be a vector space having a finite [[basisDef|basis]]. Then every basis for $V$ contains the same number of vectors.

**Corollary** - Let $V$ be a vector space with dimension $n.$
* Any finite [[spanningSetDef|spanning set]] for $V$ contains at least $n$ vectors, and a spanning set for $V$ that contains exactly $n$ vectors is a [[basisDef|basis]] for $V.$
* Any [[linearlyIndependentDef|linearly independent]] subset of $V$ that contains exactly $n$ vectors is a basis for $V.$
* Every linearly independent subset of $V$ can be extended to a basis for $V.$

**Theorem 1.11** - Let $W$ be a subspace of a [[finiteDimensionalDef|finite-dimensional]] vector space $V.$ Then $W$ is finite-dimensional and $\dim(W) \leq \dim(V).$ Moreover, if $\dim(W) = \dim(V),$ then $V = W.$

**Corollary** - If $W$ is a subspace of a [[finiteDimensionalDef|finite-dimensional]] vector space $V,$ then any [[basisDef|basis]] for $W$ can be extended to a basis for $V.$