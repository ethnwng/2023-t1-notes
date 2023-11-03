Let $A$ be an $n\times n$ matrix,
*Def* The ($i,j$) *minor* $A_{ij}$ of $A$ is the $(n-1)\times (n-1)$ matrix obtained from $A$ by deleting the $i^{th}$ row and the $j^{th}$ column. 

- ($i_j$) *cofactor* $c_{ij}$ of $A$ $$C_{ij}=(-1)^{i+j}\cdot det(A)$$
The cofactor expansion along the $i^{th}$ row of $A$ $$\sum\limits_{j=1}^{n}a_{ij}C_{ij}=det(A)$$
Cofactor expansion along the $j^{th}$ column of $A$ $$\sum\limits_{i=1}^na_{ij}C_{ij}=det(A)$$
Do the dot product of a matrix


###### Example
*Compute det(A) along the first row*

$A=\begin{bmatrix} a & b \\ c & d \end{bmatrix}$

cofactor along the first row $$det(A)=\begin{bmatrix}a & b \\c & d \end{bmatrix}=a(-1)^{1+1}det([d])+b(-1)^{1+2}det([c])$$
$$det(A) =ad-bc$$
