Spring 19 SE201 (Hyosang Kang)
**Due 3/15 23:59**

# Homework Assignment #1

## Problem 1.

### 1-1.

Find a third equation that can't be solved if $x + y + z = 0$ and $x - 2y - z = 1$. Explain how three planes are aligned in the $3$-dimensional space.

### 1-2.

Apply elimination to the system

$$u + v + w = -2$$
$$3u + 3v - w = 6$$
$$u - v + w = -1$$

## Problem 2.

### 2-1.

Prove that the product of two lower triangular matrices is lower triangular.

### 2-2.

Let $A = \begin{bmatrix} 1 & 1 & 0 \\ 4 & 6 & 0 \\ -2 & 2 & 0 \end{bmatrix}$. Find constants $a,b,c$ such that

$$E_{32}(a)E_{31}(b)E_{21}(c)A = U$$

where $U$ is a lower triangular matrix.

## Problem 3.

### 3-1.

Factor $A = \begin{bmatrix} 2 & 3 & 3 \\ 0 & 5 & 7 \\ 6 & 9 & 8 \end{bmatrix}$ into $LU$, and solve

$$Ax = A\begin{bmatrix} u \\ v \\ w\end{bmatrix} = b = \begin{bmatrix} 2 \\ 2 \\ 5 \end{bmatrix}$$

using series of two equations $Lc = b$ and $Ux = c$.

### 3-2.

Find $L,U$ for the symmetric matrix

$$A = \begin{bmatrix} a & a & a & a \\ a & b & b & b \\ a & b & c & c \\ a & b & c & d \end{bmatrix}$$

and find four conditions on $a,b,c,d$ to get $A = LU$ with four pivots.

## Problem 4.

### 4-1.

Use Gauss-Jordan method to invert

$$A = \begin{bmatrix} 1 & 0 & 0 \\ 1 & 1 & 1 \\ 0 & 0 & 1 \end{bmatrix}$$

### 4-2.

Prove that $A$ is invertible if $a\neq0$ and $a\neq b$, and find the pivots and $A^{-1}$.

$$A = \begin{bmatrix} a & b & b \\ a & a & b \\ a & a & a\end{bmatrix}$$

### 4-3.

True or false (with a counterexample if false and a reason if ture):

1. A $4$-by-$4$ matrix with a row of zeros is not invertible.
2. A matrix with $1$s down the main diagonal is invertible.
3. if $A$ is invertible then $A^{-1}$ is invertible.
4. If $A^T$ is invertible then $A$ is invertible.

## Problem 5

### 5-1.

Answer the six questions for
$$A = \begin{bmatrix} 2 & 4 & 6 & 4 \\ 2 & 5 & 7 & 6 \\ 2 & 3 & 5 & 2 \end{bmatrix},\quad b = \begin{bmatrix} b_1 \\ b_2 \\ b_3 \end{bmatrix} = \begin{bmatrix} 4 \\ 3 \\ 5 \end{bmatrix}$$

1. Reduce $[A\,\,d]$ to $[U\,\,c]$ where $U$ is the row echelon form of $A$.
2. Find the condition on $b_1,b_2,b_3$ to have a solution.
3. Describe the column space of $A$ in $\mathbf R^3$.
4. Describe the null space of $A$ and find special solutions in $\mathbf R^4$.
5. Find a paricular solution.
6. Reduce $[U\,\,c]$ to $[R\,\,d]$ where $R$ is the reduced row echelon form, and derive special solutions from $R$ and particular solution from $d$.

### 5-2.

Prove that for $n\times m$ matrix $A$ and $m\times l$ matrix $B$, the rank of $AB$ is less than or equal to the rank of $A$ and $B$.

## Problem 6

### 6-1.

Find the dimension of column space and row space of

$$A = \begin{bmatrix} 1 & 1 & 0 \\ 1 & 3 & 1 \\ 3 & 1 & -1 \end{bmatrix}$$

### 6-2.

Find a basis for each of these subspaces of $\mathbf R^4$.

1. All vectors whose components are equal.
2. All vectors whose components add to zero.
3. All vectors that are perpendicular to $(1,1,0,0)$ and $(1,0,1,1)$.
4. The null space of $U = \begin{bmatrix} 1 & 0 & 1 & 0 & 1 \\ 0 & 1 & 0 & 1 & 0 \end{bmatrix}$ 