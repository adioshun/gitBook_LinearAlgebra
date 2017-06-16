# 선형성 정의 

행렬 연산을 하려면 선형성을 만족 해야 함. 

선형성 요구 사항 
- Superposition : $$f(x_1 + x_2) = f(x_1) + f(x_2) $$

- Homogeniety : $$ f(ax) = a f(x) $$

> 합쳐서 $$ f(a_1 x_1 + a_2 x_2) = a_1 f(x_1) + a_2 f(x_2)  $$

`원점을 지나는 평면상의 직선은 선형성을 만족 하며, 백터라고 부름`

# 1차 연립 방법식과 가우스 소거법

Singular case  
    - 답이 없음 
    - 답이 무수히 많음 


#### 1. row form = 내적(Dot Product)

#### 2. Column form  = 선형결합(Linear Comnibation)

Matrix Form
$$
 \Rightarrow \begin{bmatrix} 2 & -1 \\ -1 & 2 \end{bmatrix} \begin{bmatrix} x \\ y \end{bmatrix} = \begin{bmatrix} 0 \\ 3 \end{bmatrix} 
$$

Row picture

$$ 2x -  y = 0 $$ 
$$ -x + 2y = 3 $$

column picture
$$
 x\begin{bmatrix} 2 \\ -1\end{bmatrix} + y\begin{bmatrix} -1 \\ 2 \end{bmatrix} = \begin{bmatrix} 0 \\ 3 \end{bmatrix} 
$$




## 가우스 소거법 
- 연립 방정식을 푸는 방법 
- 미지수의 갯수와 방정식의 갯수가 같은 경우 

`All pivots are non-zero -> G.E has a unique solution`

Matrix로 표현 = upper Triangular U 

## Breakdown 
- pivot에 `0`이 존재 하여 가우스 소거법을 사용 못할경우, 순서를 바꾸어 문제 해결 --> pivoting 

## 1.4 Matrix Multiplication 



