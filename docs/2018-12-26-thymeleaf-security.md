---
layout: post
title: Database Setting
date: 2018-12-25 08:48:00
categories: TIL
tag: Spring, Boot, 2.0
---
# 2018-12-26

## 1. thymeleaf

### webjars

gradle 이용해서 jquery, bootstrap 버전 관리 하자  
현제 있는 버전중에 최신 버전설정을 해서 사용 하자

### 정적 자원 위치 4곳

${PROJECT_HOME}/src/main/resources 하위 폴더
- public/public.html
- META-INF/resources/meta.html
- resources/resoures.html
- static/static.html

### th:

- [thymeleaf (server-side template engine) 사용법 정리 - 1](http://cyberx.tistory.com/132)
- [thymeleaf (server-side template engine) 사용법 정리 - 2](http://cyberx.tistory.com/160)

## 2. security

[thymeleafexamples-springsecurity 예제](https://github.com/thymeleaf/thymeleafexamples-springsecurity)

### sec:

sec tag 를 이용해서 권한 관리

### JdbcUserDetailsManager

DB 연동 해서 로그인

### 암호화 해보기

### 참조
- [Security 번역자료](https://github.com/ssosso/Docs-Reference-Translation/tree/master/Spring-Security-Reference)
- [Security 다양한 Sample](https://www.programcreek.com/java-api-examples/index.php?api=org.springframework.security.provisioning.JdbcUserDetailsManager)
- [Security 5.0 변경점](https://java.ihoney.pe.kr/tag/Security)
- [JdbcUserDetailsManager](https://stackoverflow.com/questions/16319037/using-jdbcuserdetailsmanager-vs-own-userdetailsservice)
