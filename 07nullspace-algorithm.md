# Null Space 계산 알고리즘 
- Ax = 0에서 A를 소거 

## 1. 소거를 통해 U구하기 
### 1.1 1번쨰 피봇 계산
![](http://cfile25.uf.tistory.com/image/26778933586E57E62F758E)

Step 1 : (2)에서 Low 1에 x2를 하여 Low 2를 뺀값
Step 2 : (2)에서 Low 1에 x3를 하여 Low 3를 뺀값

### 1.2 2번쨰 피봇 계산 
![](http://cfile10.uf.tistory.com/image/22762843586E59662A2345)

두번째Row가 `0`임 -> 세번쨰 Row와 `행교환`필요 -> 세번째 Row도 `0` 

Step 1 : (4)에서 Low 2에 x(-1)을 하여 Low을 뺸값 
![](http://cfile2.uf.tistory.com/image/2421764D586E5D9703BB70)

진행은 하였지만, 역삼각형(Upper triangular matrix)이 아닌 계단형태, 이를 `echelon form`이라 함

|중요 : 피봇의 갯수가 2개임을 파악 = 행렬 A의 Rank 는 2|Rank of A = number of pivots|
|-|-|

## 2. Ux = 0 풀기 

### 2.1 Pivot column와 Free column 정의 하기 

! [](http://cfile27.uf.tistory.com/image/26400C4D58703B0B2B5E5D)

### 2.2 Free column에 임이의 값 할당 후 후방대입법으로 풀기 

free columns는 임이의 값을 자유롭게 설정 할수 있음 

#### A. [예제] x2=1, x4=0을 할당

|![](http://cfile24.uf.tistory.com/image/24324939586FB3F72FBEA3)|![](http://cfile24.uf.tistory.com/image/21165643586FB59E2ED21C)|
|-|-|
|![](http://cfile26.uf.tistory.com/image/2119E64C586FB8BD14743C) |$$2x_3 = 0 \rightarrow x_3 = 0 $$ <br><br> $$x_1=-2 $$ <br><br> $$ X^T = \{-2,1,0,0\} $$ |

#### B. [예제] x2=0, x4=1을 할당

|![](http://cfile10.uf.tistory.com/image/2361F75058703AE13A6359)||
|-|-|
|![](http://cfile28.uf.tistory.com/image/211D713458703D8A21508F) |$$2x_3 = 0 \rightarrow x_3 = 0 $$ <br><br> $$x_1=-2 $$ <br><br> $$ X^T = \{-2,1,0,0\} $$ |





## 2.4 해 확장 

![](http://cfile26.uf.tistory.com/image/2315A73C5870392306694E), 해에 상수 c를 곱하여 새로운 해 찾을수 있음 


