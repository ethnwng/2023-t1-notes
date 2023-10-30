*Def* An $n\times n$ matrix $A$ is **invertible** if there exists a matrix B such that $AB=BA=Id_n$

Where we call $B$ the inverse of $A$ 
$B=A^{-1}$

##### To check when a matrix is the inverse of the other
- AB should equal the identity
- BA should also equal the identity
- pivots in every column and row


To check if a matrix $A$ is invertible
*Theorem:* Let $A$ be an $n\times n$ matrix, $A$ is **invertible** if and only if
$$RREF(A|In)=(In|B)$$
- Put identity matrix on the augmented side of the matrix
- After reducing the entire matrix to RREF, the right side of the augmented matrix will be the inverse of $A$

