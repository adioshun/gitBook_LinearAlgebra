# The Geometry of Linear Equations

## 1. 선형성 정의 

행렬 연산을 하려면 선형성을 만족 해야 함. 

선형성 요구 사항 
- Superposition : $$f(x_1 + x_2) = f(x_1) + f(x_2) $$

- Homogeniety : $$ f(ax) = a f(x) $$

> 합쳐서 $$ f(a_1 x_1 + a_2 x_2) = a_1 f(x_1) + a_2 f(x_2)  $$

`원점을 지나는 평면상의 직선은 선형성을 만족 하며, 백터라고 부름`


##### Matrix Form
$$
 \Rightarrow \begin{bmatrix} 2 & -1 \\ -1 & 2 \end{bmatrix} \begin{bmatrix} x \\ y \end{bmatrix} = \begin{bmatrix} 0 \\ 3 \end{bmatrix} 
$$

## 2. 선형 시스템 해석 하는 방법 

### 2.1 Row picture

방정식이 나타내는 기하(Geometry) 들의 교차(Intersection) 가 $$A\mathbf{x} = \mathbf{b}$$ 의 solution 이 된다. 예를 들어 A 가$$ 2\times2$$ 행렬이면 두 직선의 교차를, $$3\times3 $$행렬이라면 세 평면의 **교차**를 나타낸다. 1

### 2.2 Column picture

$$\mathbf{x}$$ 는 A 의 열 벡터들의 선형 결합 계수다. 다시 말해 A 의 열 벡터들의 선형결합으로 $$\mathbf{b}$$ 를 나타낼 수 있다면 해가 존재한다. $$\mathbf{b}$$ 에 도달하기 위해 A 의 열 벡터들을 **늘이거나 줄이는** 그림을 상상해보자.

|Row picture|column picture|
|-|-|
|row 방법 = 내적(Dot Product)|Column 방법  = 선형결합(Linear Comnibation)|
|$$ 2x -  y = 0 $$ <br>$$ -x + 2y = 3 $$|$$ x\begin{bmatrix} 2 \\ -1\end{bmatrix} + y\begin{bmatrix} -1 \\ 2 \end{bmatrix} = \begin{bmatrix} 0 \\ 3 \end{bmatrix} $$|
|![](http://cfile9.uf.tistory.com/image/2151C54158065BC00BBBD0)|![](http://cfile29.uf.tistory.com/image/260E323A5807A4A5307F03)|
|교점을 찾는것이 목표|벡터 v1과 v2에 얼마의 상수 x, y를 각각 곱하여 벡터 b를 만드는 것|



