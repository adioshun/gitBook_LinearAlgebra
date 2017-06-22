# Column Space of A 

표기 : C(A)

정의
- Set of all linear combinations of column vectors in A
- 임의의 행렬 A에서, 모든 column의 선형 결합(Linear Combination)은 부분 공간(subspace)을 형성한다. 

- 열벡터(Column Vector)로 만들어질 수 있는 모든 선형 결합(Linear Combination)을 모아놓은 공간

![](http://cfile10.uf.tistory.com/image/24278237550B9C67058A76)

cf. 열백터(=열행렬) : 크기가 n x 1 인 행렬, 한열만 있는 행렬 
- $$ A^T = [a_1 a_2 a_3 a_4 ....a_n] $$

의의
- 열공간을 통행 Ax = b 라는 선형 방정식의 Solution 존재 여부를 알 수 있음

|![](http://cfile21.uf.tistory.com/image/26736144585E8B0A142287)|![](http://cfile28.uf.tistory.com/image/274ECC36585E93B61062DA)|
|-|-|
|기본|모든 선형 결합(임이의 +,x으로 이루어짐)


---

# Null Space of A 

표기 : N(A)

정의 
- Set of vetctor such that Ax=0

- N(A) = {x | Ax =0} : Ax =0을 만족하는 모든 x의 값 

부분 공간의 일종 
- Ax=0의 해(Solutions)들이 이루는 공간
    - Ax=b에서 b가zero vector(=Null vector, =0벡터)
