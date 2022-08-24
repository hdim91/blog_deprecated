---
layout: post
title: DataFrame과 List
description: >
    R의 핵심 데이터 타입
excerpt_separator: <!--more-->
---

<!--more-->

DataFrame과 List를 설명하기에 앞서 벡터를 짤게 설명하고자 한다.

# 벡터와 데이터 타입

벡터는 아래와 같이 `c()`로 선언하며, 벡터 안의 요소들은 모두 같은 타입이여야 한다.
```r:
char_var <- c('A','B','C','D')
char_var
```
```r:
int_var <- c(1,2,3,4,5)
int_var
```
만약 숫자 벡터 안에 문자열 데이터가 하나라도 들어갈 경우, 모든 숫자들은 문자열로 변환되니 주의해야한다.
```r:
mix_var <- c(1,2,3,4,'D')
mix_var
```
위와 같이 벡터들을 생성하면, 그 다음에는 생성된 벡터들을 모아 DataFrame을 구축할 수 있게 된다.
# DataFrame

# List