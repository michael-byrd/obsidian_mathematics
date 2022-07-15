**Contraction** - Let $G = (V,E)$ be a graph with $e \in E.$ Then $G/e$ read (read '$G$ contract $e$') is the graph obtained from $G$ by identifying the ends to form a new vertex $v_e,$ and then removing any loops or multiple edges. 

Let $e = xy$ be an edge of $G = (V,E).$ Then $G/e = (V', E')$ where $$V' = \left( V \setminus \{ x, y \} \right) \cup \{v_e\}$$ and $$E' = \{ vw \in E : \{v,w\} \cap \{x,y\} = \emptyset\} \bigcup \{v_ew : xw \in E \setminus \{e\} \text{ or } yw \in E \setminus \{e\}\}.$$

We can [[contraction_def|contract]] an entire connected subgraph $U,$ written $G/U.$ 