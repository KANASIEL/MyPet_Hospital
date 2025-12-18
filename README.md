# 🐾 MyPet_Hospital

![📅 개발 기간](https://img.shields.io/badge/개발%20기간-2025.10.13%20~%202025.10.20%20&%202025.11.13%20~%202025.11.20-blue?style=flat-square)
![👥 팀원 수](https://img.shields.io/badge/팀원-6명-green?style=flat-square)

<img width="744" height="228" alt="메인 로고/배너" src="https://github.com/user-attachments/assets/cf293a35-848c-4b31-90b7-c5151884357a" />

## 📖 프로젝트 소개
반려인을 위한 맞춤형 진료 및 미용 서비스를 제공하고,  
정보 공유와 소통이 가능한 **커뮤니티형 웹사이트**

### ⏰ 개발 기간
- 2025.10.13 ~ 10.20  
- 2025.11.13 ~ 11.20

### 👥 팀원 및 역할

| 이름   | 역할 | GitHub |
|--------|------|--------|
| 이현석 | 👑 **팀장** · 스프링 부트 포팅, 백엔드 구조 분리, 이미지 첨부, 서머노트 이미지·동영상 미리보기 기능 | GitHub |
| 정태규 | 🗄 **DB 설계·구현**, 멤버십 자동관리, 마이페이지, 관리자 페이지(예약 관리), Q&A 기능 강화 | GitHub |
| 김주현 | 🔐 소셜 로그인, 회원정보 추가 페이지, 통합 회원가입 DB 연동(공동), 반려동물 몸무게 기록·그래프 | GitHub |
| 김지호 | 🔐 소셜 로그인, 회원정보 추가 페이지, 통합 회원가입 DB 연동(공동) | GitHub |
| 채교준 | 🤖 DB 설계·구현, Gemini 기반 챗봇, 반려동물 비만도 계산기 | GitHub |
| 구현서 | 📧 이메일 인증, 아이디·비밀번호 찾기, 검색 자동완성, 자유게시판 CRUD·댓글 | GitHub |

## 🛠 기술 스택

| 카테고리 | 기술 |
|---------|------|
| 🖥 운영체제 | Windows 11 |
| 💻 언어 | Java |
| 🎨 프론트엔드 | JSP, JavaScrip, jQuery, CSS |
| ⚙ 백엔드 프레임워크 | Spring Boot |
| 🧩 ORM / DB 접근 | MyBatis |
| 🗄 데이터베이스 | Oracle |
| 🔐 인증 / 보안 | Spring Security, Kakao, Google, Naver |
| 🤖 AI / 외부 API | Google Gemini |
| 🧰 개발 도구 / IDE | IntelliJ, STS, VS Code |

## 🖼 주요 화면

<details>
<summary>🏠 메인 페이지</summary>

반려인을 위한 따뜻한 첫인상을 주는 랜딩 페이지로,  
✨ 서비스 소개 · 📅 빠른 예약 · 💬 커뮤니티 바로가기 제공

</details>

<details>
<summary>🔐 소셜 로그인 및 회원가입</summary>

Kakao · Google · Naver 소셜 로그인을 지원하며  
🧾 추가 정보 입력 후 통합 회원가입 가능

</details>

<details>
<summary>🤖 Gemini AI 챗봇 상담</summary>

Google Gemini API 기반 실시간 챗봇으로  
🐶 반려동물 건강 · 🥗 영양 상담 제공

</details>

<details>
<summary>⚖ 반려동물 비만도 계산기</summary>

사진 기반 체형 선택을 통해  
📊 반려동물 비만도 진단 및 건강 조언 제공

</details>

<details>
<summary>📈 몸무게 기록 및 그래프 시각화</summary>

마이페이지에서  
📝 몸무게 기록 · 📊 기간별 변화 그래프 제공

</details>

<details>
<summary>✍ 자유게시판 글쓰기 (서머노트)</summary>

🖼 이미지 · 🎥 동영상 첨부  
👀 미리보기 지원 게시글 작성 기능

</details>

<details>
<summary>👤 마이페이지 & 🛠 관리자 페이지</summary>

- 👤 회원 정보 관리
- 🐕 반려동물 정보 등록
- 📅 예약 내역 확인
- 🛠 관리자 예약·회원 관리

</details>

## 🐞 이슈 발생 및 해결

### 📌 이슈 개요
- 🚨 **발생 상황**: GitHub Pull Request 병합 과정
- 🌿 **관련 브랜치**: `feature/*` → `develop`
- ❗ **증상**: 동일 파일 동시 수정으로 Merge Conflict 발생

### 🔍 원인 분석
- 🧑‍💻 동일 파일·동일 라인을 여러 명이 수정
- 🔄 최신 `develop` 미반영 상태에서 작업
- 🗣 작업 범위 공유 부족

### 🛠 해결 방법
- 🔃 최신 브랜치 반영
  ```bash
  git pull origin develop
