<h1 align="center">Linear Algebra</h1>

## 1. Vectors and Matrices

- **Vector**: an ordered list of numbers representing quantities in a fixed order.

$$
u = \begin{bmatrix}
x1 \\
x2
\end{bmatrix}
$$

- **Scalar Multiplication:** multiplying a vector by a scalar means multiplying every entry by the same number.

$$
c\begin{bmatrix}
x1\\
x2\end{bmatrix} = \begin{bmatrix}
cx1\\
cx2\end{bmatrix}
$$

- **Vector addition:** adds corresponding entries.

$$
u+w=
\begin{bmatrix}
3\\
1
\end{bmatrix}
+
\begin{bmatrix}
1\\
2
\end{bmatrix} =
\begin{bmatrix}
4\\
3
\end{bmatrix}
$$

- **Dot Product**: multiplies corresponding entries of two vectors and adds the results. It produces a single number.

$$
a = \begin{bmatrix}
a_1 \\
a_2
\end{bmatrix},
\quad
b = \begin{bmatrix}
b_1 \\
b_2
\end{bmatrix}
$$

$$
a \cdot b = a_1b_1 + a_2b_2
$$

- **Matrix**: a rectangular arrangement of numbers in rows and columns.
- **Matrix–Vector Multiplication**: applies the dot product to each matrix row and the input vector. For \(Mu\) to be valid, the number of columns of \(M\) must equal the number of rows of \(u\).

$$
Mu =
\underbrace{
\begin{bmatrix}
1 & 0 \\
0 & 1 \\
0.6 & 0.8
\end{bmatrix}
}_{3 \times 2}
\underbrace{
\begin{bmatrix}
3 \\
1
\end{bmatrix}
}_{2 \times 1} =
\underbrace{
\begin{bmatrix}
3 \\
1 \\
2.6
\end{bmatrix}
}_{3 \times 1}
$$

- **Matrix–Matrix Multiplication**: multiplying the feature matrix \(M\) by the user matrix \(U\) calculates scores for all videos across both users simultaneously.

$$
MU =
\underbrace{
\begin{bmatrix}
1 & 0 \\
0 & 1 \\
0.6 & 0.8
\end{bmatrix}
}_{3 \times 2}
\underbrace{
\begin{bmatrix}
3 & 1 \\
1 & 2
\end{bmatrix}
}_{2 \times 2} =
\underbrace{
\begin{bmatrix}
3 & 1 \\
1 & 2 \\
2.6 & 2.2
\end{bmatrix}
}_{3 \times 2}
$$

---

