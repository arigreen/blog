---
layout: post
title: Problem Set 2.1
---

# Problem Set 2.1


**Problems 1-8 are about the row and column pictures of $$Ax = b$$.**
## Problem 1
With $$A = I$$ (the identity matrix) draw the planes in the row picture. Three sides of a box meet at the solution $$\boldsymbol{x} = (x, y, z) = (2, 3, 4)$$:

$$
\begin{array}{}
    1x+0y+0z&=2 \\
    0x+1y+0z&=3 \\
    0x+0y+0z&=4&
\end{array}
\quad
\text{or}
\quad
\begin{bmatrix}
    1 & 0 & 0 \\
    0 & 1 & 0 \\
    0 & 0 & 1
\end{bmatrix}
\begin{bmatrix} x \\ y \\ z
\end{bmatrix}
=
\begin{bmatrix} 2 \\ 3 \\ 4\end{bmatrix}
.
$$

Draw the vectors in the column picture. Two times column 1 plus three times column 2 plus four times column 3 equals the right side $$\boldsymbol{b}$$.

## Solution 1

Row picture:
> TODO: Add a 3d graphs for the row and column pictures.

The row picture consists of three perpendicular planes: $$x=2$$, $$y=3$$, and $$z=4$$.

The column picture consists of three vectors, each of length 1:
$$\boldsymbol{i} = \begin{bmatrix} 1 \\ 0 \\ 0 \end{bmatrix}$$,
$$\boldsymbol{j} = \begin{bmatrix} 0 \\ 1 \\ 0 \end{bmatrix}$$, and
$$\boldsymbol{k} = \begin{bmatrix} 0 \\ 0 \\ 1 \end{bmatrix}$$.

$$
2\boldsymbol{i} + 3\boldsymbol{j} + 4\boldsymbol{k} = \boldsymbol{b}
$$
