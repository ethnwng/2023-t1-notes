*Def* The *dot product* of two vectors $\mathbf{x}$, $\mathbf{y}$ in $\mathbb{R^n}$ is$$\mathbf{x}\cdot\mathbf{y}=x_{1}y_{1}+x_{2}y_{2}+\dots+x_{n}y_{n}=\mathbf{x}^{T}\mathbf{y}$$ 

###### Properties
1. Commutative product

$$c\mathbf{x}\cdot\mathbf{y}=c(\mathbf{x}\cdot\mathbf{y})$$
2. Distributes over scalar multiplication
$$(\mathbf{x}+\mathbf{y})\cdot\mathbf{z}=\mathbf{x}\mathbf{z}+\mathbf{y}\mathbf{z}$$

###### Special Case
The dot product with itself is the sum of squares of the components of the vector
$$\begin{pmatrix}x_{1}\\ x_{2}\\ \vdots \\ x_{n}\end{pmatrix}\begin{pmatrix}x_{1}\\ x_{2}\\ \vdots \\ x_{n}\end{pmatrix}=x_{1}^{2}+x_{2}^{2}+\dots +x_{n}^{2}$$
Where $\mathbf{x}\cdot \mathbf{x}=\vec{0}$ if and only if $\mathbf{x}=0$

- With the special case, we can find the length of any vector since the dot product of a vector with itself is always some positive number, or zero.

We define the **norm** of some vector $\mathbf{x}$ as $$||\mathbf{x}||=\sqrt{\vec{x}\cdot\vec{x}}$$
The **norm** of a vector computes the **length** of the the vector


If $\mathbf{y}=c\mathbf{x}$ for a scalar $c$, then $$||\vec{y}|| = |c| \ ||\vec{x}||$$

The length of some vector divided by its norm is **1**.
$$\frac{x}{||x||}=1$$
A vector with *length* $1$ is called a **unit vector**

