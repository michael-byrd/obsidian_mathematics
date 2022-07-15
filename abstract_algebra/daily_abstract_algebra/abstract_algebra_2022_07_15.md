**Ring** - A *ring* is a set $R$ with two binary operations called $+$ *addition* and $\times$ *multiplication* such that 
1. $(R, +)$ is an abelian group.
2. $\times$ is associative, that is, $(a \times b) \times c = a \times (b \times c), \forall a,b,c \in R.$
3. Multiplcation distributes over addition, that is, $(a+b) \times c = a \times c + b \times c$ and $a \times(b + c ) = a \times b + a \times c, \forall a,b,c \in R.$ 

* If multiplication is commutative, we say that $R$ is a *commutative ring.*
* If there exists a $1 \in R$ such that $1 \times a = a \times 1 = a, \forall a \in R,$ then $R$ is a *ring with identity.*
* Let $R$ be a nontrivial ring with identity. If every $a \in R\setminus \{0\}$ has a multiplicative inverse, then $R$ is a *division ring.*
* A commutative division ring is a *field.*

Let $R$ be a ring.
1. An element $a \in R$ is a zero divisor if $a \neq 0$ and there exists a $b \in R$ such that $ab = 0$ or $ba = 0.$
2. Let $R$ be a nontrivial ring with identity. An element $u \in R$ is a *unit* in $R$ if there exists some $v \in R$ such that $uv = vu = 1.$ The set of units in $R$ is $R^\times.$ $R^\times$ forms a group under multiplication.

**Proposition**: Let $R$  be a ring.
1. For all $a \in R, 0a = a0 = 0.$
2. For all $a,b \in R, (-a)b = a(-b) = -(ab).$
3. For all $a,b \in R, (-a)(-b) = ab.$
4. Let $1 \in R,$ then $1$ is unique.
5. Let $1 \in R, $ then $-a = (-1)a.$ 

**Integral Domains** - A nontrivial commutative ring with no zero divisors is an *integral domain.*

**Proposition**: Integral domains have cancellation laws. That is, if $a,b,c \in R$ with $a \neq 0,$ then $ab = ac$ if and only if $b=c.$

**Corollary**: Any finite integral domain is a field.

