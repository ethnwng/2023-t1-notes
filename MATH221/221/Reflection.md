##### Premise
Matrix Algebra is mainly the study of **[[Linear Equation|linear equations]]**, a linear equation is just any equation where all the variables are to the first power.
$$c_1x+c_2y=2$$ 
One of the applications of **matrix algebra** is using it to solve **[[Linear System|systems of linear equations]]**. We can represent any system as a matrix and its unknowns and output as column vectors.

Really its the study of equations that draw straight lines.

##### Vectors
A vector in either $\mathbb{R}^2$ or $\mathbb{R}^3$ can be geometrically understood as the $(x,y)/(x,y,z)$ coordinates of some **point**. Its easier to think of vectors as **points**.

Connecting *vectors* to *linear equations*, lets first start with the linear equation $$4x+3y=6$$The graph of this equation looks like![[Pasted image 20231203185704.png]]
All linear systems create **straight** lines, if we represent the equation as a [[Vector Equations|vector]],$$\begin{pmatrix}4 & 3 \end{pmatrix}\begin{pmatrix}x\\y\end{pmatrix} = 6$$
OR$$\begin{pmatrix}4\\3\end{pmatrix}\begin{pmatrix}x & y \end{pmatrix}=6$$
Given, a system of equations we can represent the entire thing as an **matrix equation**  $$\begin{align*} 4x+y=3 \\ 2x+3y =2\end{align*}$$
Represented as a matrix we get $$\begin{bmatrix}4&1 \\ 2&3\end{bmatrix}\begin{bmatrix}x\\y\end{bmatrix}=\begin{bmatrix}3\\2\end{bmatrix}$$
***[[Solution Set|The solution to this system of equations is a vector, and if we imagined extending that vector infinitely all vectors that lie on that line are solutions to the system.]]***

Consider two vectors $u_1$ and $u_2$. If we extend $u_1$ infinitely, which would create a  straight line, does $u_2$ lie on that line?

If it does the vectors $u_1$ and $u_{2}$ are linearly dependent meaning that one vector must be a **scalar** multiple of the other.

This is important when we consider [[Linear Combination|combinations]] of vectors.

##### Side
When adding vectors we use the **tip to tail** method![[Pasted image 20231203194654.png]]

So consider, the combination of two vectors $u_1$ and $u_2$ and any multiple of them. $$c_{1}\mathbf{u_{1}}+c_{2}\mathbf{u_{2}}=\mathbf{v}$$
We call the **[[Span|span]]** of a set of vectors **all the possible vectors that can be created by the combination of $\mathbf{u_1}$ and $\mathbf{u_2}$ for any $c_1$ and $c_2$**. 

What this means is that when someone says $\mathbf{v}$ is in the $Span$ of $\mathbf{v_1}$ and $\mathbf{v_2}$, it means we can write $\mathbf{v}$ as some combination of the two vectors.

Another thing to realize is that the solution $\mathbf{x}$ to matrix equation $A\mathbf{x}=\mathbf{v}$ is some linear combination of the **columns of A**. So we could say that the $Span$ (all the possible combinations of the vectors) is the column space of some matrix $A$.

If we consider two vectors $\mathbf{u_{1}},\mathbf{u_2}$ and they are [[Linear Independence|linearly independent]] they are able to make any vector in $\mathbb{R}^n$. 


##### Transformations
A transformation in linear algebra is the same as in other math. Some input vector is transformed by some operation to get a different new vector. In this case, **the operation done is normally multiplying the input vector by some matrix A**. 

A [[Standard Matrix of a Lin. Transformation|matrix transformation]] just means if we considered $f(\mathbf{x})=A\mathbf{x}$, where the set of all possible output vectors is just all the vectors $\mathbf{b}$ such that $A\mathbf{x}=\mathbf{b}$ has a solution.


