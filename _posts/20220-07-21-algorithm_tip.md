---
title: 알고리즘 팁 정리
tags: 
    - algorithm
    - study
categories: 
    - algorithm
comments: true
---

1. 반복문을 돌때, 시간 절약을 위해 break를 쓰면 오히려 알수없는 오류에 빠질 수 있음...! 특히 dp!
2. 재귀를 통해 중첩for문을 돌 때, dp랑 헷갈리지말자. 재귀를 이용해 중첩 for문을 줄인거면, 최종 계산을 가장 깊을때 해야함. dp는 반대임!
3. 순열, 조합 등을 계산할때, itertools를 사용하자.