---
layout: single
title:  "[tail]실시간 로그 보기 명령어"
categories: linux
tag: [linux, sample, blog]
toc: true
author_profile: false
sidebar:
    nav: "docs"
---

리눅스로 로그의 기록을 실시간으로 보려면 tail을 아래와 같이사용해야 한다.

※ **옵션**

- [-**f**] 파일의 **마지막 10라인 실시간으로 계속 출력**
- [-**F**] 파일변동시 **실시간 출력** & 특정**시간 지난 후** 파일 변동시 **새로운 파일 오픈**해서 출력
- [**n**] 파일의 **마지막부터 n만큼의 라인**을 출력
- [**+n**] 파일의 **첫번째부터 n번째 이후 라인**을 출력
- **옵션 생략 가능**

※ **실시간 로그 기록 보기 명령어
tail [-f] 파일명**
ex) test.log 파일 실시간으로 보기 : **tail -f test.log**

※ **로그 종료하기
Ctrl + C**

출처: [https://javaoop.tistory.com/60](https://javaoop.tistory.com/60)
