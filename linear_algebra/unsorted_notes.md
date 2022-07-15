# 2022-07-11 Notes

## $k \text{-linear form}$
$k$-linear form - A $k$-linear form is a function $f : X \times \cdots X \rightarrow K$ that is linear in each coordinate. That is, if we fix $k-1$ inputs, the function is linear in the remaining input.

Proposition: Let $\dim(X) = n.$ The set of $k$-linear forms is a vector space of dimension $n^k.$ 

## Symmetric, Skew-symmetric, and alternating
Let $f: X \times \cdots \times X \rightarrow K$ be a $k$-linear form. For any permutation $\pi \in S_k$ define the following $k$-linear form $$(\pi f)(x_1, \ldots, x_k) = f\left( x_{\pi_1}, \ldots, x_{\pi_k} \right).$$
A $k$-linear form is *symmetric* if $\pi f = f$ for all $\pi \in S_k.$

A $k$-linear form is *skew-symmetric* if $\tau f = f$ for all transpositions $\tau \in S_k.$

A $k$-linear form is *alternating* if $f(x_1, \ldots, x_k) = 0$ whenever $x_i=x_j$ for some $i\neq j.$

Proposition: Every alternating form is skew-symmetric.

Proposition: If $K$ is not characteristic $2,$ then ever skew-symmetric form is alternating.

Proposition: If $f$ is alternating and $y_1, \ldots, y_k$ are linearly dependent then $f(y_1, \ldots, y_k) = 0.$

Proposition: If $f$ is a non-zero alternating $n$-linear form and $v_1, \ldots, v_n$ is a basis, then $f(v_1, \ldots, v_n) \neq 0.$ 

Corollary: Any two alternating $n$-linear forms are linearly dependent. 

## Determinants
Let $T: X \rightarrow X$ be linear. For an alternating $n$-linear form $f,$ define a new alternating $n$-linear form $$\tilde{T}f:X^n \rightarrow K, \quad (x_1, \ldots, x_n) \mapsto f(Tx_1, \ldots, Tx_n).$$
That is, $T$ induces a map $\tilde{T}$ on the space of alternating $n$-linear forms, $$\tilde{T}: f \mapsto \tilde{T}f.$$
Since this is a $1$ dimensional vectorspace, we have $$\tilde{T}:f \mapsto \lambda f.$$ The scalar $\lambda$ is called the determinant of $T.$

### Univeral Property of Determinats
Given a linear map $T: X \rightarrow X,$ there exists a unique scalar $\lambda$ such that for all alternating $n$-linear forms $f,$ $$f(Tx_1, \ldots, Tx_n) = \lambda f(x_1, \ldots, x_n).$$
![[Pasted image 20220711200636.png]]
#### Basic properties of Determinants
* If $Tx = cx,$ then $\det(T) = c^n.$ 
* $\det(0) = 0$ 
* $\det(I) = 1$
* $\det(AB) = \det(A)\det(B)$
* If $A$ is invertible, then $\det(A^{-1})=\det(A)^{-1}$

## Eigenvectors and Eigenvalues
**Eigenvalue/vector** - If $Av = \lambda v$ for some nonzero vector $v$ and scalar $\lambda \in K,$ then we say $v$ is an eigenvector and $\lambda$ is the corresponding eigenvalue.

Proposition: Every linear map has an eigenvector.

Remark: $A-\lambda I$ is noninvertible if and only if $\det(A-\lambda I)=0.$ That is, $\lambda$ is an eigenvalue of $A$ if and only if $\det(A-\lambda I)=0.$

Proposition: Eigenvectors of distinct eigenvalues are linearly independent.

Proposition: If $X$ has a basis of eigenvectors of $A,$ then $A$ is similar to a diagonal matrix. In this case, we say $A$ is diagonalizable.

**Characteristic polynomial** - The *characteristic polynomial* of $A$ is $p_A(t) = \det(tI - A).$ This polynomial has degree $n$ and its roots are the eigenvalues of $A.$

Proposition: If $A$ has eigenvalues $\lambda_1, \ldots, \lambda_n,$ then 
* $\operatorname{tr}(A) = \sum\limits_{i=1}^{n}{\lambda_i}$ 
* $\det(A)=\prod\limits_{i=1}^{n}{\lambda_i}$

Remark: if $Av = \lambda v,$ then $A^kv = \lambda^k v.$ 

### Spectral Mapping Theorem
If $\lambda$ is an eigenvalue of $A,$ then for all polynomials $q(t)$ we have 
* $q(\lambda)$ is an eigenvalue for $q(A)$
* every eigenvalue of $q(A)$ is of this form

Corollary: Every eigenvalue of $p_A(A)$ is zero.

### Cayley Hamilton Theorem
Every matrix satisfies its characteristic polynomial. That is, $p_A(A) = 0.$