###### one-to-one
*Def.* A transformation $T$ $\mathbb{R}^{n}\longrightarrow \mathbb{R}^m$ is **one-to-one** if for every $\vec{b} \in \mathbb{R}^m$ such that $T(\vec{x})=\vec{b}$


*proposition*
Let $T$ $\mathbb{R}^{n}\longrightarrow \mathbb{R}^m$ be a linear transformation with a standard matrix $A$. $T$ is one-to-one
$\iff$ $\forall \ \vec{b} \in \mathbb{R}^m$ There is at most one solution to $T(\vec{x})=\vec{b}$
$\iff A\vec{x}=\vec{b}$ has at most one solution $\forall \ b\in \mathbb{R}^m$ 
$\iff A$ has a pivot in every column
$\iff$ $A\vec{x}=0$ has just the trivial solution
$\iff$ Range $(T)$ has dimension $n$


##### onto 
*Def.* A transformation $T \ \ \ \mathbb{R}^{n} \longrightarrow \mathbb{R}^m$ is **onto** if for every $\vec{b}$ in $\mathbb{R}^m$, $T(\vec{x}) =\vec{b}$
has **at least one** solution

*proposition* Let $T$ be a linear transformation with standard matrix $T$ is **onto**
$\iff$ $\forall \ \vec{b},$ $T(\vec{x})=\vec{b}$ has at least one solution
$\iff$ A has a pivot in every row
$\iff$ The range of $T$ has dimension $m$
$\iff$ $A\vec{x}=\vec{b}$ is consistent for every $\vec{b}$
$\iff$ The Columns of $A$ span $\mathbb{R}^m$
