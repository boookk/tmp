---
layout: post
title: Kotlin SpannableString
date: 2021-10-27 00:00:00 +0300
tags: [Kotlin, Learn]
---

## 💙️ Kotlin TextView

<br>
<center><img src="/assets/img/kotlin/kotlin_textview.png" alt="Drawing"/></center>
<br>

### ❓ SpannableString

SpannableString class는 텍스트를 출력할 때 텍스트 일부의 색상, 크기, 스타일 등을 변경할 때 사용한다.

아래는 현재 진행하고 있는 프로젝트에 적용한 예시이다.

TextView의 내용 중 오른쪽 디데이에 포인트를 주고 싶어서 SpannableString class를 사용하였다.

<script src="https://gist.github.com/boookk/ccd17b48f85bb00ace20f59a9ce0bd24.js"></script>

```kotlin
binding.tvRange.setText(setRange(strDate, "+$day"), TextView.BufferType.SPANNABLE)
```
