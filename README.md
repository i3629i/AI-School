# ai-school
양재
# 선형대수 정리
##    1. 선형변환
##    2. 고유값 고유벡터

# 선형 변환
선형변환? : 벡터에 행렬을 곱해 또 다른 벡터를 만드는 함수. , 하나의 벡터 공간에 또 다른 벡터 공간으로, 벡터의 특징을 유지한 채 변환하는 방법.
### 식1
A = 
$$ \begin{bmatrix}
-1 & 2 \\
1 & 1
\end{bmatrix}$
  b = $$
  \begin{bmatrix}
3 \\
2
\end{bmatrix}$

Ab = 
$ \begin{bmatrix}
1 \\
5
\end{bmatrix}$

### 식2
b의 표준기저 e 를 구하면
b = 3 $ \begin{bmatrix}
1 \\
0
\end{bmatrix}$ + 
2$ \begin{bmatrix}
0 \\
1
\end{bmatrix}$
= 3e.x + 2e.y

표준기저 e 를 이용해서 Ab구하기
표준기저란? X축 Y축 z축 처럼 일종의 '좌표계'를 정할 수 있는 벡터집합
b의 표준기저 : 
e.x = $ \begin{bmatrix}
1 \\
0
\end{bmatrix}$
e.y = $ \begin{bmatrix}
0 \\
1
\end{bmatrix}$



### 식3
A를 두개의 열벡터로 나누면 
e1 = $ \begin{bmatrix}
-1 \\
1
\end{bmatrix}$
e2 = $ \begin{bmatrix}
2 \\
1
\end{bmatrix}$


Ab = $ \begin{bmatrix}
-1 & 2 \\
1 & 1
\end{bmatrix}$
{3$ \begin{bmatrix}
1 \\
0
\end{bmatrix}$
+
2$ \begin{bmatrix}
0 \\
1
\end{bmatrix}$}


2x2 2x1 행렬곱 생략

= 3$ \begin{bmatrix}
-1 \\
1
\end{bmatrix}$
+
2$ \begin{bmatrix}
2 \\
1
\end{bmatrix}$
=3e1 + 2e2 = $ \begin{bmatrix}
1 \\
5
\end{bmatrix}$

### 수학적 의미
### 식2의 의미 : e.x방향으로 3만큼 e.y방향으로 2만큼 움직인 지점

### 식3의 의미 : 식2와 같은 방법으로 e1의 3만큼 e2의 2만큼 움직인 지점 은 같은 스칼라배로 움직였다는 것을 알 수 있다.  이에 따라 행렬의 계산은 벡터를 회전하거나 확대, 또는 축소시킨 것과 같은 효과를 나타냄

### 결론 선형 변환이라는 말은 어떤 벡터값에 행렬A를 곱한다는 것은 그 벡터를 다른 벡터공간으로 변환하고자회전,확대, 축소 한다는 것과 같음
