# 3강 LU 분할

## 1.5 Triangular Factors   

$$ A x = b  $$

$$ A = LU  $$ 

Lower Triangular matrix * Upper Triangular matrix

> ? 가우시안 소거법을 행렬로 표현 -> Elementary Matrix $$  E_{31}E_{21} A  $$ => U (upper triangular matrix)

###### Elementary Matrix in GE
$$
E_{21} = \begin{bmatrix}1 & 0 & 0 \\-l_{21} & ? & ?  \\0 & 0 & 1  \end{bmatrix} 
$$

해석 : 2번식 - (1번식 * $$L_{21}$$) 



[참고]
$$
E_{21}^{-1} = \begin{bmatrix}1 & 0 & 0 \\l_{21} & 1 & 0  \\0 & 0 & 1  \end{bmatrix} 

$$

$$ E_{21}E_{21}^{-1} = I $$

---

#### LU는

$$
E_{32}E_{31}E_{21}A = U 
$$
$$
A = E_{32}^{-1}E_{31}^{-1}E_{21}^{-1} U 
$$
$$
\begin{bmatrix}1 & 0 & 0 \\l_{21} & 1 & 0  \\0 & 0 & 1  \end{bmatrix} 

\begin{bmatrix}1 & 0 & 0 \\0 & 1 & 0  \\l_{31} & 0 & 1  \end{bmatrix} 

\begin{bmatrix}1 & 0 & 0 \\0 & 1 & 0  \\0 & l_{32} & 1  \end{bmatrix} U
$$
$$
\begin{bmatrix}1 & 0 & 0 \\l_{21} & 1 & 0  \\l_{31} & l_{32} & 1  \end{bmatrix}
= Lower Triangular matrix = L 
$$ 

---
### LU 예시 

$$
A = \begin{bmatrix} 1 & 2 \\ 3 & 8 \end{bmatrix} 
$$

2번식 - (3번식) x 1

$$
U = \begin{bmatrix} 1 & 2 \\ 0 & 2 \end{bmatrix} 
$$

$$
L = \begin{bmatrix} 1 & 0 \\ 3 & 1 \end{bmatrix} 
$$




> ? Diagonal matrix(D) =  A = LU = LDU



























