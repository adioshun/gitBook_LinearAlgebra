# 행렬식(Determinant)의 계산 방법


## 1. Product of all pivots from G.E
- 가우스 소거법으로 U로 바꾸어 대각선의 Pivot을 곱하여 계산
- (행교환 없을 경우) A = LDU에서 $$\rightarrow$$ det a = det L x det D x det U $$\rightarrow$$ 1 x $$ \prod_{i=1}^n P_i $$ x 1  
- (행교환 있을 경우)PA = LDU $$\rightarrow$$ det p = $$\pm 1 $$
     

## 2. 주요 3성질 이용



### 2.1 2x2행렬
$$\begin{bmatrix}
a & b \\
c & d \end
{bmatrix}$$ = ad -bc

### 2.2 3x3 행렬

Big Formula

[한양대 Youtube 강의: 16강 판별식의 공식](https://youtu.be/xjoo5Ik0LQA?t=30m19s)





   
    



---

# 여인수(cofactor)
Big formula를 분할하는 방법