# 🧳 같이가자 : 단체 여행 AI 플래너
🖥️ 배포 주소 : https://gachi-gaja.vercel.app/ <br/>
단체 여행 참여자의 성향 및 의견을 취합해 AI 기반 최적의 여행 계획을 제시하는 단체 여행 AI 플래너 웹 서비스

## ✨ 주요 기능
### 여행 모임 관리
- 여행지, 여행 일자, 예산 등을 입력해 여행 모임 생성 <br/>
- 모임 초대 링크 생성 <br/>
- 모임 초대 링크로 여행 모임 참여
### 참여자 의견 취합
- 여행 스타일, 식습관, 기타 요구 사항 등 참여자 의견 입력 및 수정
### AI 기반 여행 계획 후보 생성 및 투표
- Gemini로 참여자 의견을 취합해 2개의 여행 계획 후보 생성 및 생성 근거 제공 <br/>
- 참여자는 1개의 후보안에 투표해 다수결로 여행 계획 후보 결정
### AI 기반 여행 계획 생성 및 수정
- Gemini로 결정된 여행 게획 후보 기반 여행 계획 생성
- 일정 변경에 따라 여행 계획 수정

## 🛠️ 기술 스택
| 분야 | 사용 기술 |
|-|-|
| Frontend | ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) |
| Backend | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white) ![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white) |
| Databases | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) |
| AI | ![Gemini 2.5 Flash](https://img.shields.io/badge/Gemini_2.5_Flash-8E75B2?style=for-the-badge&logo=google&logoColor=white) |
| Release | ![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white) ![Google Cloud Platform](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white) |

## 🔎 시스템 아키텍처

## 🧑‍💻 담당 파트
- Project Manager & Backend Engineer
- ERD 설계
- Gemini 연동 및 프롬프트 작성
- 여행 계획 후보, 여행 계획 기능 구현

## ⬆️ 추후 개선 사항
### 기술적 측면
- AI 답변 속도 향상 <br/>
- AI 기반 여행 계획 후보 및 여행 계획 생성 로직 최적화 <br/>
### 기능적 측면
- 모임 공동 체크리스트 기능 구현 <br/>
- 숙소, 관광지 예약 바로가기 구현 <br/>
- 여행 공금 관리 기능 구현 <br/>
- 모이별 여행 사진 공유 공간 추가
