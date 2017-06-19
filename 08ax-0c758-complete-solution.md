# Ax=b의 완전해(complete solution)

## 1. 해가 존재 하는지 알아 보기

가해 조건 확인 

|![](http://cfile27.uf.tistory.com/image/264280375876234918C5CE)|![](http://cfile4.uf.tistory.com/image/25779D455878E373135237)|![](http://cfile25.uf.tistory.com/image/24381E3B5876431D02789F)|
|-|-|
|원식|매트릭스폼|소거 <br>-[row2=row2-2*row1]<br>-[row3=row3-3*row1]|
|![](http://cfile26.uf.tistory.com/image/211E804B5876452E3F8A0F)|![](http://cfile25.uf.tistory.com/image/252C0B4F58778A33095D7B)|
|(row2, col3)의 아래원소를 2->0으로<br> row3=row3-row2|최종 U행렬|

최종 u행렬의 row3을 보면 좌변 계수는 모두 `0`이다. 따라서 $$b_3 - b_2 - b_1 = 0$$이다. 
    - 계수가 전부 0이기 때문에 어떤 변수를 곱해도 결과는 당연히 0이 될 수 밖에 없다.
    - 가해 조건(solvability condition)
    - 선형방정식에 해가 존재하기 위한 조건    

> 가해 조건을 확인해보는 것은 결국 이 선형방정식이 해가 존재하는지를 확인해보는 작업

## 2. 완전해 구하기 

### 2.1 particular solution(특수해) x를 찾는다. 

특수해 : 소거를 마친 행렬 U에서 free variable을 모두 0으로 만든 다음 pivot variable에 대해서 구한 해

|![](http://cfile2.uf.tistory.com/image/221A0B4B587A2197106EB9)|![](http://cfile24.uf.tistory.com/image/23636848587A232621A999)|![](http://cfile7.uf.tistory.com/image/270C3343587A27321FCEAE)|
|-|-|-|
|식(8)에서 Free variables로 식(9)를 만듬| free variable을 0으로 설정<<br>후방대입으로 $$ x_1=-2, x_3=\frac{3}{2}$$ 구함 |Ax=b의 `특수해` 도출|

### 2.2 Null Space해를 찾는다. 

널스페이스 해 : Ax=0을 만족시키는 x

||![](http://cfile24.uf.tistory.com/image/2338703C587A2DA5027F0B)
|-|-|
|7장 참고|최종 Null space 해|



### 2.3 완전해 구하기 = 특수해 + 널 스페이스 해 

![](http://cfile22.uf.tistory.com/image/21293345587A38EA1F767B)


---

# Rank와 Solution 

![](http://i.imgur.com/ZXZawGj.png)
n = rank , m = # of rows, n = # of columns


출처:[Learn Again! 러너게인](http://twlab.tistory.com/entry/Linear-Algebra-Lecture-8-선형방정식-Axb의-완전해complete-solution)
