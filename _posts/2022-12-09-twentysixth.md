---
layout: post
title: 유니티 - 벡터
tags: 유니티, 벡터
date: 2022-12-09
---
## 유니티 벡터
유니티에는 Vector2와 Vector3, Vector4가 있음.  
Vector2는 x,y 좌표를 가짐.(2차원)  
Vector3는 x,y,z 좌표를 가짐.(3차원)  
Vector4는 x,y,z,w 좌표를 가짐.(4차원)  
Vector를 이용해서 단순 사칙연산과 거리 계산, 정규화 등을 할 수 있음. 
```
 Vector3 v = new Vector3(10,10,10); 
 transform.position = v;
```
이와 같은 방식으로 사용하면 10, 10, 10 위치로 이동함.  
참고) Translate() 메소드는 벡터값만큼 이동함.  
벡터 생성후 transform.Translate(vec); 과 같이 쓰면 10, 10, 10 만큼 이동함.
position이외에도 rotation과 scale도 같은 방식으로 사용 가능.
