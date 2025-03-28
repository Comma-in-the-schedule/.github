# Web Application - 스케줄 속 쉼표
<p align="center">
  <img width="400" alt="스크린샷 2025-03-22 오후 6 31 39" src="https://github.com/user-attachments/assets/3f05c64b-c140-443a-b1c0-1d1e6d64582b" />

<p align="center">
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot"/>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask"/>
</p>

## 🚀 프로젝트 개요

### 💡 기획 배경

현대인의 일정은 바쁘고 촘촘하게 구성되어 있어, 여유 시간이 생겨도 이를 효율적으로 활용하기란 쉽지 않습니다. 특히, 짧은 여유 시간에 취향에 맞는 여가 활동을 직접 찾는 것은 번거롭고 어려운 일입니다. 이러한 문제에서 출발하여, 바쁜 일상 속 ‘쉼’의 순간을 제안하고자 본 프로젝트를 기획하였습니다.

### 🧠 서비스 개요

“스케줄 속 쉼표”는 **AI 기반의 개인 맞춤형 여가 추천 기능을 탑재한 일정 관리 앱**입니다. 사용자가 입력한 정보를 분석하고,

- **위치 정보**
- **개인 취향 및 관심사**
- **취미 활동 정보**

를 바탕으로 사용자에게 가장 적합한 여가 활동을 자동으로 추천합니다.

### ⚙️ 주요 기능

- 기본 일정 관리 기능 (일정 등록, 수정, 삭제)
- **‘쉼표 버튼’ 클릭 시**, 여유 시간 탐색 및 추천 기능 활성화
- 관심사에 기반한 여가 콘텐츠 추천 예시:
  -  영화 감상을 좋아하는 사용자 → 해당 시간에 상영 중인 드라마 장르 영화 추천
  -  특정 문화(예: 중국 문화)에 관심 있는 사용자 → 관련 전시회 정보 제공
  -  쇼핑을 선호하는 사용자 → 세일 중인 매장 정보 제공

## 📂 3가지 서버 

| 서버 | 설명 | 레포지토리 링크 |
|------------|--------|----------------|
| **Front-End 서버** | Flutter 기반 모바일 앱, 사용자 일정 입력 및 추천 결과 UI 제공 | [🔗 GitHub](https://github.com/Comma-in-the-schedule/front_end_repo) |
| **Back-End 서버** | Spring Boot 기반, 일정 및 회원 정보 처리, AI 서버 연동 | [🔗 GitHub](https://github.com/Comma-in-the-schedule/main_server_repo) |
| **AI 서버** | Flask 기반, 사용자 데이터 기반 여가 추천 AI 모델 제공 | [🔗 GitHub](https://github.com/Comma-in-the-schedule/ai_server_repo) |
---

## 🖥️ 서비스 화면

| 로딩 화면 | 로그인 화면 | 회원가입 화면 |
|:--:|:--:|:--:|
| <img width="200" src="https://github.com/user-attachments/assets/3db31050-aa64-4177-acd7-79cd764dfa31" /> | <img width="200" src="https://github.com/user-attachments/assets/f03de874-5ab2-4aea-889a-359699ade1fd" /> | <img width="200" src="https://github.com/user-attachments/assets/69b88a4d-1811-4a8b-a157-0603cb458e0c" /> |


| 설문 조사 화면 | 메인 페이지 | 상세 페이지 |
|:--:|:--:|:--:|
| <img width="200" src="https://github.com/user-attachments/assets/5a5df607-be83-4bdb-a6fe-03eca8ca03c5" /> | <img width="200" src="https://github.com/user-attachments/assets/26013d45-18d1-49c2-bf50-7c78d0577a0f" /> | <img width="200" src="https://github.com/user-attachments/assets/7fb3132c-9d32-497b-9bf7-9c6aedb54701" /> |


## 🎥 시연 영상

<video src="https://github.com/user-attachments/assets/af3c217a-4637-4357-aedd-6edb72f741d9" width="600" controls></video>

