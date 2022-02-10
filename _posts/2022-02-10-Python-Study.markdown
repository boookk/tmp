---
layout: post
title: "Python 최대 공약수, 최소 공배수"
date: 2022-02-10 00:00:00 +0300
img: python/python.PNG
tags: [Algorithm, Python, Learn]
---



# 📚 최대 공약수

### <mark style='background-color: #fff5b1'> 유클리드 호제법 </mark> 
- 두 자연수 A, B에 대하여 (A > B) A를 B로 나눈 나머지와 B의 최대 공약수는 A와 B의 최대 공약수와 같다.
```python
def gcd(a, b):
  if a % b == 0:
    return b
  else:
    return gcd(b, a % b)
```

<br><br>

# 📚 최소 공배수

### <mark style='background-color: #fff5b1'> 구현 </mark>
- 서로 다른 a, b의 곱을 a, b의 최대 공약수로 나눈다.
```python
def lcm(a, b):
  return a * b / gcd(a,b)
```


<br><br>


