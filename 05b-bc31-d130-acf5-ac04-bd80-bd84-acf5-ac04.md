# 벡터 공간

- 정의 : 다수의 벡터가 있고, 이 벡터들이 모여 하나의 공간을 형성하는 것이다. 백터들의 집합

- 조건 : 그러나 아무 벡터나 허용 되는 것은 아니다. 이 공간상에 존재하는 벡터들은 서로가 서로에게 **더해**질 수 있고, 임의의 숫자가 각각에 **곱해**져서 각 벡터의 길이가 늘어날 수도 있다

- 성질 
  1. x+y = y +x
  2. x + (y +z ) = (x+y)+z
  3. there is a zero-vector(항상 Zero(원점,중점) vetor를 포함하고 있다)
  4. For each vector X, 
      - X + (-X) = (-X) + X = 0  
  5. 1 * X = X
  6. c(X+Y) = cX + cY 
  7. (c1 + c2)X = C1X + C2X 


|정의: 모든 벡터들이 존재할 수 있는 공간|
|-|
|요구사항 1: Closed under addition <br> 요구사항 2: Closed under Scalar multiplications|
|[해석]<br>- 선형결합(Linear Combination)연산이 같은 공간상에 존재하는 벡터들 사이에 가능해야 한다.<br> - 벡터 공간내의 벡터들은 서로 더하고 임의의 scale상수를 곱해도 그 결과 벡터가 해당 공간내에 존재해야 한다|

---

# 부분 벡터(subspace)

- 정의 : 임의의 n차원 공간에 대해, n차원 공간에 포함되면서 n차원 벡터들에 대해 선형 결합 연산이 성립하는 작은 공간

- 조건
  - 부분 공간이 되기 위해선 어떠한 수를 **곱하**거나, 같은 공간내의 어떠한 벡터들을 **더해**도 그 결과가 부분 공간내에 존재해야 한다
  - $$R^2$$의 부분 공간(subspace)은 "반드시 zero vector를 포함(0을 지나야 한다)해야 한다!", 왜냐하면 어떠한 벡터도 영을 곱하면 zero vector가 되기 때문이다.
  

## 1. $$R^2$$에서 가능한 부분 공간은 
- All of $$ R^2 $$ 
- Any line through zero vector
- zero vector only

## 2. $$R^3$$에서 가능한 부분 공간은 
- All of $$ R^3 $$ 
- plane through the origin(zero vector)
- line through the origin(zero vector)
- zero vector itself


## 3. 두개 이상의 부분 집합의 합/교집합

- 어떤 부분 공간들의 합집합은 부분 공간(subspace)이 아니다. 

- 어떤 부분 공간들의 교집합은 부분 공간(subspace)이다. 






  


