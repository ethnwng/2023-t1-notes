*Def* A transformation $T : \mathbb{R}^{n}\rightarrow\mathbb{R}^n$ is **invertible** if $\exists\ \mu:\mathbb{R}^n\rightarrow\mathbb{R}^n$ such that $T\circ \mu = \mu \circ T=Id_n$ 

*Theorem:* $T$ is invertible if and only if it is *one-to-one* and *onto*


##### Proof there exists only one inverse of an [[Invertible Matrices]] A
Suppose $A$ is invertible and suppose $B$ and $C$ are inverses of A
$$I_{n}=AB=AC$$
$$\begin{align*}BI_{n}=BAB=BAC\\ B=I_{n}B=I_{n}C\\ B=B=C\end{align*}$$
Therefore $B=C$ and there exists only one inverse of an invertible matrix


##### Invertible Matrix Theorem
Let A be an $n\times n$ matrix, $T:\mathbb{R}^{n}\rightarrow\mathbb{R}^n$ given by $T(\mathbf{x}) = A\mathbf{x}$. Then the following are equivalent
1. A is invertible
2. A has *n* pivots
3. Nul(A) ={$\vec{0}$} 
4. The columns of $A$ are [[Linear Independence]]
5. The columns of A span $\mathbb{R}^n$
6. $A\mathbf{x}=\vec{b}$ has a unique solution $\forall\ b \in  \mathbb{R}^n$
7. T is one-to-one
8. T is onto
9. T is invertible


