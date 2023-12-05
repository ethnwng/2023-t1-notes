*Theorem:* If $W=Span\{\mathbf{x}_W\}$, the basis of the subspace $W$, if we compute the [[Orthogonal Vectors#Orthogonal Complement|complement]] $W^\perp$ and its basis $W^\perp=Span\{x_{W^\perp}\}$. The combination of the two subspaces $W \cup W^\perp$ creates the basis for $\mathbb{R}^n$. 

Using this we can represent any vector $\mathbf{x}$ as a combination of the basis vectors for $W$ and the basis vector for $W^\perp$
$$\mathbf{x}=\mathbf{x}_W+\mathbf{x}_{W^\perp}$$

Where $$\mathbf{x_{w}}= \frac{u\cdot x}{u\cdot u}u$$
$$\mathbf{x_{W^\perp}}=\mathbf{x}-\mathbf{x_W}$$
We call $\mathbf{x}_{W^\perp}$ the the vector which is orthogonal to the set $W$, with its tail position on $\mathbf{x}_W$ and its tip on $\mathbf{x}$. 

If we represent $\mathbf{x}$ as a point in space, then $\mathbf{x_w}$ is projection of $\mathbf{x}$ on the subspace $W$. 