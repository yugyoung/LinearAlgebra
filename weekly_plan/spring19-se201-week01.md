# Week 01


* Period: 19/2/25 - 19/3/1
* Lecture (1.1 - 2.3, skip 1.7)
  * Introduction to vectors and linear equations
  * Elimination by matrices
  * Vectors and vector spaces
* Recitation
  * Introduction to Python programming.
  * Installing Python IDEs.

## Lecture 01 (19/2/25)

### To Do
* Overview syllabus
  * Emphasize homework policy
  * Explain the purpose of the project
* Checking roster
* Split recitation classes
  * Check available time

### Contents

* Notations
  * Define vector notations: tuple, column, or row representations.
  * Define matrix addition, multiplication, scalar multiplications. 
  * Upshots for using row / column reprensetations of vectors. 

* System of linear equations
  * Converting the system of linear equation into a matrix equation.
  * Classifications of systems of linear equations with 3 undetermined variables by geometric position of planes.
  * Working example: $\begin{bmatrix} 2 & 1 & 1 \\ 4 & -6 & 0 \\ -2 & 7 & 2 \end{bmatrix}  \begin{bmatrix} u \\ v \\ w\end{bmatrix} = \begin{bmatrix}5 \\ -2 \\ 9 \end{bmatrix}$

* Elimination method
  * Pivots.
    * **Q** In what conditions of pivots is there a unique solution to the system of linear equations?
  * Upper / lower triangular matrices, echelon form. 
    * **Q** Show that the multiple of two lower (or upper) triangular matrices is also lower (or upper) triangular.
  * Elementary row operations.

* Inverse matrix
  * Nonsingular system and inverse matrix.
  * LU decomposition.
    * **Q** Show that if $A$ is nonsingular, then there exists a permutation matrix $P$ such that $PA=LU$.
  * Gauss-Jordon elimination.
  * Working example: $A = \begin{bmatrix} 2 & 1 & 1 \\ 4 & -6 & 0 \\ -2 & 7 & 2 \end{bmatrix}$

### Timeline

* (0 ~ 10 min) Syllabus
* (10 ~ 15 min) Roster and recitation availability check
* (15 ~ 55 min) Lecture on main contents (English)
* (55 ~ 75 min) Discussion on questions (Korean)

## Lecture 02 (19/2/28)

### To Do

* Review previous lecture
* Check roster
* Announce homework assignment #01

### Contents

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