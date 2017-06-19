# Null Space 계산 알고리즘 
- Ax = 0에서 A를 소거 

## 1. 1번쨰 피봇 계산
![](http://cfile25.uf.tistory.com/image/26778933586E57E62F758E)

Step 1 : (2)에서 Low 1에 x2를 하여 Low 2를 뺀값
Step 2 : (2)에서 Low 1에 x3를 하여 Low 3를 뺀값

## 2. 2번쨰 피봇 계산 
![](http://cfile10.uf.tistory.com/image/22762843586E59662A2345)

두번째Row가 `0`임 -> 세번쨰 Row와 `행교환`필요 -> 세번째 Row도 `0` 

Step 1 : (4)에서 Low 2에 x(-1)을 하여 Low을 뺸값 
![](http://cfile2.uf.tistory.com/image/2421764D586E5D9703BB70)

진행은 하였지만, 역삼각형(Upper triangular matrix)이 아닌 계단형태, 이를 `echelon form`이라 함

|중요 : 피봇의 갯수가 2개임을 파악 = 행렬 A의 Rank 는 2|Rank of A = number of pivots|
|-|-|

## 3. 알려진 행렬A의 Rank로 



