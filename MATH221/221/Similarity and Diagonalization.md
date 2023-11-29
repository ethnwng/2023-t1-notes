*Def* Two $n\times n$ matrices A and B are **similar** if there exists an invertible $n \times n$ matrix $C$ such that $$A=CBC^{-1}$$
###### Example
Suppose $A$ is *similar* to $In$. Then there exists $C$ such that $$\begin{align*} A=CInC^{-1}\\ A=CC^{-1} \\ A=In \end{align*}$$


*Def* A matrix $A$ is diagonalisable if it is similar to a diagonal matrix $D$. There exists an invertible matrix $C$ such that $A = CDC^{-1}$.
- Any diagonal matrix is diagonalisable


###### Example
A diagonal matrix $D$ is diagonalisable
$$D=InDIn^{-1}$$
Calculations become simpler if $A = CDC^{-1}$. Then taking powers of $A$ becomes easier since the power of diagonal matrices is easy to compute and we can write them as. $$A^{2}=CD^{2}C^{-1}$$
Or more generally $$A^{n}=CD^{n}C^{-1}$$

**$D$ and $A$ have the same [[Eigenvalue]]s, and the columns of $C$ are the corresponding eigenvectors.**

