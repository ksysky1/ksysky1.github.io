---
layout: post
title: 유니티 - 중력과 반동(리지드바디 컴포넌트)
tags: 유니티, 중력, 반동, 리지드바디
date: 2022-12-07
---
## 유니티 중력과 반동
### 리지드바디 컴포넌트(Rigidbody component)
물체에 중력을 적용해야 공중에 있지 않고 아래로 떨어짐.
- 중력 적용하는 방법 
1. 중력을 적용할 물체를 선택한 후 Inspector창 아래쪽에 Add component 클릭
2. Physics - Rigidbody 클릭  
게임 뷰에서 Maximize On Play 선택 후 플레이 버튼을 누르면 물체에 중력이 적용된 것 확인 가능.
- 물체에 반동 적용하는 방법
1. 반동을 적용할 물체를 선택한 후 Inspector창 아래쪽에 Add component 클릭
2. Physics - Rigidbody 클릭
3. Project창 - Assets에서 마우스 우클릭 - Create - Physics Material 클릭
4. 반동효과 이름 정해서 입력
5. Insptctor창에서 속성 변경(Bounciness값 변경, Bounce Combine은 Maximum으로 변경)
6. 반동을 적용할 물체에 반동효과 드래그하기  
플레이 버튼 눌러 확인하기
