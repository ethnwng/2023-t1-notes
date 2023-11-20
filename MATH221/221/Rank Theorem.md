*If a matrix $A$ with n columns, then*
$$rank(A)+nullity(A)=n$$
The [[Rank]] is the number of columns with pivots, the [[nullity]] is the number of columns without pivots, therefore the *total* number of columns can be found by adding both the rank of a matrix and its nullity.

##### Importance
The rank of a matrix $A$ represents important information about the solutions to the matrix equation $A\mathbf{x} = \mathbf{b}$. Such equation is *consistent* if and only if $\mathbf{b}$ is in the span of the column space of $A$. 

Therefore, $\operatorname{rank}(A)$ is the dimension of the set of $b$ with the property that $Ax=b$ is consistent. 

We also know that $\operatorname{rank}(A)$ is the number of **pivot** columns and the $\operatorname{nullity}(A)$ is the number of free variables, so to summarize:
$$\begin{align*} \operatorname{rank}(A)=\operatorname{dimCol}(A)=\# \ of\ columns\ with\ pivots \\ \operatorname{nullity}(A)=\operatorname{dimNul}(A)=\# \ of \ free \ variables \\ = \# of \ columns\ without\ pivots\end{align*}$$

##### Other
This stuff links back to solutions of $Ax=b$ equations. The matrix equation $Ax=b$ is pretty much saying, *what vector $\mathbf{x}$ when multiplied by $A$ produces $\mathbf{b}$*? And, there exists a solution to (some value of $x$ exists) $Ax=b$ if $\mathbf{b}$ is in the span of the column space of $A$.  

Should be used when asked 