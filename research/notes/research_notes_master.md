* Predicate $C_0(I)$ :   $0\notin \square f\left(I\right)$
* Predicate $C_1(I) :  0 \notin \left(\square \frac{\partial f}{\partial X} f\left(I\right)\right)^2 + \left(\square \frac{\partial f}{\partial Y} f\left(I\right)\right)^2$
* Predicate $C_1'(I) : 0 \notin \square \nabla f\left(I\right) \times \square \nabla g(I)$

**Lemma** -  If $C_1'\left(I\right)$ is true, then $\left|\mathcal{V}\left(f, g\right) \cap I\right| \leq 1.$
*Proof:*  Suppose that the curves $f$ and $g$ intersect at least twice in $I.$ Let $l(t) = p + t \vv$ be the line passing through two points of intersection. We shall choose $p = \left(p_x, p_y\right)$ and $\vv = \left(v_x, v_y\right)$ such that $l(0)$ and $l(1)$ are the two points of intersection from above. It follows that $f\left(l\left(0\right)\right) = 0$  and $f\left(l\left(1\right)\right) = 0.$ Then, by Rolle's Theorem, we have that there exists some $c \in \left(0, 1\right)$  such that $\left(f \circ l\right)'(c) = 0.$  Since $$f\left(l\left(t\right)\right) = f\left( p_x + v_xt, p_y+v_yt \right),$$ we have
	$$\begin{align}
		\left(f \circ l\right)'(t) &= \partial_x f\left(l\left(t\right)\right)l_x'(t) + \partial_y f\left(l\left(t\right)\right)l_y'(t) \\
		&= \partial_x f\left(l\left(t\right)\right)v_x + \partial_y f\left(l\left(t\right)\right)v_y \\
		&= \del f\left(l(t)\right) \cdot \vv.
	\end{align}$$
	Therefore, there exists a $c \in \left(0, 1\right)$ such that $\del f\left(l(c)\right)$ is orthogonal to $\vv,$ hence orthogonal to the line $l(t).$ Since $I$ is convex, we have that this point is contained in $I.$ By a similar arguement, there exists a $d \in \left(0, 1\right)$ such that $\del g\left(l(d)\right)$ is orthogonal to $l(t).$
		
Finally, we have that there exists gradient vectors for $f$ and $g$ in $I$ that are parallel, that is, $0 \in \square \del f (I) \times \square \del g (I).$ 