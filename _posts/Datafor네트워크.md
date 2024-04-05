# 복잡계 네트워크(Complex Network)

- 생명과학  예시: `단백질 네트워크`
- 사회  예시: `소셜 네트워크`
- 기술  예시: `물리적 네트워크`
- 자연현상 예시: `동역학`
    
**`복잡계 네트워크의 대표적 특징`**
- 척도없는 네트워크(scale-free)
    - 긴 꼬리를 가진 그래프 형태인 특정 노드에 더 많이 집중되어있는 것이 특징
    - 평균이상으로 많은 링크를 가진 허브(노드)가 탄생
    - 멱함수 법칙을 따름
- 소규모 네트워크(small-world)
    - 소수의 원거리 연결만 해도 전체네트워크의 평균 거리가 짧아진다.



# 중심성(Centrality)
- 중심성(Centrality)분석은 네트워크에서 가장 중요한 노드를 찾는 방법
    - `Degree Centrality(차수 중심성)`
        - ㅇㅇ
    - Closeness Centrality(인접 중심성)
    - Betweenness Centrality(매개 중심성)
    - PageRank





```python
import numpy as np
```


```python

```




    array([1, 2, 3])




```python

```

# 네트워크의 동역학 분석

## 개혁의 확산: *Diffusion of Innovation*
- 에버렛 로저스: 사람들이 신기술을 받아들이는 데에는 일정한 패턴존재

### 질병의 확산 모델: *The Spread of Disease, Epidemic*

- `SIR`모델: 전염병의 확산을 분석하는 가장 기본 모델
    - Susceptible: 감염될수 있는 개체
    - Infected: 감연된 개체
    - Recovered: 면역된 개체

- 정보의 케스케이드: `Information Cascade`
    - 101마리 원숭이 현상: 다수의 사람들이 동시에 같은 결정을 내리게 되는 현상
    - 소문의 확산, 가짜 뉴스의 확산 등을 모델링할떄
    - ICM: `independent Cascade` Model
        - 정보의 확산을 독립된 개체의 확률적 결정으로 판단

- 영향력 극대화 문제: `Influence Maximization` Problem(타겟 마케팅등 중요한 문제, 전염병 확산 막기에 중요한 문제)
    -   소셜 네트워크에서 영향력을 극대화할 수 있는 사람들의 집합을 찾는 문제
    - k가 주어졌을때, 가장 확산 범위가 높은 k개의 노드 선택

- 추천 알고리즘(Recommendation Algorithms)
    - missing link 찾기
    - 컨텐츠 기반, 협업 필터링




```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```
