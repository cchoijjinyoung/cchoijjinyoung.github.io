---
date: 2021-10-06
title: "[Java] BufferedReader와 BufferedWriter"
excerpt: "알고리즘을 공부하다 보니 Scanner보다 Buffer를 사용하는 것이 속도 면에서 훨씬 좋다고 들었다. 활용하기 위해 공부내용을 적어보자"
categories: 
    - Java
tags: 
    - [Java, Algorithm]
toc: true
toc_sticky: true
last_modified_at: 2021-10-07 
---

# BufferedReader 와 BufferedWriter (입/출력)
---
자바를 처음 공부하면 Scanner를 이용해 입력받는 것을 배운다.   
Scanner는 스페이스와 엔터를 경계로 인식하기 때문에 가공할 필요가 없어서 사용하기 매우 편리하다.   
반면에, BufferdReader는 엔터만 경계로 인식하고, 받은 데이터는 String으로 고정되기 때문에 데이터를 따로 가공해야 하는 경우가 많다.   
**그러나 속도 면에서 BufferedReader를 사용하는 것이 상대적으로 빠르다.**
데이터를 입력받으면 `Buffer`라는 데이터를 보관하는 임시적 영역에 보관했다가 개행문자가 나타나면 한번에 전송하기 때문이다.   
>Scanner는 놀이터의 흙을 옮길 때 삽질마다 이동하는 반면에,   
>**BufferedReader**는 `buffer`라는 수레에 담았다가 한 번에 가져간다고 생각하면 이해가 편하다.

# BufferedReader 사용방법
---
