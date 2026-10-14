# 👋 Transient-Onlooker

<div align="center">

<img width="100%" alt="english_black" src="https://github.com/user-attachments/assets/e1341020-7916-41a0-bead-fe3ca6030ef8" />

<br/>

### 시스템 설계 · 과학 모델링 · 웹 도구 개발

TypeScript, Python, Kotlin을 중심으로  
과학 모델링과 실사용 도구를 만드는 개발자입니다.

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Transient-Onlooker)
[![Projects](https://img.shields.io/badge/🎯%20Projects-111111?style=for-the-badge)](#-대표-프로젝트)
[![Contact](https://img.shields.io/badge/Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](#-연결)

</div>

---

## 🚀 About Me

항공우주공학과 시스템 설계에 관심이 많은 개발자입니다.

수학·과학 모델을 코드로 구현하고, 실제로 사용할 수 있는 앱과 자동화 도구로 확장하는 데 집중하고 있습니다.  
학습 기록·통계 웹서비스, 전염병 확산 및 로켓 비행 시뮬레이션, OMR 자동화, 3D 제작 도구, 개인 Capture & Workspace, AI 개발 도구 기여, 안드로이드 앱 등 다양한 아이디어를 직접 프로젝트로 구체화하고 있습니다.

---

## 🎯 대표 프로젝트

### 1. [ypt-web](https://github.com/Transient-Onlooker/ypt-web)

열품타의 공부 타이머·기록·그룹을 PC와 모바일 웹에서 다루는 비공식 클라이언트입니다.  
React 프론트엔드와 Cloudflare Workers API를 분리하고, D1을 이용해 인증 세션·타이머 상태·조회 캐시를 관리합니다.

완료 기록과 실행 중 예상 시간을 구분하고, 중복 요청·응답 실패 후 상태 복구를 고려해 설계했습니다. 7·14·30일 학습 통계와 뽀모도로·계획 기능도 제공합니다.

[Live Demo](https://ypt.mcv.kr/)

**주요 특징**

- React + TypeScript + Vite 기반 반응형 웹 클라이언트
- Cloudflare Workers API 중계와 D1 기반 인증 세션·타이머 상태 관리
- 타이머 상태 재확인, 중복 요청 제어와 불확실한 결과의 안전한 처리
- 일반 타이머·뽀모도로, 하루 계획 및 그룹 멤버 상태 동기화
- 날짜·과목별 기록과 7·14·30일 통계, CSV 내보내기
- D1 캐시·강제 새로고침, 미확인 기록과 실제 0시간 구분
- 라이트/OLED 다크 테마 및 WCAG 2.2 AA 대비 회귀 검사

**Tech**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare%20Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white)
![Cloudflare D1](https://img.shields.io/badge/Cloudflare%20D1-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

### 2. [openflight4and](https://github.com/Transient-Onlooker/openflight4and)

출발지·목적지와 예상 비행시간을 선택해 가상 비행을 진행하는 Android 집중 앱입니다.  
단순 카운트다운 대신 **공항 선택 → 좌석·보딩패스 → 지도 기반 비행 → 도착 기록**으로 이어지는 경험을 구현했습니다.

Kotlin·Jetpack Compose로 UI를 구성하고 Firebase 인증, Google Maps/Maps 3D, 비행권·보상 시스템과 집중 잠금을 결합했습니다.

**주요 특징**

- Kotlin + Jetpack Compose 기반 Android 네이티브 앱
- 대권 거리 기반 예상 비행시간과 2D·2.5D·3D 지도 표시
- 좌석 선택·보딩패스·비행권·출석 및 광고 보상 흐름
- 사용 정보 접근·오버레이 기반 단계별 집중 잠금
- Firebase Auth, Google Sign-In 및 Cloudflare Worker/D1 연동
- Room·DataStore 기반 로컬 상태 관리
- GitHub Actions 기반 CI 빌드 흐름

**Tech**

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white)
![Cloudflare D1](https://img.shields.io/badge/Cloudflare%20D1-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Google Maps](https://img.shields.io/badge/Google%20Maps-4285F4?style=flat-square&logo=googlemaps&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle%20KTS-02303A?style=flat-square&logo=gradle&logoColor=white)

---

### 3. [NoteRelay](https://github.com/Transient-Onlooker/tg-note-agent-web) · [tg-note-agent](https://github.com/Transient-Onlooker/tg-note-agent)

Telegram으로 빠르게 기록하고 Web에서 정리하는 개인용 Capture & Workspace입니다.<br/>
Cloudflare D1에서 **입력 원문(`captures`)과 수정 가능한 항목(`items`)을 분리**해 기록을 보존합니다.

Inbox·Todo·Projects·Purchase·Print Queue 등을 한곳에서 관리하고, WebSocket 변경 알림과 재조회로 화면을 최신화합니다. 삭제 복원·Undo·편집 실패 시 draft 복원으로 작업 안정성을 높였습니다.

[tg-note-agent](https://github.com/Transient-Onlooker/tg-note-agent)은 별도의 FastAPI·SQLite·NVIDIA NIM 기반 초기 실험으로, 명령어 기반 기록과 수정·삭제 전 승인 흐름을 검증한 프로토타입입니다.

**주요 특징**

- Telegram webhook과 Web Quick Capture 기반 기록 수집
- Cloudflare D1의 `captures`, `items`, `projects` 기반 원문 보존·관리 구조
- Inbox, Todo, Today, Notes, Projects, Purchase, Print Queue, Archive, Trash Workspace
- 항목 분류·수정·soft delete·복원과 optimistic UI, Undo 흐름 구현
- 명시적 `/print` 명령어로 3D 출력 작업의 대기열·상태·순서 관리
- Durable Object + WebSocket 이벤트 수신과 TanStack Query 기반 실시간 최신화
- GitHub Pages Web 배포와 Cloudflare Worker API 배포 흐름 구성

**Tech**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare%20Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white)
![Cloudflare D1](https://img.shields.io/badge/Cloudflare%20D1-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Hono](https://img.shields.io/badge/Hono-E36002?style=flat-square&logo=hono&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-000000?style=flat-square&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

### 4. SIR Model Series

전염병 확산을 서로 다른 수학적 방법으로 구현한 탐구 프로젝트 시리즈입니다.  
**2차원 격자 기반 확률적 개체 모델 → SciPy 연립미분방정식 기반 모델 → TypeScript/RK4 웹 시뮬레이터**로 접근법을 발전시켰습니다.

**Repositories**

- [sir-model-classic](https://github.com/Transient-Onlooker/sir-model-classic.git)  
  S/I/R/V/Q/D 상태를 격자에 배치하고 확산·이동·방역 이벤트를 처리하는 Python 시뮬레이터

- [sir-model-differential-equations](https://github.com/Transient-Onlooker/sir-model-differential-equations.git)  
  SciPy solve_ivp를 사용한 기본 SIR 및 확장 SEIRS 계열 GUI 시뮬레이터

- [sir-model-diff-web](https://github.com/Transient-Onlooker/sir-model-diff-web.git)  
  TypeScript + Vite 기반 RK4 구획 모델 웹 시뮬레이터  
  [Demo](https://sir-model.mcv.kr/)

**주요 특징**

- NumPy 격자 기반 SIRVQ-D 확산과 이동·격리·정책 이벤트 시뮬레이션
- SciPy solve_ivp 기반 SIR/SEIRS 구획 모델 및 Python GUI
- TypeScript 웹 버전의 RK4 기반 수치 적분
- 변이·개입·백신 및 면역 파라미터 변경에 따른 결과 시각화
- 학습·탐구용 가정 모델로 실제 감염 규모 예측과 구분

**Tech**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

---

### 5. [BlocksTL](https://github.com/Transient-Onlooker/BlocksTL)

브라우저에서 STL 모델을 조립식 블록으로 분할하고, 3D 프린팅용 결합 핀과 실험적 스프링 소켓을 생성하는 로컬 전용 도구입니다.
서버 업로드 없이 Web Worker와 Manifold WASM으로 메시 분할·Boolean 연산을 처리하고, 분할 미리보기부터 생성 결과 검증, STL/ZIP 내보내기까지 하나의 흐름으로 제공합니다.

[Live Demo](https://transient-onlooker.github.io/BlocksTL/)

**주요 특징**

- Binary/ASCII STL 입력과 2~8개 Z축 블록 분할
- 고정 mm 치수의 결합 핀·실험적 스프링 소켓 및 19/20/21 맞춤 테스트 쿠폰 생성
- 다중 절단면 connector footprint 검증과 Three.js 기반 결과 QA·3D 점검
- Web Worker 기반 비차단 처리와 Manifold WASM 기반 메시 Boolean 연산
- 블록별 STL 및 전체 ZIP 다운로드, GitHub Actions 검증 후 Pages 자동 배포

**Tech**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-111111?style=flat-square&logo=threedotjs&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white)
![Web Worker](https://img.shields.io/badge/Web%20Worker-111111?style=flat-square)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

### 6. [rocket-3d-4all](https://github.com/Transient-Onlooker/rocket-3d-4all)

브라우저에서 실행되는 로켓 비행 시뮬레이터 프로젝트입니다.  
추력, 연료 소모, 항력, 중력, 대기 밀도, 바람 등의 요소를 반영해 비행을 계산하고, 결과를 2D 차트와 3D 뷰로 함께 시각화했습니다.

RK4 기반 수치 적분과 비행 이벤트 추출, 동기화된 2D/3D 재생에 더해 **미션 평가·비행 제약 검증·불확실성 분석·시나리오 비교**를 제공하는 교육용 비행 분석 도구로 구성했습니다.

**주요 특징**

- RK4 기반 로켓 비행 수치 시뮬레이션
- 추력, 연료 질량, 항력, 중력, 풍속 반영
- 2D 궤적 차트 + 텔레메트리 차트 + 3D 비행 뷰 동시 제공
- 재생 시점과 2D/3D 뷰 동기화
- 미션 분석·비행 검증 게이트·불확실성 분석·시나리오 비교와 GitHub Pages 배포 구성

**Tech**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=flat-square&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-111111?style=flat-square&logo=threedotjs&logoColor=white)
![React Three Fiber](https://img.shields.io/badge/React%20Three%20Fiber-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

---

### 7. [newomr](https://github.com/Transient-Onlooker/newomr)

OMR 답안 이미지의 마커와 버블을 브라우저에서 분석하는 채점 웹앱입니다.  
기존 `autoomr`를 개선해 **3개 기준 마커(TL·TR·BR)에 따른 회전·크기 정렬**과 Canvas 기반 버블 판독을 구현했습니다.

[Demo](https://autoomr.mcv.kr)

**주요 특징**

- React + TypeScript 기반 OMR 채점 웹앱
- 4개 모서리 영역에서 BFS로 마커 후보 탐색·노이즈 필터링
- TL·TR·BR 기준 회전·축별 크기 정렬 (Homography와 구분)
- Canvas 이진화·버블 내부의 검은 픽셀 비율로 답안 판정
- 그리드 매핑·답안 편집·디버그 화면 제공
- 기존 `autoomr` 이후 버전과 GitHub Pages 배포 구성

**Tech**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

---

## 🛠️ Tech Stack & Tools

### Main Languages

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

### Frontend / App

![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tkinter](https://img.shields.io/badge/Tkinter-FFD43B?style=flat-square&logo=python&logoColor=black)

### Backend / Cloud / API

![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white)
![Google Maps SDK](https://img.shields.io/badge/Google%20Maps%20SDK-4285F4?style=flat-square&logo=googlemaps&logoColor=white)
![Google Maps 3D SDK](https://img.shields.io/badge/Google%20Maps%20SDK-4285F4?style=flat-square&logo=googlemaps&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare%20Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white)
![Cloudflare D1](https://img.shields.io/badge/Cloudflare%20D1-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Hono](https://img.shields.io/badge/Hono-E36002?style=flat-square&logo=hono&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-000000?style=flat-square&logoColor=white)
![AdMob](https://img.shields.io/badge/AdMob-EA4335?style=flat-square&logo=googleadmob&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini%20API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white)

### Scientific / Simulation

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![SIR Model](https://img.shields.io/badge/SIR%20Model-Scientific%20Modeling-blue?style=flat-square)
![SEIRS Simulation](https://img.shields.io/badge/SEIRS-Simulation-blueviolet?style=flat-square)

### Tools

![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=flat-square&logo=androidstudio&logoColor=white)
![Gradle KTS](https://img.shields.io/badge/Gradle%20KTS-02303A?style=flat-square&logo=gradle&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Fusion 360](https://img.shields.io/badge/Fusion%20360-FF6600?style=flat-square&logo=autodesk&logoColor=white)
![Codex CLI](https://img.shields.io/badge/Codex%20CLI-111111?style=flat-square&logo=openai&logoColor=white)
![Gemini CLI](https://img.shields.io/badge/Gemini%20CLI-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

### Secondary / Used Before

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Bubble Tea](https://img.shields.io/badge/Bubble%20Tea-TUI-FF69B4?style=flat-square)
![Wails](https://img.shields.io/badge/Wails-Go%20GUI-DF0000?style=flat-square)

---

<details>
<summary>📁 Other Projects</summary>

<br/>

| 프로젝트 | 설명 | 기술 |
|---|---|---|
| [tokscale (기여 포크)](https://github.com/Transient-Onlooker/tokscale) | 여러 AI 코딩 에이전트의 토큰·비용을 분석하는 [Tokscale 원본 프로젝트](https://github.com/junhoyeo/tokscale)의 포크. OpenCodex combo 요청을 실제 처리 모델에 연결하는 Codex 사용량 귀속 로직을 구현해 [upstream PR #1400](https://github.com/junhoyeo/tokscale/pull/1400)으로 제안했습니다(검토 중). | ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![CLI](https://img.shields.io/badge/CLI-111111?style=flat-square&logo=gnubash&logoColor=white) |
| [TRINITY-OS (기여 포크)](https://github.com/Transient-Onlooker/TRINITY-OS) | [TRINITY-OS 원본](https://github.com/itsmekk-mario/TRINITY-OS)을 바탕으로 학습 기록에 수식과 함수 그래프를 작성·저장·재표시하는 패치를 작업한 포크. 기존 데이터 스키마를 유지하며 자체 수식 파서를 사용합니다. | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Math](https://img.shields.io/badge/Math-Rendering-555555?style=flat-square) |
| [MinimalMP3](https://github.com/Transient-Onlooker/MinimalMP3) | LG V30을 음악 플레이어처럼 사용하기 위한 Android 홈 런처. 검은 화면과 앨범 아트 중심 UI에서 Spotify·Samsung Music 등 설치된 음악 앱의 MediaSession을 제어하고, 앱 서랍·런처 전환·재생 제어를 제공합니다. | ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white) ![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white) |
| [arcacon-downloader](https://github.com/Transient-Onlooker/arcacon-downloader) | 아카콘 페이지 링크에서 상품 이미지를 수집하고 GIF로 변환하는 Python CLI. 브라우저 프로필 기반 로그인 유지, 병렬 수집, FPS·출력 폭·헤드리스 실행 옵션을 지원합니다. | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white) ![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white) |
| [seoul3dmetromap](https://github.com/Transient-Onlooker/seoul3dmetromap) | 서울 지역을 격자로 나누고 각 위치에서 가장 가까운 지하철역까지의 거리를 2.5D 막대맵으로 시각화한 웹앱. 열린데이터 기반 좌표 처리와 정적 JSON 데이터 생성 흐름 구현 | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| [step-only-android](https://github.com/Transient-Onlooker/step-only-android) | 외부 통신 없이 기기 내 걸음 수 센서와 로컬 DB만 사용하는 오프라인 만보기 앱. Foreground Service와 센서 delta 누적 방식을 구현 | ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white) ![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white) ![Room](https://img.shields.io/badge/Room-3DDC84?style=flat-square&logo=android&logoColor=white) |
| Vocab Generator Series | AI 기반 영어 단어장 생성기 시리즈. [gemini-vocab-generator](https://github.com/Transient-Onlooker/gemini-vocab-generator.git)와 [chatgpt-vocab-generator](https://github.com/Transient-Onlooker/chatgpt-vocab-generator.git)로 Gemini API 기반 Python GUI, OpenAI API 기반 Go TUI 흐름을 실험 | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Tkinter](https://img.shields.io/badge/Tkinter-FFD43B?style=flat-square&logo=python&logoColor=black) ![Gemini API](https://img.shields.io/badge/Gemini%20API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![OpenAI API](https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) |
| [WorldWords](https://github.com/Transient-Onlooker/WorldWords) | 영어 단어 학습을 위한 Kotlin 기반 안드로이드 앱. Jetpack Compose 계열 구조와 모바일 학습 UI/UX를 실험 | ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white) ![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white) |
| [se3cdocs](https://github.com/SE3C/se3cdocs) | SE3C 동아리 공식 문서 포털. Markdown 기반 문서를 React로 렌더링하고 커스텀 도메인으로 배포한 문서화 웹사이트 | ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) |
| [openjacks](https://github.com/Transient-Onlooker/openjacks) | React + Express 기반 웹앱. API 서버 연동 구조와 배포 설정을 포함한 웹 프로젝트 | ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) |
| [chat-application](https://github.com/Transient-Onlooker/chat-application) | WebSocket 기반 실시간 채팅 서버/클라이언트 | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![WebSocket](https://img.shields.io/badge/WebSocket-000000?style=flat-square&logoColor=white) |
| [golf-schedule-generator](https://github.com/Transient-Onlooker/golf-schedule-generator) | JSON 입력 기반 골프 대회 일정 자동 생성 GUI 툴 | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Tkinter](https://img.shields.io/badge/Tkinter-FFD43B?style=flat-square&logo=python&logoColor=black) |
| [personnel-management-spreadsheet](https://github.com/Transient-Onlooker/personnel-management-spreadsheet) | 인원 관리용 Python 데스크탑 앱. 실행 파일 빌드까지 포함한 도구형 프로젝트 | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Tkinter](https://img.shields.io/badge/Tkinter-FFD43B?style=flat-square&logo=python&logoColor=black) |
| [music-box-score-converter](https://github.com/Transient-Onlooker/music-box-score-converter) | 오르골 악보 숫자 표기를 MIDI로 변환하는 Python 스크립트 | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![MIDI](https://img.shields.io/badge/MIDI-5A4FCF?style=flat-square&logoColor=white) |
| [kim-game](https://github.com/Transient-Onlooker/kim-game) | Python 기반 미니 게임 프로젝트 | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |

</details>

---

<details>
<summary>🧪 Archived / Experimental Projects</summary>

<br/>

| 프로젝트 | 시도한 것 | 배운 점 |
|---|---|---|
| [chatgpt-vocab-generator-wails](https://github.com/Transient-Onlooker/chatgpt-vocab-generator-wails.git) | ChatGPT 단어장 생성기의 Wails GUI 버전 | Go/Wails 기반 GUI 앱의 크로스 컴파일 제약 확인 |
| [chatgpt-vocab-generator-python](https://github.com/Transient-Onlooker/chatgpt-vocab-generator-python.git) | Python 기반 ChatGPT 단어장 생성기 | Python 앱 배포와 크로스 컴파일의 한계 확인 |
| [autoomr](https://github.com/Transient-Onlooker/autoomr.git) | 초기 OMR 자동화 프로젝트 | 3모서리식 알고리즘 도입 후 `newomr`로 구조 개선 |
| [HWPXport](https://github.com/Transient-Onlooker/HWPXport.git) | 시험지를 HWP 형식으로 생성하는 앱 | HWPX 문서 구조의 복잡성과 자동화 한계 이해 |

</details>

---

<details>
<summary>📊 GitHub Activity & Stats</summary>

<br/>

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Transient-Onlooker&theme=tokyo-night&hide_border=true&area=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

<br/>

[![Tokscale Stats](https://tokscale.ai/api/embed/Transient-Onlooker/svg?compact=1)](https://tokscale.ai/u/Transient-Onlooker)

<br/>

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Transient-Onlooker&layout=donut&theme=codeSTACKr)

</details>

---

## 💡 관심 분야

항공우주공학 · 수치 시뮬레이션 · 웹 서비스 개발 · 시스템 설계 · AI 개발 도구 · 자동화

---

## 🔗 연결

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:swapomit@gmail.com)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.com/users/nomoregimal)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Transient-Onlooker)

질문이 있으신가요?  
[Issues](https://github.com/Transient-Onlooker/Transient-Onlooker/issues)를 통해 연락해주세요.

---

> **0.1%의 창의적 인간이 미래를 발명하고, 0.9%의 통찰력 있는 인간이 그것을 사업화하며, 99%의 잉여인간은 역사의 변화를 모른 채 따라갈 뿐이다. (제레미 리프킨)**
