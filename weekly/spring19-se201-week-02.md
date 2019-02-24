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
  * Column space $C(R)$.
  * Null space $N(R)$ and null matrix.
    * **Q** Why is $N(R)$ a vector space?
* Solving $Ax = b$ using the reduced form $R$.
  * Working example: $A = \begin{bmatrix}1 & 3 & 3 & 2 \\ 2 & 6 & 9 & 7 \\ -1 & -3 & 3 & 4 \end{bmatrix}$, $b = \begin{bmatrix}1 \\ 5 \\ 5\end{bmatrix}$.

### Timeline

* (0 ~ 5 min) Review
* (5 ~ 10 min) Questions, roster
* (10 ~ 55 min) Lecture on contents (English)
* (55 ~ 75 min) Discussion (Korean)

## Lecture 04 (19/3/7)

### To Do

* Review previous lecture
* Check roster

### Contents (2.2 - 2.3)

* Echelon form
  * Convert 
  $$A = \begin{bmatrix}1 & 3 & 3 & 2 \\ 2 & 6 & 9 & 7 \\ -1 & -3 & 3 & 4 \end{bmatrix}$$
  into row echeolon form $U$, reduced row echelon form $R$.
  * Six steps to find solution of $Ax=b$.
    * Reduce $[A\,\,b]$ to $[U\,\,c]$.
    * Find condition on $b$.
    * Describe column space of $A$.
    * Describe null space of $A$.
    * Find a particular solution to 
    $$Ax = \begin{bmatrix}1 \\ 5 \\ 5\end{bmatrix}$$
    * Reduce $[U\,\,c]$ to $[R\,\,d]$ and find special solution from $R$ and $x_p$ from $d$.
  * Rank of a matrix
  	* **Q** Show that the pivot columns of $A$ spans the column space $C(A)$, and the rest columns are written as linear combinations of pivot columns.
* Basis of vector spaces
  * Definition of basis
    * **Q** If $n>m$ then the set of $n$ vectors in a $m$-dimensional vector space is linearly dependent.
  * Dimension of vector subspaces
    * **Q** Show that the dimension of the column space $C(A)$ is the number of pivots in $A$.

### Timeline

* (0 ~ 5 min) Review
* (5 ~ 10 min) Questions, roster
* (10 ~ 55 min) Lecture on contents (English)
* (55 ~ 75 min) Discussion (Korean)

