*Def* The **determinant** is a function
$$det.\{square\ matrix\}\rightarrow \mathbb{R}$$
Produces a real number

The function satisfies the following properties
1. Performing **row-replacement** on a square matrix $A$ *does not change* the determinant
2. **Scaling** a row *multiplies* the determinant by that scalar
3. **Swapping** rows multiplies the determinant by $-1$ 
4. $det(I_n)=1$ 


###### Computing Determinants
Given,$$A = \begin{bmatrix}2 & 0\\0 & 3\end{bmatrix}$$
Row reduce to get to the Identity Matrix
$$\begin{align*}\begin{bmatrix}2 & 0\\0 & 3\end{bmatrix}= \begin{bmatrix}1 & 0\\0 & 3\end{bmatrix}=\begin{bmatrix}1 & 0 \\ 0 & 1\end{bmatrix}\end{align*}$$

- We know $det(I_{n}) = 1$ 
- We scaled the second part of the reduction by $1/3$ therefore, we multiply the determinant by $3$
- similarly we scaled our first step by $1/2$, so we multiply by $2$ to get $det(A) = 6$


###### Closed along Multiplication
Given two matrices $A,B$ $$det(A)\cdot det(B) = det(AB)$$

###### Computing Determinants
To compute a determinant we use [[cofactor expansion]] 


**determinants can prove if a set of vectors are linearly in/dependent, a set of vectors is dependent when $det=0$ and independent when the $det\neq 0$
