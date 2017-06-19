# Four fundamental subspaces

임의의 행렬 A에 대한 네 개의 주요부분공간은 아래와 같다. 
1. Column space 
2. Null space 
3. Row space 
4. Left null space

## 1. column space
행렬 A의 column vector들의 선형 조합(Linear combination)을 통해 형성하는 공간

## 2.  Null space
Ax=0를 만족시키는 해(x)들의 선형 조합으로 형성되는 공간

## 3. Row space

- 행렬 A의 row vector들의 선형 조합을 통해 형성하는 공간

- 만약 행렬 A의 row vector들이 
    - 독립(Independent)이면 기저(basis)가 되고,
    - 종속(Dependent)일 경우, 기저가 아니다.

row space를 column vector로 표현하려면 어떻게 해야 할까? 바로 A의 전치(Transpose)행렬에 대한 column space를 구하면 된다

> Row space = All combinations of columns of $$A^T = C(A^T)$$ 

## 4. Left null space

- 행렬 A의 전치에 대한 Null space

> Left null space - null space of $$A^T$$ = $$N(A^T)$$


