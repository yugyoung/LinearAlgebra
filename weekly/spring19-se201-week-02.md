# Week 02

* Period: 19/3/4 - 19/3/8
* Lecture
  * Vectors and vector spaces
  * Solving $Ax = b$
  * Basis and dimensions
* Recitation
  * Python package `numpy`
  * Python package `matplotlib`

## Lecture 03 (19/3/4)

### To Do

* Review previous lecture
* Check roster
* Announce recitation classroom E3-317, 318 (Assign students while checking attendency)

### Contents (1.5 - 1.6)

* LU decompoisition
  * $LA = U, A = L^{-1}U = \bar L U$
  * Example: 
    $$A = \begin{bmatrix} 1 & 1 & 1 \\ 1 & 1 & 3 \\ 2 & 5 & 8 \end{bmatrix}$$
    * Permutation matrices
    * **Q** Let $A$ be a nonsingular matrix and $P$ be the multiple of all permutation matrices during the reduction of $A$ to row echelon form (REF). Show that $PA$ can be decomposed to $LU$.
  * LDU decomposition
    * Uniqueness

* Transpose and symmetric matrices
  * Property : $(AB)^T = B^TA^T$, $(A^{-1})^T = (A^T)^{-1}$
  * $LDU$ factorization of symmetric matrix: $LDL^T$
  * **Q** Re-visit the question: if a left (or right) inverse exists, then a right (or left) inverse exists.

* Gauss-Jordan elimination
  * Reduced row echelon from (RREF)
    * All pivots are 1 and pivot columns are placed in order.
    * 0 entries above and below the pivots.
  * Finding the inverse of $A = \begin{bmatrix} 1 & 1 & 1 \\ 1 & 1 & 3 \\ 2 & 5 & 8 \end{bmatrix}$

### Timeline

* (0 ~ 5 min) Review
* (5 ~ 10 min) Questions, roster
* (10 ~ 55 min) Lecture on contents (English)
  * LU decomposition (15 min)
  * Transpose and symmetric matrices (15 min)
  * Gauss-Jordan elimination (15 min)
* (55 ~ 75 min) Discussion (Korean)
  * $PA = LU$. (Hint: see how elementary row operation matrix $E$ 'commutes' with $P$.)
  * For a nonsingular matrix $A$, if a matrix $B$ satisfying $BA = I$ exists, then there is a matrix $C$ such that $AC = I$. (Hint: use the uniqueness of the $LDU$ decomposition.)

## Lecture 04 (19/3/7)

### To Do

* Review previous lecture
* Check roster

### Contents (2.1 - 2.2)

* Vectors
  * Vector addition, scalar multiplications
  * Inner product
    * **Q** Show that for any two vectors $v,w$ with internal angle $\theta$, the following holds.
    $$v\cdot w = \Vert v\Vert\Vert w\Vert\cos\theta$$
  * linear combination, linear independence
* Vector spaces 
  * Difference between Euclidean space
  * Working example: $R = \begin{bmatrix} 1 & 3 & 0 & -1 \\ 0 & 0 & 1 & 1 \\ 0 & 0 & 0 & 0\end{bmatrix}$
  * Column space $C(A)$.
  * Null space $N(A)$ and null matrix.
    * **Q** Why is $N(A)$ a vector space?
* Solving $Ax = b$
  * Working example: 
    $$A = \begin{bmatrix}1 & 3 & 3 & 2 \\ 2 & 6 & 9 & 7 \\ -1 & -3 & 3 & 4 \end{bmatrix},\quad b = \begin{bmatrix}1 \\ 5 \\ 5\end{bmatrix}$$
  * Six steps to find solution of $Ax=b$.
    * Reduce $[A\,\,b]$ to REF.
    * Find condition on $b$.
    * Describe column space of $A$.
    * Describe null space of $A$.
    * Reduce REF to RREF and find special and particular solutions.
  * The rank

### Timeline

* (0 ~ 5 min) Review
* (5 ~ 10 min) Questions, roster
* (10 ~ 55 min) Lecture on contents (English)
  * Vectors (10 min)
  * Vector spaces (10 min)
  * Solving $Ax = b$ (25 min)
* (55 ~ 75 min) Discussion (Korean)
  * $v\cdot w = \Vert v\Vert\Vert w\Vert\cos\theta$ (Hint: show for $2$-dimensional case, and generalize.)
  * $N(A)$ is a vector space. (Hint: what is the definition of a vector space?)

