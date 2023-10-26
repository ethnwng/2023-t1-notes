The solution set of a system of equations are the vectors $v_{1},v_{2},\dots ,v_{k}$ of the [[Parametric Vector Form]] of the matrix equation. Whether that be homogeneous ($Ax=0$) or non homogenous $b \neq 0$. 

To find the solution set of a system, convert the matrix equation to its [[Parametric Vector Form]]. The solution set is then the vectors of the linear combination created.

#### Example
*Find the solution set of $Ax=b$, where*
$A = \begin{pmatrix} 1  & -3 \\ 2  & -6 \end{pmatrix}$  and $b = \begin{pmatrix} -3 \\ -6 \end{pmatrix}$

##### Solution
Row reduce A to get $$A=\begin{pmatrix}1 & -3 & \bigm |  & -3 \\ 0 & 0 & \bigm | & 0 \end{pmatrix}$$
We get the single equation $x_{1}-3x_{2}=-3$. We can write the parametric form as $$x=\begin{pmatrix}x_1\\x_2\end{pmatrix}=x_2\begin{pmatrix}3\\1\end{pmatrix}+\begin{pmatrix}-3 \\ 0 \end{pmatrix}$$
Our solution set is then the two vectors meaning$$Span\{\begin{pmatrix}3\\1\end{pmatrix}\}+\begin{pmatrix}-3\\0\end{pmatrix}$$
