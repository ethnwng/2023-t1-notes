*Trying to prove that all [[linear transformations]] are Matrix Transformations*
Given the standard basis vector $\vec{e_{i}}\in \mathbb{R}^n$ $$\vec{e_{i}}= \begin{pmatrix}0\\0\\1\\\vdots \\ 0 \end{pmatrix}$$ Where the $1$ shows up in the $i_{th}$ position and the rest of the entries are zero.

Let $T$ be a linear transformation $\mathbb{R}^{n}\longrightarrow \mathbb{R}^m$. 

Take the transformation of the standard basis $\vec{e_i}$

$$T(\vec{e_{i}}) = \begin{bmatrix}v_1\\v_{2}\\v_{3}\\ \vdots \\ v_n\end{bmatrix} = \vec{v_i}$$

Let $A = \begin{pmatrix} v_{1} & v_{2} & \dots & v_{n} \\ \vdots & \vdots & \vdots & \vdots \end{pmatrix}$ where the columns of $A$ are the transformations of the standard basis. 

This is the **standard matrix** for $T$.

*Theorem* $T(\vec{x})=A\vec{x}$
