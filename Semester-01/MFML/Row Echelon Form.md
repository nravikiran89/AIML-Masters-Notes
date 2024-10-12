### Row Echelon Form
A matrix is said to be in Row Echelon Form if
- All rows having zero entries are at the bottom
- The leading entry (left-most nonzero entry) of every non-zero row, called the pivot, is on the right of the leading entry of the row above.
- Example: $$
\begin{bmatrix}
a_0& a_1& a_2& a_3& a_4\\
0& a_5& a_6& a_7& a_8 \\
0& 0& 0& a_6& a_7 \\
0& 0& 0& 0& 0
\end{bmatrix}
$$
### Reduced Row Echelon Form
A matrix is in Reduced Row Echelon Form if
- It is in [[Row Echelon Form]]
- Leading entry in each non-zero row is 1
- Each column containing the leading 1 has zeros in all it's other entries.

Given a matrix in reduced row echelon form, the rows can be reorganized to obtain a matrix of the form $$\begin{pmatrix}I& X\\0& 0\end{pmatrix}$$

### Gaussian Elimination
Process of obtaining a [[#Row Echelon Form]] or a [[#Reduced Row Echelon Form]] from a series of Elementary Operations.
