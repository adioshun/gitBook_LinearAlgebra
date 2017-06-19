# 벡터 공간

- 정의 : 다수의 벡터가 있고, 이 벡터들이 모여 하나의 공간을 형성하는 것이다. 

- 조건 : 그러나 아무 벡터나 허용 되는 것은 아니다. 이 공간상에 존재하는 벡터들은 서로가 서로에게 **더해**질 수 있고, 임의의 숫자가 각각에 **곱해**져서 각 벡터의 길이가 늘어날 수도 있다

|모든 벡터들이 존재할 수 있는 공간|
|-|

> 선형결합(Linear Combination)연산이 같은 공간상에 존재하는 벡터들 사이에 가능해야 한다.

> 벡터 공간내의 벡터들은 서로 더하고 임의의 scale상수를 곱해도 그 결과 벡터가 해당 공간내에 존재해야 한다


---

# 부분 벡터(subspace)

- 정의 : 임의의 n차원 공간에 대해, n차원 공간에 포함되면서 n차원 벡터들에 대해 선형 결합 연산이 성립하는 작은 공간

- 조건
  - 부분 공간이 되기 위해선 어떠한 수를 **곱하**거나, 같은 공간내의 어떠한 벡터들을 **더해**도 그 결과가 부분 공간내에 존재해야 한다
  - $$R^2$$의 부분 공간(subspace)은 "반드시 zero vector를 포함해야 한다!", 왜냐하면 어떠한 벡터도 영을 곱하면 zero vector가 되기 때문이다.
  
  


## 1. $$R^2$$에서 가능한 부분 공간은 
- All of $$ R^2 $$ 
- Any line through zero vector
- zero vector only

## 2. $$R^3$$에서 가능한 부분 공간은 
- All of $$ R^3 $$ 
- plane through the origin(zero vector)
- line through the origin(zero vector)
- zero vector itself


## 3. 행렬의 부분 공간(Subspace of Matrix)
- 행렬에서 부분공간 끄집어내기 

![](http://cfile5.uf.tistory.com/image/2453CF3B585E868F0DC41E)

위 행렬에서 끄집어 낼수 있는 공간 : Column space 

> 임의의 행렬 A에서, 모든 column의 선형 결합(Linear Combination)은 부분 공간(subspace)을 형성한다. 우리는 이를 column space라 부르고 C(A)로 쓴다. 


|![](http://cfile21.uf.tistory.com/image/26736144585E8B0A142287)|![](http://cfile28.uf.tistory.com/image/274ECC36585E93B61062DA)|
|-|-|
|기본|모든 선형 결합(임이의 +,x으로 이루어짐)

  


