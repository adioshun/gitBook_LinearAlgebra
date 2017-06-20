


## 3. 해를 구하기 위한 방법
![](http://cfile6.uf.tistory.com/image/24502934581DC8162AFF95)

|가우스 소거법|상삼각행렬|후진 대입|
|-|-|-|



### 2.1 가우스 소거법 
- 연립 방정식을 푸는 방법 
- 미지수의 갯수와 방정식의 갯수가 같은 경우
- 목적 : 시스템 행렬 A를 upper triangular matrix로 만드는것  

`All pivots are non-zero -> G.E has a unique solution`

Matrix로 표현 = upper Triangular U 

고려 사항 : 피봇에 0이 존재 하면 가우스 소거법 사용 못함 
- pivot에 `0`이 존재 하여 가우스 소거법을 사용 못할경우, 순서를 바꾸어 문제 해결 --> pivoting 

### 2.2 Back-substitution (후방 대입법)
기존 소거법은 Ax = b에서 A만을 소거 하는 방식, b까지 고려 하여 소거법을 적용 해야 한다


일단 b까지 추가 하여 행렬을 생성 = augmented Matrix 
![](http://i.imgur.com/cSEt4bl.png)

 $$ x + 2y + z =  2 $$
 $$     2y -2z =  6 $$
 $$         5z =-10 $$ 
 
후방대입법이란 말 그대로 아래쪽 변수, 즉 z텀(z=-2)만 남아있는 세 번째 Row방정식에서부터 해를 풀어나가는 것





### 3.3 Elimination matrices (소거 행렬= E)

![](http://cfile9.uf.tistory.com/image/2669753358220C1E0E87C5)

> 소거 행렬을 $$ E_{21}$$이라고 표현한 이유는 A의 Row2/Col1(=값 3)을 0으로 만드는 것이 목적이므로 

###### 1. Row1과 Row3은 그대로 유지 하기 위하여 I 행렬로 지정 
![](http://cfile25.uf.tistory.com/image/252B3C45582211FC070F56)

###### 2. Row2는 A의 Row1에 3을 곱하고 Row2에서 이를 뺴준다. (Row3은 아무 역할도 안함)
![](http://cfile9.uf.tistory.com/image/2762593F58234AB60AF0BE)

###### 3. Row3은 A`의 Row2에 2를 곱하고 Row3에서 이를 뺴준다. 
![](http://cfile3.uf.tistory.com/image/254C143F582353E038D2FD)
- 소거 행렬 $$ E_{32}$$ 를 생성 하는것 
- 산출물은 U 행렬

###### 정리 $$ (E_{32}E_{21}) A = u \Rightarrow EA=u $$







