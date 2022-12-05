---
layout: post
title: 자바스크립트 문법 - 클래스
tags: 클래스, 자바스크립트
date: 2022-12-05
---
## 자바스크립트 
### 자바스크립트 클래스 문법
```
class 클래스명 {
    구성요소(){
        ...
    }
}
```
예시
```
class Student {    
    constructor(name, old, major){
        this.name = name;
        this.old = old;
        this.major = major;
    }
}
```

클래스 사용 예시
```
let student1 = new Student("judy", 23, "간호학과");
let student2 = new Student("rose", 20, "국어국문학과");
```
