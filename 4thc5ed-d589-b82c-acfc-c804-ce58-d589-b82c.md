#1.6 Inverse & Transpose 

## 1. Inverse(역행렬)

$$ AA^{-1} = A^{-1}A = I $$ 

> 보통 행렬은 곱셈의 순서에 따라 결과가 달라진다. 하지만, 역행렬이 존재 하는 `정방행렬(Square Matrix)`의 경우는 그렇지 않다. 

###### 역행렬 존재 요구 사항 
- 만약, 가우스 소거법 결과과 N 개의 피폿을 생성할때 (=가우스 소거법이 가능하다)
- The inverse is unique
- if $$ A^{-1} $$ exists, Ax = b => $$AA^{-1}x = A^{-1}b $$
- Assume that there is a non-zero vector X such that Ax = 0 (b=0) ==> then $$ A^{-1} $$ does not exist 
- Diagonal Matrix의 역행렬은 $$ d_n -> 1/d_n $$
    - 대각선은 0이 존재 하면 안된다. (곱해서 0이 되면 안됨)
- The inverse comes in the reverse order
    - $$ (ABC)^{-1} = C^{-1}B^{-1}A^{-1}  $$

### 1.1 역행렬 계산법 (2x2경우)

### 1.2 역행렬 계산 법 (3x3 이상의 경우)
Gauss-Jordan Method 



## 2. Transpose (전치행렬)
$$  A^T = a_{ij} -> a_{ji} $$

$$ (A+B)^T = A^T + B^T$$

$$ (AB)^T = B^TA^T$$

$$(A^{-1})^T = (A^T)^{-1} $$



###### Symmetric Matrix (대칭행렬)
$$ A^T = A $$ : 전치해도 값이 같다. 

- if A is symmetrix and invertible, then $$ A^{-1}$$ is too 


###### Correlation Matrix 
- 자신과 관련된 정보 출력 

$$ R = A^TA$$

$$ R^T = R $$

> 자신과 자신의 전치와의 곱은 내적과 같음 