---
layout: post
title: 유니티 오브젝트 요소 접근, 오브젝트 활성화/비활성화
tags: 유니티, 오브젝트
date: 2022-11-22
---

## 유니티 오브젝트 요소 접근
```
게임 오브젝트명.컴포넌트명.멤버명....  
```
위와 같은 방식으로 다른 오브젝트 요소에 접근함
ex) gameObject.GetComponent<Transform>().position.x
    gameObject.GetComponent<Rigidbody>().AddForce(1,0,0);

## 게임 오브젝트 활성화/비활성화 방법
게임오브젝트가 인스펙터창에 뜨도록 선택한 뒤, 오브젝트 이름 옆에 체크표시를 해제한다. - 비활성화   
게임오브젝트가 인스펙터창에 뜨도록 선택한 뒤, 오브젝트 이름 옆에 체크표시를 한다. - 활성화   
코드를 통해서 게임 오브젝트를 활성화/비활성화하는 방법은 다음과 같다.
```
gameObject.SetActive(true); // 활성화
gameObject.SetActive(false); // 비활성화
```
