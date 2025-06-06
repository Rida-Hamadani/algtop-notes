#theorem
### Types
- `X` `Y` : [[Topological Space]]
- $f : X \to Y$
### Statement
If $f$ is [[Continuity|continuous]], and $X$ is [[Compact Space|compact]], then $f\left( X \right)$ is [[Compact Space|compact]].
### Proof
Let $\left\{ U_{i} \right\}_{i\in I}$ be a [[Covering]] of $f(X)$, then $X = f^{-1}\left(\bigcup\limits_{{i\in I}} U_{i} \right) = \bigcup\limits_{i \in I} f^{-1}\left( U_{i} \right)$, which means that $\left\{f^{-1}\left(U_{i}  \right)\right\}_{i\in I}$ is a [[Covering]] of $X$, as $f$ is continuous making the elements of the [[Covering]] [[Open Set|open]]. 
Since $X$ is a [[Compact Space|compact]], there exists a finite subcover of $\left\{ f\left( U_{i}\right) \right\}_{i\in I}$ that covers $X$,  so we have $\bigcup\limits_{{i\in\mathbb{N}}}f^{-1}\left(V_{i}\right) = X$, and thus $\left\{ V_{i} \right\}_{i\in\mathbb{N}}$ is a finite cover of $f(X)$.