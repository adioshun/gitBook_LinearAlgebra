# 용어 정리 

## 1 선형
‘선형(Linear)’이란 ‘줄 선(線)’ + ‘모형 형(型)’이 결합한 단어로, 선의 형상을 갖는 것입니다.


선형성
- wiki : 그래픽적으로 직선 형태로 표현될 수 있는 수학적 관계(또는 함수)를 의미
- 통계: 독립 변수에 대한 결과가 1차식으로 표현될 것
- 통계: 독립 변수에 대한 결과가 1차식으로 표현될 것
- 기계: 수학적으로 변수를 x,y, 상수를 a,b라 할 때 y=ax+b가 만족할 때

> 어떤 시스템에서 입력에 대응하는 출력이 나온다는 의미, ‘원인(입력)과 효과(결과)간의 비례(직선) 특성’


선형성을 가진다 = 예측이 가능하다 

## 2 대수 
‘대수(algebra)’란 대신할 대(代) + 셈수(數)가 결합한 것, 수를 대신하여 문자나 수학법칙으로 표현하는 것

y = 3x 에서 대수는 x,y  /3는 계수 

대수 = 산수

## 3 선형 대수  
- 선형 방정식을 풀기 위한 방법론 

- 선형성을 가지는 대수로 이루어진 방정식들의 해를 구하는 방법론 

- 선의 형상을 가진 것을 수가 아닌 문자나 수학법칙으로 표현해야 것

- 선형대수는 어떤 함수(Function, Mapping Operator, Transformation)가 선형 함수(Linear Function)일 때 그 성질을 배우는 것 

- 선형 대수는 벡터(Vector)와 행렬(Matrix)을 이용하여 표현되며, ​대표적인 선형 함수로는 
 - 정비례 함수(y=ax)
 - 미분
 - 적분

- 벡터(Vector)와 행렬(Matrix)를 배우는 학문

###### 백터와 행렬을 이용한 산수/산수와의 유사성
- 수의 닫힘 집합 = 벡터 공간 
- 절대값 = 행렬값(Determinant)
- 양수 = 양정치(Positive-definite Matrix)
 
# 선형대수학과 머신러닝 
- 머신러닝 = 데이터를 처리 = 방정식을 풀어 해를 구한다 = 방정식을 푸는 방법이 `선형대수`
 
###### 딥러닝을 위한 선형 대수 요약본 by [Ian Goodfellow](https://1drv.ms/b/s!AkdMyVHUt0bovVHUBxOQsaeKYnSo)
- Scalars/Vectors/Matrices/Tensors
- Matrix Transpose
- Matrix (Dot) Product 
- Identity Matrix 
- Systems of Equations 
- Solving Systems of Equations
- Matrix Inversion 
- Invertibility
- Norms
- Special Matrices and Vectors: Unit vector, Symmetric Matrix, Orthogonal matrix
- Eigendecomposition
- Eﬀect of Eigenvalues
- Singular Value Decomposition
- Moore-Penrose Pseudoinverse
- Computing the Pseudoinverse


######  Linear Algebra Review by [Andrew NG](https://1drv.ms/b/s!AkdMyVHUt0bovVKnpYOUAU7v194F)

###### [머신러닝 기초 - 선형 대수](https://opentutorials.org/module/2336/13156)
- Matrix란 무엇인가?
- Linearly independent
- Rank
- Vector space
- Subspace , ColumnSpace , NullSpace
- Orthogonality와 projection
- determinant
- eigen vector와 eigen value

###### Facebook 조언
(1) 가우스 소거법이 어떤 거구나
(2) 벡터 공간과 부벡터 공간에 대한 개념적 이해
(3) 선형변환, 선형독립, 선형결합, Projection 등에 대한 개념적 이해
(4) 행렬 판별식과 eigenvalue, eigenvector에 대한 개념적 이해
(5) Singular에 대한 개념적 이해

 
# 참고 강의 


|Learn Again|MIT강의|한양대|
|-|-|-|
|1, The Geometry of Linear Equations|note 1: Geometry of linear equations |1강 선형성 정의 및 1차 연립방정식의 의미|
|2, 소거법, 후방 대입법 그리고 소거 행렬|note 2: Elimination with Matrices|1차 연립방정식과 가우스소거법| 
|3, 행렬곱셉(Matrix multiplication), 역행렬(Inverse matrix) 그리고 Gauss-Jordan|note 3: Multiplication and Inverse Matrices|4강 역행렬과 전치행렬|
|4, LU Decomposition(분해)|note 4: Factorization into A = LU|3강 LU 분할|
|5 - (1) 치환행렬(Permutations), 전치(Transposes) 그리고 대칭 행렬(Symmetric Matrix)|note 5: Transposes, permutations, space R^n| 4강 역행렬과 전치행렬|
|5 - (2) 벡터 공간(Vector Spaces), 부분 공간(Sub Spaces) |note 5: Transposes, permutations, space R^n|5강 벡터공간과 열벡터공간|


|Prezi정리|http://prezi.com/eidhydrvbwmp/?utm_campaign=share&utm_medium=copy&rc=ex0share|
|-|-|

###### 라온피플 [수학포기 금지](https://m.blog.naver.com/laonple/220925319311)
- <del>[Intro](https://m.blog.naver.com/laonple/220925319311)</del>
- <del>[선형대수 정의](https://m.blog.naver.com/laonple/220930613080)</del>
- [백터 탐구 생활](https://m.blog.naver.com/laonple/220949928793)

 




###### [Diamond Shore](http://blog.naver.com/dydrogud22)

  
###### Lear Again 블로그 
- 1, The Geometry of Linear Equations (1)
- 1, The Geometry of Linear Equations (2)
- 2, 소거법, 후방 대입법 그리고 소거 행렬
- 3, 행렬곱셉(Matrix multiplication), 역행렬(Inverse matrix) 그리고 Gauss-Jordan
- 4, [LU Decomposition(분해)](http://twlab.tistory.com/entry/Linear-Algebra-Lecture-4-%ED%96%89%EB%A0%AC-%EB%B6%84%ED%95%B4Factorization-ALU)
- 5 - (1) 치환행렬(Permutations), 전치(Transposes) 그리고 대칭 행렬(Symmetric Matrix)
- 5 - (2) 벡터 공간(Vector Spaces), 부분 공간(Sub Spaces)
- 6 Column Space와 영공간(Null Space)
- 7 Null Space계산 알고리즘. Ax=0과 Pivot variable 그리고 Free variable
- 8 선형방정식 Ax=b의 완전해(complete solution)와 Rank
- 9 선형 독립(Linear independence), Span, 기저(Basis) 그리고 차원(Dimension)
- 10 네 개의 주요 부분 공간(Fundamental subspaces)
- 11-(1) 행렬 공간(Matrix Spaces)
- 11-(2) Rank 1행렬 (Rank 1 Matrix)
- 12 그래프와 네트워크(Graph and Network), 근접 행렬(Incidence Matrices)
- 14 직교 벡터(Orthogonal Vector)와 부분 공간(Subspace)
- 15-(1) 해가 존재하지 않는 선형연립방정식(Ax=b)의 해 (overdetermined case)
- 15-(2) 투영행렬(Projection matrix)과 부분 공간(subspaces)
- 16 투영행렬(Projection matrix)과 최소자승법(Least Square method)
- 17-(1) 직교행렬(Orthogonal Matrices)과 그람 슈미트 과정(Gram-Schmidt Process)
- 17-(2) 직교행렬(Orthogonal Matrices)과 그람 슈미트 과정(Gram-Schmidt Process)
- 18 행렬식의 특성(Properties of Determinants)
- 19 행렬식(Determinant)의 계산 방법과 여인수(Cofactor)
- 20-(1) 행렬식(Determinant)과 역행렬(Inverse Matrix), 그리고 크래머 공식(Cramer's Rule)
- 20-(2) 행렬식(Determinant)의 기하학적 해석(Geometrical Analysis)
- 21-(1) 고유값(eigenvalues)과 고유 벡터(eigenvectors)
- 21-(2) 고유값(eigenvalues)과 고유 벡터(eigenvectors)


##### [MIT강좌 (2005)](http://judis.me/wordpress/2015/09/30/%EC%84%A0%ED%98%95%EB%8C%80%EC%88%98-note-1-geometry-of-linear-equations/)

- 선형대수 note 1: Geometry of linear equations (9/30/2015)
- 선형대수 note 2: Elimination with Matrices (9/30/2015)
- 선형대수 note 3: Multiplication and Inverse Matrices (9/30/2015)
- 선형대수 note 4: Factorization into A = LU (9/30/2015)
- 선형대수 note 5: Transposes, permutations, space R^n (9/30/2015)
- 선형대수 note 6: Column space and nullspace (10/2/2015)
- 선형대수 note 7: Solving Ax = 0 pivot variables, special solutions (10/2/2015)
- 선형대수 note 8: Solving Ax = b row reduced form R (10/2/2015)
- 선형대수 note 9: Independence, basis, and dimension (10/2/2015)
- 선형대수 note 10: The four fundamental subspaces (10/3/2015)
- 선형대수 note 11: Matrix spaces; rank 1; small world graphs (10/4/2015)
- 선형대수 note 14: Orthogonal vectors and subspaces (10/4/2015)
- 선형대수 note 15: Projections onto subspaces (10/4/2015)
- 선형대수 note 16: Projection matrices and least squares (10/6/2015)
- 선형대수 note 17: Orthogonal matrices and Gram-Schmidt (10/10/2015)
- 선형대수 note 18: Properties of determinants (10/10/2015)
- 선형대수 note 19: Determinant formulas and cofactors (10/12/2015)
- 선형대수 note 20: Cramer’s rule, inverse matrix, and volume (10/13/2015)
- 선형대수 note 21: Eigenvalues and Eigenvectors (10/14/2015)
- 선형대수 note 22: Diagonalization and Powers of A (10/18/2015)
- 선형대수 note 23: Differential equations and exp(At) (12/23/2015)
- 선형대수 note 24: Markov matrices; fourier series (12/23/2015)
- 선형대수 note 25: Symmetric matrices and positive definiteness (12/23/2015)
- 선형대수 note 26: Complex matrices; fast fourier transform (12/23/2015)
- 선형대수 note 27: Positive definite matrices and minima (12/24/2015)
- 선형대수 note 28: Similar matrices and jordan form (12/24/2015)
- 선형대수 note 29: Singular value decomposition (12/25/2015)
- 선형대수 note 30: Linear Transformations and Their Matrices (12/26/2015)
- 선형대수 note 33: Left and Right Inverses; Pseudoinverse. (12/27/2015)




#### Linear Algebra and its application [[교재]](https://drive.google.com/file/d/0B6Ry8c3OoOuqcDN6TXQzWlF2V3M/view?usp=sharing)

- Chapter 1 MATRICES AND GAUSSIAN ELIMINATION
 - 1.1 Introduction 1 
 - 1.2 The Geometry of Linear Equations 3 
 - 1.3 An Example of Gaussian Elimination 11 
 - 1.4 Matrix Notation and Matrix Multiplication 19 
 - 1.5 Triangular Factors and Row Exchanges 32 
 - 1.6 Inverses and Transposes 45 
 - 1.7 Special Matrices and Applications 58 


- Chapter 2 VECTOR 69
 - 2.1 Vector Spaces and Subspaces 69 
 - 2.2 Solving Ax = 0 and Ax = b 77 
 - 2.3 Linear Independence, Basis, and Dimension 92 
 - 2.4 The Four Fundamental Subspaces 102 
 - 2.5 Graphs and Networks 114 
 - 2.6 Linear Transformations 125 


- Chapter 3 ORTHOGONALITY 141
 - 3.1 Orthogonal Vectors and Subspaces 141 
 - 3.2 Cosines and Projections onto Lines 152 
 - 3.3 Projections and Least Squares 160 
 - 3.4 Orthogonal Bases and Gram-Schmidt 174 
 - 3.5 The Fast Fourier Transform 188 


- Chapter 4 DETERMINANTS 201
 - 4.1 Introduction 201 
 - 4.2 Properties of the Determinant 203 
 - 4.3 Formulas for the Determinant 210 
 - 4.4 Applications of Determinants 220 

- Chapter 5 EIGENVALUES AND EIGENVECTORS 233 
 - 5.1 Introduction 233 
 - 5.2 Diagonalization of a Matrix 245 
 - 5.3 Difference Equations and Powers Ak 254 
 - 5.4 Differential Equations and eAt 266 
 - 5.5 Complex Matrices 280 
 - 5.6 Similarity Transformations 293 

- Chapter 6 POSITIVE DEFINITE MATRICES 311
 - 6.1 Minima, Maxima, and Saddle Points 311 
 - 6.2 Tests -for Positive Definiteness 318 
 - 6.3 ` Singular Value Decomposition 331 
 - 6.4 Minimum Principles 339 
 - 6.5 The Finite-Element Method 346

- Chapter 7 COMPUTATIONS WITH MATRICES 351
 - 7.1 Introduction 351 
 - 7.2 Matrix Number 352 
 - 7.3 Computation of Eigenvalues 359 
 - 7.4 Iterative Methods for Ax = b 367

- Chapter 8 LINEAR PROGRAMMING AND GAME THEORY 377
 - 8.1 Linear Inequalities 377 
 - 8.2 The Simplex Method 382 
 - 8.3 The Dual Problem 392 
 - 8.4 Network Models 401 
 - 8.5 Game Theory 408



 
###### [한양대 이상화 교수 강좌](https://www.youtube.com/playlist?list=PLSN_PltQeOyjDGSghAf92VhdMBeaLZWR3)  [[강의자료]](http://www.kocw.net/home/search/kemView.do?kemId=977757)

- 선형대수 1강 선형성 정의 및 1차 연립방정식의 의미
- 선형대수 2강 1차 연립방정식과 가우스소거법
- 선형대수 3강 LU 분할
- 선형대수 4강 역행렬과 전치행렬
- 선형대수 5강 벡터공간과 열벡터공간
- 선형대수 6강 영벡터공간과 해집합
- 선형대수 7강 벡터의 선형독립과 기저벡터
- 선형대수 8강 벡터공간의 차원과 4가지 부벡터공간
- 선형대수 9강 선형변환과 행렬
- 선형대수 10강 벡터의 직교성과 직선투영
- 선형대수 11강 벡터투영과 최소제곱법
- 선형대수 12강 1차연립방정식 풀이와 직교벡터 구하기
- 선형대수 13강 일반최소제곱법과 QR 분할
- 선형대수 14강 함수 공간
- 선형대수 15강 행렬의 판별식
- 선형대수 16강 판별식의 공식
- 선형대수 17강 판별식의 응용
- 선형대수 18강 고유값과 고유벡터 및 대각화
- 선형대수 19강 차분방정식과 고유값
- 선형대수 20강 동질최소제곱법의 해와 마르코프 행렬
- 선형대수 21강 연립미분방정식과 행렬
- 선형대수 22강 복소행렬과 에르미트 행렬
- 선형대수 23강 특이값 분할 (SVD)



###### 칸 아카데미 [선형대수](https://www.khanacademy.org/math/linear-algebra)
Vectors and spaces
- Vectors
- Linear combinations and spans
- Linear dependence and independence
- Subspaces and the basis for a subspace
- Vector dot and cross products
- Matrices for solving systems by elimination
- Null space and column space

Matrix transformations
- Functions and linear transformations
- Linear transformation examples
- Transformations and matrix multiplication
- Inverse functions and transformations
- Finding inverses and determinants
- More determinant depth
- Transpose of a matrix

Alternate coordinate systems (bases)
- Orthogonal complements
- Orthogonal projections
- Change of basis
- Orthonormal bases and the Gram-Schmidt process
- Eigen-everything


참고 : [High school statistics](https://www.khanacademy.org/math/probability)