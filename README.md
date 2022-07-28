# intellij_todoList
#### 리스트에 추가,삭제,검색하는 것을 springboot 사용하여 만들기

## 목차
1. [개발 환경](#1_개발-환경)
2. [명세](#2_명세)
3. [실행 결과](#3_실행-결과)
---
## 1_개발 환경
- Java11
- intellij
- Springboot
- JPA
- Postman
---
## 2_명세
|메소드 명|기능명세|endPoint|request|
|:--:|:--:|:--:|:--:|
|create|POST/아이템 추가|/|{"title":"아이템 입력"}|
|readOne|GET/모든 아이템 읽기|/{id}||
|readAll|GET/트정 아이템 읽기|/||
|deleteOne|DELETE/특정 아이템 삭제|/{id}||
|deleteAll|DELETE/모든 아이템 삭제|/||
|update|PATCH/특정 아이템 수정|/{id}|{"title":"수정값 입력"}|
---
## 3_실행 결과
#### 3.1) ceate
![create_post방식](https://user-images.githubusercontent.com/82923905/180906268-144a4052-b8f3-4f9b-83c4-06a795da03a3.PNG)
#### 3.2) readAll
![readAll_GET방식](https://user-images.githubusercontent.com/82923905/180906309-aff2c1e3-db39-49f5-8c30-ce193549df1f.PNG)
#### 3.3) readOne
![read_GET방식](https://user-images.githubusercontent.com/82923905/180906340-32516993-9331-4fdf-8c06-a1a06fcd7c77.PNG)
#### 3.4) deleteOne
![delete_delete방식](https://user-images.githubusercontent.com/82923905/180906388-148688b2-650b-440d-9af6-a5570bf8a7ac.PNG)
#### 3.5) update
![uodate](https://user-images.githubusercontent.com/82923905/180906609-6193250c-f72e-4447-93b0-0056faed8003.PNG)
#### 3.6) deleteAll


