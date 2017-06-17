# Matrix multiplication (행렬 곱)

> [다시 살펴 보기](http://twlab.tistory.com/entry/%ED%96%89%EB%A0%AC%EA%B3%B1%EC%85%89Matrix-multiplication-%EC%97%AD%ED%96%89%EB%A0%ACInverse-matrix-%EA%B7%B8%EB%A6%AC%EA%B3%A0-GaussJordan)

# 1 Row x column 방법 

# 2 Column-wise방법 

# 3 Row-wise 방법 

# 4 column x row 방법 

# 5 Block Multiplication 방법 

--- 
# Inverse\(역행렬\)

$$ AA^{-1} = A^{-1}A = I $$

> 보통 행렬은 곱셈의 순서에 따라 결과가 달라진다. 하지만, 역행렬이 존재 하는 `정방행렬(Square Matrix)`의 경우는 그렇지 않다.

한개 이상의 역행렬의 곱
![](http://cfile23.uf.tistory.com/image/276838355845878C2E3000)


###### 역행렬 존재 요구 사항

1. 만약, 가우스 소거법 결과과 N 개의 피폿을 생성할때 \(=가우스 소거법이 가능하다\)

2. The inverse is unique

3. if $$ A^{-1} $$ exists, Ax = b =&gt; $$AA^{-1}x = A^{-1}b $$

4. Assume that there is a non-zero vector X such that Ax = 0 \(b=0\) ==&gt; then $$ A^{-1} $$ does not exist 


5. Diagonal Matrix의 역행렬은 $$ d_n -> 1/d_n $$
  * 대각선은 0이 존재 하면 안된다. \(곱해서 0이 되면 안됨\)


6. The inverse comes in the reverse order
  * $$ (ABC)^{-1} = C^{-1}B^{-1}A^{-1}  $$


###### 역행렬이 존재 하지 않는 경우 

1. Ax = 0을 만족 하는 해가 있는 경우 
  - A는 정방행렬, x는 0이 아닌 백터


2. 행렬식이 0이 되는 경우 

3. Column picture에서 두 column이 같은 방향을 가르 키는 경우 


### 1.1 역행렬 계산법 \(2x2경우\)

$$
A^{-1} = \frac{1}{ad-bc}\begin{bmatrix} d & -b \\ -c & a  \end{bmatrix} 


$$

### 1.2 역행렬 계산 법 \(3x3 이상의 경우\) - Gauss-Jordan Method
1. A에 역행렬을 곱하면 I가 되어야 한다. 
![](http://cfile9.uf.tistory.com/image/2371784D5839C868199769)

2. 두개의 column wise시스템으로 분리 하면 아래와 같다. 
![](http://cfile29.uf.tistory.com/image/2108CC485839CF8C14C9D5)

3. 두 식을 합쳐서 하나의 식으로 만든다. 이때, Augmented Matrix의 extra column를 두개로 한다. 
![](http://cfile3.uf.tistory.com/image/215852495839D85F1EDF80)

4.  Gauss소거법을 활용해 소거
![](http://cfile5.uf.tistory.com/image/2451AE495839DD9025DB01)

5. 반대로 아래에서 위쪽으로 소거를 한번 더 진행 
![](http://cfile9.uf.tistory.com/image/276A894F5839DF291A6375)

