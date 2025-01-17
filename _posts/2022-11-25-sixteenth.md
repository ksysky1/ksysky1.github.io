---
layout: post
title: 프로그래밍 언어론 - 영역과 수명 관련 용어 정리
tags: 프로그래밍언어론
date: 2022-11-25
---
## 프로그래밍언어론 - 용어 정리
1. 자유변수(free variable)   
자유변수는 현재 블록에서 선언되지 않고 사용되는 변수이다.   
전역변수들은 어떤 블록에서 선언되지 않고도 사용될 수 있으므로 자유변수이다.


2. 이명(aliasing)   
이명은 어떤 변수의 값을 변경할 때 다른 변수의 값까지 변경하게 되는 현상을 의미한다.   
기억장소를 공유하는 call by reference, call by name에서 한 변수의 값을 변경할 때 다른 변수의 값도 변하는 경우를 예로 들 수 있다.


3. 연산자의 중복 정의(overloading)  
연산자의 중복 정의는 매개변수에 따라 연산자의 의미가 달라지는 것이다.  
피연산자의 자료형에 따라 의미가 달라진다.  
예를 들어 Ada로 A := B * C를 작성했다고 할 때, B, C가 MATRIX형이면 함수 정의대로 수행되고, integer형이면 정수 곱셈을 수행하고, real형이면 실수 곱셈을 수행한다. 
  

4. 영역 구멍(hole-in-scope)  
영역 구멍은 내포된 블록 사이에 동일 지역 변수를 선언하면 바깥 블록의 지역변수는 내부 블록 구간에서 사용할 수 없는 현상을 의미한다.   
예를 들어 B블록을 내포하고 있는 A블록이 있다고 가정하고, A블록에 변수 a가 있고 B블록에도 변수 a가 있다고 가정한다.   
이 경우에 A블록에 있는 변수 a에 대해 영역 구멍 상태가 된다.
