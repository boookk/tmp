---
layout: post
title: "트리 자료구조"
date: 2022-02-25 00:00:00 +0300
img: python/python.PNG
tags: [Algorithm, Python, Learn]
---

# 📚 Tree

계층적인 구조를 표현할 때 사용하는 자료구조


### <mark style='background-color: #fff5b1'> 트리 관련 용어 </mark>
| 명칭 | 의미 |
|:----:|:----:|
| 루트 노드 (root node) | 부모가 없는 최상위 노드 |
| 단말 노드 (leaf node) | 자식이 없는 노드 |
| 크기 (size) | 트리에 포함된 모든 노드의 개수 |
| 깊이 (depth) | 루트 노드부터의 거리 |
| 높이 (height) | 깊이 중 최댓값 |
| 차수 (degree) | 각 노드의 (자식 방향) 간선 개수 |


<br><br>


# 📚 이진 탐색 트리
- 이진 탐색이 동작할 수 있도록 고안된 효율적인 탐색이 가능한 자료구조의 일종
- 왼쪽 자식 노드  < 부모 노드 < 오른쪽 자식 노드


<br><br>


# 📚 트리의 순회
- 트리 자료구조에 포함된 노드를 특정한 방법으로 한 번씩 방문하는 방법

### <mark style='background-color: #fff5b1'> 전위 순회 </mark> (Pre-order traverse)
- 루트를 먼저 방문한다.

<br>

### <mark style='background-color: #fff5b1'> 중위 순회 </mark> (In-order traverse)
- 왼쪽 자식을 방문한 뒤에 루트를 방문한다.

<br>

### <mark style='background-color: #fff5b1'> 후위 순회 </mark> (Post-order traverse)
- 오른쪽 자식을 방문한 뒤에 루트를 방문한다.

<br><br>
