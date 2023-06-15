# 상담, 소설 생성 서비스 (작성중)


## 1. 목표와 기능
### 1.1 목표
- 고민 상담을 할 수 있는 플랫폼
- 키워드, 장르만으로 소설을 작성할 수 있는 플랫폼
- 의료적 상담을 할 수 있는 플랫폼

### 1.2 기능
#### 1.2.1 고민상담챗봇
- 사용자는 챗봇을 통해 고민을 이야기할 수 있음
- 사용자의 입력을 받아 챗봇은 고민 해결 방법을 제시
#### 1.2.2 소설생성기
- 사용자는 키워드, 장르, 글자수를 입력할 수 있음
- 로딩 시간 후 소설 생성
#### 1.2.3 의료비서챗봇
- 사용자는 챗봇을 통해 자신의 증상을 입력하여 자가진단할 수 있음
- 사용자는 약물을 입력하여 약의 부작용이나 효능에 대한 정보를 받을 수 있음
- 챗봇은 사용자가 입력한 증상이나 약에 대한 정보를 제시

### 1.3 동기
#### 1.3.1 고민상담챗봇
- 누구나 쉬운 접근으로 고민을 말할 수 있는 대나무숲 같은 공간을 만들고자 했음.
- ChatGpt의 고민 해결이 곁들여진다면, 사용자가 고민을 말하고 해결받을 수 있는 상담소가 만들어질 것 같아 제작하게 됨
#### 1.3.2 소설생성기
- 책을 읽고자 하지만, 너무 긴 책의 분량이 무겁게 다가오는 사용자를 위함.
- 자신이 원하는 키워드, 장르가 단편의 소설이 될 수 있기에, 재미있게 접근하여 읽을 수 있음
- 작가는 소설을 작성하다가 아이디어가 떠오르지 않으면 참고할 수 있음
#### 1.3.3 의료비서챗봇
- 주변 사람이 아플 때나 본인이 아플 때 가장 먼저 하는 행동은 증상을 검색하여 아픈 이유를 찾아보는 행위
- 하지만 허황된 정보나 신뢰성 없는 정보가 많음
- 의료비서챗봇에 증상을 이야기하여 쉽고 빠르게 자가진단할 수 있도록 함
- 먹고있는 약의 정보도 하나하나 찾아보는게 아니라 의료비서챗봇을 통해 부작용과 유의사항을 쉽게 알 수 있도록 함


## 2. 개발 환경 및 배포 URL
### 2.1 개발 환경
- html, css, js
### 2.2 배포 URL
- https://won0201.github.io/Ormi_Project1/


## 3. 프로젝트 구조와 개발 일정
### 3.1 프로젝트 구조
```
|   index.html
|   README.md
|   
+---assets
|   +---css
|   |       style.css
|   |       
|   +---img
|   |       chating.jpg
|   |       logo.png
|   |       novel.jpg
|   |       room.jpg
|   |       service.png
|   |       stethoscope.jpg
|   |       
|   \---js
|           index.js
|           
+---Chatbot
|   |   index.html
|   |   
|   \---assets
|       +---css
|       |       darkmode.css
|       |       style.css
|       |       
|       +---img
|       |       bot.png
|       |       logo.png
|       |       logo2.png
|       |       moon.png
|       |       submit.png
|       |       sun.png
|       |       user.png
|       |       
|       \---js
|               darkmode.js
|               index.js
|               
+---Medical
|   |   index.html
|   |   
|   \---assets
|       |   style2.css
|       |   style3.css
|       |   
|       +---css
|       |       darkmode.css
|       |       style.css
|       |       
|       +---img
|       |       logo.png
|       |       moon.png
|       |       nurse.png
|       |       submit.png
|       |       sun.png
|       |       user.png
|       |       
|       \---js
|               darkmode.js
|               index.js
|               
\---Novel
    |   index.html
    |   
    \---assets
        +---css
        |       creator.css
        |       loading.css
        |       style.css
        |       
        +---html
        |       creator.html
        |       loading.html
        |       
        +---img
        |       book.png
        |       loading.png
        |       loading2.png
        |       logo.png
        |       
        \---js
                creator.js
                index.js
                loading.js
```
- 기본 페이지에서 3가지 페이지로 연결되는 구조

### 3.2 개발일정
- 2023.06.01 ~ 2023.06.15  

## 4. 세부 기능
### 4.1 전체 페이지
