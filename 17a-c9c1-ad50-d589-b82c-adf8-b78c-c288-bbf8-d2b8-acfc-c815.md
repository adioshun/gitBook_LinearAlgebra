# 직교행렬(Orthogonal Matrices)과 그람 슈미트 과정(Gram-Schmidt Process)

직교 행렬
- 모든 column vector가 자기 자신을 제외한 나머지 모든 column vector들과 직교
- 크기가 1인 단위 벡터들로 구성된 행렬


그람 슈미트 과정
- 임의의 독립 행렬(independent matrix)로부터 각 column vector가 정규직교(Orthonormal)한 벡터들로 구성된 `직교 행렬`을 만드는 과정

## 1. 정규직교벡터(Orthonormal Vector)

### 1.1 단위 벡터(Unit Vector)

정의 : 길이가 1(단위길이)인 벡터 = `방향성분`만을 나타내는 벡터 = 크기 성분에는 영향을 끼치지 않음
    - 예 : 길이를 나타내는 2m에서 m는 길이를 나타내며 실제 길이에는 영향을 안 미침 
    
|일반벡터 -> 단위백터 | ![](http://cfile29.uf.tistory.com/image/220AD33458E27EE42CB3A0)|
|-|-|
|(예) $$v=[2 1 3]^T$$ <br> -> 단위벡터|![](http://cfile24.uf.tistory.com/image/2537C54C58E27E60325CBF)|

단위 벡터 = 정규화 벡터(normalized vector)라고도 한다. 
- 즉 서로 다른 스케일을 가지고있는 벡터들을 동일한 스케일에서 바라보기위해 벡터의 크기로 나누어 정규화(normalization)한 벡터를 의미한다. 

### 1.2 정규직교벡터(Orthonormal vector)

