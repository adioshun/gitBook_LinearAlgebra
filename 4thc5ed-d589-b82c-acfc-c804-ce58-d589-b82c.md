## 1.6 Inverse & Transpose 

### A. Inverse(역행렬)

$$ AA^{-1} = A^{-1}A = I $$ 

역행렬 존재 요구 사항 
- 만약, 가우스 소거법 결과과 N 개의 피폿을 생성할때 (=가우스 소거법이 가능하다)
- The inverse is unique
- if $$ A^{-1} $$ exists, Ax = b => $$AA^{-1}x = A^{-1}b $$
- Assume that there is a non-zero vector X such that Ax = 0 (b=0) ==> then $$ A^{-1} $$ does not exist 
- 2x2일때의 역행렬은 공식으로 유도 된다. (3x3 이상일때는 가우시안 조르단 방식을 이용)
- Diagonal Matrix의 역행렬은 $$ d_n -> 1/d_n $$
    - 대각선은 0이 존재 하면 안된다. (곱해서 0이 되면 안됨)
- The inverse comes in the reverse order
    - $$ (ABC)^{-1} = C^{-1}B^{-1}A^{-1}  $$

###### $$A^{-1}$$ Gauss-Jordan Method 

### B. Transpose (전치행렬)
$$  A^T = a_{ij} -> a_{ji} $$

$$ (A+B)^T = A^T + B^T$$

$$ (AB)^T = B^TA^T$$

$$(A^{-1})^T = (A^T)^{-1} $$


