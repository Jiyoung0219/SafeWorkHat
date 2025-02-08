# SafeWorkHat(SW^)
---

**사전 개발 기간**: 2025.01.10~2025.01.20(MVP구현) 

**개발 기간**: 2025.01.21~2025.01.22(해커톤 형식)

-   아이디어 및 모델 구상: 01.10 ~ 01.12
-   구현: 01.13 ~ 01.22

**제작 인원**: 4명

---

### **1️⃣ 프로젝트 개요**

**1-1 팀/프로젝트 이름**

-   **팀 이름**: 헌희석이지영
    -   팀원들 이름을 조합한 팀명이다. 
-   **프로젝트 이름**: SafeWorkHat(SW^) 


**1-2 제안 배경/프로젝트 소개**

- 열악한 환경 속에서도 화재 진압과 인명 구조를 목표로 항상 최선을 다해주시는 소방관분들에게 조금이나마 도움이 되고 싶다는 생각을 가지고 있었고,
최근 개봉한 영화 '소방관'을 계기로 위의 생각을 실행에 옮기고자 하였다.   
소방관의 안전도 보장하며 정확하고 신속한 구조 작업을 구축하고자 개발하게 되었다.
더하여, 화재 발생 시에 화재를 자동으로 감지해 신고하는 기능까지 구현하고자 하였다. 

- 화재 시 CCTV를 통한 화재 인식 및 신고 기능 구현, 구조 시 CV를 통해 
구조자 감지 및 환경 파악 


**1-3 기술 스택**

-   인공지능: YOLOv8, OPENCV, FLASK
-   언어: python
-   하드웨어: Arduino, ipwebcam
-   데이터베이스: MongoDB

**1-4 프로젝트 주요 기능**

| 구분 | 기능 | 설명 | 인원수/담당자 |
| --- | --- | --- | --- |
| 1 | cctv파트 cv |  cctv에 들어갈 yolo모델 훈련 | 1/강지영 |
| 2 |  근무모파트 cv | 근무모에 들어갈 yolo모델 훈련 | 1/현희섭 |
| 3 |  아두이노 | 아두이노 카메라로 객체 인식, 아두이노 와이파이 FLASK 웹 서버의 문자열 파싱 | 1/이헌성       |
| 4 | 데이터베이스 | 데이터 실시간 시각화 | 2/석민정, 현희섭       |




* * *

### **2️⃣ 프로젝트 수행 내용**

**2-1 프로젝트 수행 일정**
![image](https://github.com/user-attachments/assets/f4dbb274-f815-4a23-8676-fa06d9b39a4e)

**2-2 프로젝트 구조도**
![image](https://github.com/user-attachments/assets/336cbf75-b4c3-4b01-a654-4c93b759d5d6)
CCTV의 화재 감지 및 신고   
근무모의 균열 및 신체 탐지
